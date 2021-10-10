## Welcome to Manabie coding challenge

*Hello!*
*We're excited that you're interested in joining the Manabie. Below are the requirements and explanations for the challenge.*

### Notes: 
- Our challenge codebase is based on create-react-app with typescript.
- All provided codes are in this repository. Please fork, complete your challenge, and create a PR for us.
- We judge your codes:
    - Easy to understand.
    - Well organized.
    - Performance.
    - Test cases.
    - Your behavior when approach a new technology.
- Dont worry if you cant complete the challenge in time. Just do your best in a mindful way.
- If you can't fully complete the challenge , please note the completed features.
    
### Simple app diagram
![App diagram](diagram.png)

### Requirements

#### Common (required for both positions)
- Our code base has some strange bugs and anti-patterns, please help us find and fix these (please comment the reasons why you change it).
- Write some tests (prefer unit tests as it can save your time) to persuade us that what you had ADDED or FIXED are correct.

#### Front-end engineer
- For front-end engineer, you can use localStorage instead of calling remote APIs.
- We provided you a simple UI for todo app, please enhance it with your creative mind (We prefer not using any CSS framework as we want to see your CSS skills).
- Please help split huge code blocks in App.tsx into reusable UI components.
- Please help us add some features to the application by:
    - Implement the persistent feature. After refreshing, our todos will be disappeared, that's annoying for our users, let's use localStorage (or API calls for fullstack engineer) to keep them.
    - Implement the edit feature. Currently, users cannot edit the todos, please help them (user double-click the todo to edit, press enter to apply the changes, or click outside to discard).

#### Fullstack engineer
- You have to make sure your code satisfy the back-end requirements in https://github.com/manabie-com/togo.
- We do not require you to enhance the UI, but it is preferable.
- Done the common requirements above.

### How to run this code
- Run ```yarn``` or ```npm install``` if this is the first time you clone this repo (`master` branch).
- Run ```yarn start:fullstack``` in case you are doing a fullstack test, else run ```yarn start:frontend``` to start this project in development mode.
- Sign in using username: `firstUser`, password: `example`

Last updated: 2021/08/01
