# Buzzz the app to buzzer (and more)
This apps core functionality is to provide a buzzer to the user, that they can press and a host view, that shows the host, which user pressed the buzzer first (or a list with the squence of buzzer presses). It can be used when doing something like a quizz or other games with your friends (or a youth group).
This is a rough concept of the app and will develop over time. 
# Planned features
## Base version 
The first version of the App will only be available as a web app. There will be two seperate UIs. One for the host of the game, one for the participants.
### Host UI
The host UI will require a log in with a host account.
After logging in, the host can create a game and share the invitation url. The Host is presented with a view that shows all participants and allows the host to start and finish a buzzer round, as well es reset the result list (this should be automatically done, when a new buzzer round is started).
### Participant UI 
The participant UI will either require a game session id or lead to a prompt for a user name, depending on if the participant followed an invitation url or just opened the apps page. There needs to be some way to restore a session, in case a participant messes up. A first Idea would be for the host to be able to provide a restore code for an existing participant. 
After entering an username, the participant is brought to the buzzer UI, which will in a first version just show the buzzer for the user to press (and maybe an indicator if a buzzer round is going)
### User management
There needs to be a way to manage the hosts that have access to the game. A start could be one or two hardcoded users, but there needs to be some kind of management for the user.
## Ideas for future versions
* Have an actual app installed on the users devices.
* Host should be able to provide a qr code
* More features than just buzzing (buzzering? what's the correct term here?)
  * Build in quizz functionality users get asked a question and is presented with possible answers (can be )
  * Survey the user (difference between quizz and survey is the amount of questions and them being quickly created)
# About this repository
As I'm looking into the structure of this type of project for now there will be a repository for the frontend and one for the backend and this one will contain documentation and planning about the project. This will likely change in the future.
Backend: https://github.com/rhaecker/buzzz-backend.git