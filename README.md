How to use it in your local system
First install mongodb community server on your device by going into the mongodb websites and then download mongodb community server
Once you download the mongoDb community server then just open your terminal and run the command as npm install
After running the command , it will download all the libralries needed to run this project.
For using This project , You need the postMan and Mongodb Compass getting the documents saved in you database.
just Download the MongoDb Compass and PostMan from the browser.
<h1>How to use PostMan</h1>
Open PostMan
Enter The Url into the postMan with the required Method and data to pass with the request
Then just Note The Change in your database.

<h2>URL That I Have Created:</h2>

http://localhost:8000/questions/create (To create the questions)

http://localhost:8000/questions/:id/options/create (To create the options of a particular questions)

http://localhost:8000/options/:id/add_vote (To add a vote for a Particular Option)

http://localhost:8000/questions/:id (To get the details about the particular question)

http://localhost:8000/questions/62ff5f8d8989690a30403f31/delete (To delete a Particular Question)

http://localhost:8000/options/62ff61c492d525ac764ec787/delete (To delete a particular option)

<h1>Note</h1>
A question can’t be deleted if one of it’s options has votes
An option can’t be deleted if it has even one vote given to it
