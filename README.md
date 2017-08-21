# Spam-Button

I have decided to start releasing more of my past work in hopes of helping others improve their Cybersecurity. This little project is what I like to call the "Spam Button" It is an Outlook add-in that adds a spam button on the top toolbar that any user can press then it will send the email to a predefined email address and delete it from the user's inbox.

You might ask so what? Well, the spam button does not simply forward the email. It wraps the original suspicious email as an attachment then sends it over. This helps preserve a lot of metadata that can be priceless for SOC analysts.

To use this tool, all you have to do is change the line of code in the ThisAddin.cs to whatever your spam mailbox is.



tosend.To = "Example@gmail.com";//Set the To equal to whatever the email address is for the spam mailbox.;



Change that, then install on a computer and you are good to go.


