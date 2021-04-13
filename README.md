# Chat Interface Test
Welcome to the Fuzzy Android chat interface challenge! Just to kick things off, let's clarify some initial questions you may have:

#### How long do I have to work on this?
We want to respect your time so we tried to keep this challenge scoped down small enough that you shouldn't need to spend more than an hour or two on this. If you find yourself spending more time than that, we'd encourage you to stop and submit your solution anyways. We are primarily interested in discovering your thought process behind your implementation.

#### How do I submit my work once I'm done?
We want to learn a little bit about how you like to communicate along the way, so we'll leave this one a bit open-ended. Typically the easiest route looks something like this:
1. Push this repo up to a private (please don't share!) repo on your own Github
2. Create a PR (or multiple if you prefer) for your changes
3. Invite the hiring manager who invited you to this challenge as a collaborator on your repo once you've completed the task. If they haven't informed you of their e-mail or github username, please don't hesitate to ask!

### Instructions
You will find chat data under data.json in the assests folder. Your task is to create a simple chat interface to display these chats. You do not need to implement any user input.

- You need to implement a delay so that each message will display in the order it came in (descending order of the data) with a 1.5 second interval between each message.
- You can use the incoming and outgoing layout files. Please create simple message layouts using the suzy image from Assets for the incoming message layout and the user image for the outgoing message layout.
- See the reference image (chatbot.jpg) for an example of how it should look.

#### Important Note
The chat messages must start at the bottom of the screen and move upwards. See chatbot.mp4. You do not need to replicate the chatbot exactly, but you do need to ensure the messages start at the bottom and fill the screen upwards as shown in chatbot.mp4.

#### Bonus
Bonus points: display "Suzy is typing..." message during the 1.5 second delay between receiving messages and or implement a method to replace `[NAME]` with your name as chats are inserted.
