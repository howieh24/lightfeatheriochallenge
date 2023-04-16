Hello Lightfeather.io,

After some extensive tests, the docker desktop app would not work on my computer, although I am sure that if I had more time I could figure out how to make it work
but with my limited time and resources it was not an option. 

I will write a detailed description of how to run the Front and Back end code that I do have which follows the instructions for the Full Stack Challenge. 

First would be to unzip both LightfeatherChallenge-Frontend and LightfeatherChallenge-Backend. 

The Frontend is ran through Angular which can be started up through VS code (preferrably)

After starting the application, it should lead to the localhost:4200 page where you (the user) will be prompted to enter the first name, last name, email, 
phone, and select from a list of supervisors pulled from the aws list link that was provided. In order for this list link to work however, the Backend must be up and 
running. 

Unzip the Lightfeatherio-Backend folder and import it into Eclipse as an existing maven file. Run said application as a Java Application. Once that is running, any inputs
entered in through the Frontend will show up as messages in the Console here. 

The first part of the Backend will take the list from the aws link and sort it based on Jurisdiction alphabetically and then exclude out all numbered jurisdictions. 

This will then send said information back to the Frontend to be displayed in the dropdown menu. 

After user selects all their information, if the form is filled corrected, the user will get a Success message passed back in the Console. If the user missed the first name,
last name, or supervisor. They will get a error message telling them that they missed a section. 

This essentially breaks down all the parts of the program and what I managed to finish within this 48 hour challenge. 
