# Giffygram Instructions

For this project, you will be building a web application that lets people post their favorite gifs. Each post can be favorited by other users, and deleted by the original author. Users can also send direct messages to each other, and be notified when they have messages.

### Starting the API

Open a terminal window and go to the `giffygram` directory.

1. `cd api`
1. `cp db.json.example giffygram.json`
1. `json-server giffygram.json`

### Starting the Web Server

Open another terminal window and go to the `giffygram` directory.

1. `cd src`
1. `serve`

Use the assets that you created during the deconstruction phase to construct your own working version of Giffygram.

## Using Github

### Issue Tickets and Projects

1. Once your team defines all of the features that need to be built for the application, create an Issue for each one.
1. Create a project for your repository.
1. Create the following columns in your project
    * Backlog
    * Doing
    * Ready to test
    * Done
1. Add each issue to your Backlog column.

Each teammate then drags one issue from the Backlog to the Doing column, and assigns themselves to the issue. You are now accountable for making sure that issue gets done.

You and all of your teammates **share the responsibility** of getting it done. No one works alone. It doesn't matter how many of your teammates you ask for help, as long as you ensure that the issue gets completed during the sprint.

### PR Templates

Create a file named `PULL_REQUEST_TEMPLATE.md` in your repository and place the following content into it. Every new PR you create will have this structure automatically.

```text
#### Changes Made
1. Added file `filename` to `directoryname` directory.
1. Modified file `filename` to include `functionalityname` and functionality.
​
#### Steps to Review
1. Checkout this branch locally.
    ```
    git fetch --all
    git checkout branchname
    ```
2. Open a new Terminal tab (⌘T) and navigate to the server directory.
3. Test app functionality.
    > Instructions for how reviewer can test functionality, and detailed description of what the expected outcome is.
    > Example: When user does BLANK, then BLANK should happen.
4. View code file.
    > Confirm file modifications are present as indicated above.
    > Confirm no unused code or extraneous comments exist.
```

### Team Completion -- Project by Brittany, Chelsea, Duley & Nick
The project was to be completed in roughly two weeks. I (Brittany) was given the leadership role to aid in completion of the project and help my classmates with any questions/tasks they were in need of help with. 

My tasks were to help structure the site as the guided example provided, including how it functioned and looked. The initial project was given to the group broken. Within this project I worked on: 
1. Successfully connecting the proper code for render of the app's home page
2. The direct message form
3. The message mailbox for successful receipt of messages and return button to home page
4. Getting the logout link to route successfully to the login page
5. Filtering features towards the bottom of the page including getting the main feed's posts to filter by year, author/user name and/or favorited posts.
6. Favorite/unfavorite feature for individual posts
7. Overall CSS for clean usage and styling

### Team Kudos
Nick: 
"dooley has been so humble throughout this whole project and everyone has been very kind and easy to work with."

Chelsea: 
"I want to give kudos to the whole team (Duley, Nick, Brittany, and myself)  for contributing in all the ways that they could with what we could come up with on our own and as a whole. A big kudos to Brittany for making sure everyone was staying on track and leading the group with her determination and knowledge that helped all of us the in the learning process."

Duley: 
"Chelsea seems to always ask the right questions which brings things to a practical epiphany leaving you asking yourself "why didn't I think of that?" She is extremely encouraging and supportive of the team setting."

"Nick is a secret code op. He has some major retention skills and insight on how to approach things from a different perspective."

"Everyone stayed engaged and eager to learn. We all went hard and got to see what it was like problem-solving as a group where all input and ideas can help move things forward."

"Brittany is going to go places with her work ethic and attention to detail. I seriously think she codes in her sleep. Her role was pivotal to jumpstarting the team and keeping everyone in the loop. Brittany puts leadership on her back and rides into the sunset while bringing the team along for the amazing journey. Peer-to-peer learning is dope."

Brittany: 
"Kudos to all three of my teammates for being supportive and encouraging during all ups and downs of this project. When things would break, everyone was always positive and willing to look for solutions via google or previous projects. Every one of my teammates showed their strengths and had no problem admitting to any weaknesses, but that never stopped them from trying. Diligence, great spirits and teamwork would be the three phrases I use to sum up my time working with them!"

"Kudos to Chelsea and Duley for being so involved and eager to learn! They both helped with structuring the visual HTML for our Giffygram which was gave us the ability to keep working out the kinks and functionality of key components. We alternated group times together but spent late hours knocking things out and even when things were’t super clear or thoroughly understood, they both brought positive attitudes, suggestions and help at every meet up! And regardless of knowing the solution or not, they were willing to test their scope of knowledge at every turn. Kudos to Nick for executing the functionality of the form to input the gif information and send to the API properly. I know there were several times he had to work late hours and/or had issues with his laptop but he still came through!"