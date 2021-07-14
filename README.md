# MEL-practice
MEL-dyn-practice  Mule Expression Language Examples  These examples introduce some basic implementations of Mule Expression Language (MEL). Each example includes a step-by-step guide for creating the flow in Studio’s visual editor or in XML. You can also jump straight to the complete code for all six examples, which you can copy and manipulate further in your own applications. 

Example 3 – Variable Assignment and Evaluating Conditions

In this example, the service saves a CSV file with user data besides just returning a greeting. The call to the service now includes two parameters, username and age. The service stores these two parameters and adds a third boolean parameter that evaluates if the user is above a certain age (if age is > 18). In this example, you uses MEL to:

 - Generate an output based on evaluating the input
 - Access an inbound property
 - Dynamically set the payload


We played with connectors and decided we will not use the flow Variable this time and added a choice router to allow us to have different possible conditions. Since we want to still have a final answer (message), if one or both conditions were missing . -- We'll test our API and remove the first or second or both parameters and see if it gives us a possible final answer and it worked. 

It did work with all the conditions.
