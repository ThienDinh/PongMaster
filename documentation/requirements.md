# Pong Master
![Game Homepage](pongmaster.png)
## Requirements Specification
### Constraints
1. This is a one week project. The end day is June 24th, 2017.
### Functional Requirements
- Users can see the rooms list or lobby.
  - Rationale: Naming the room is the only way to show a player's characteristic in the game. For example, one can name their room as "The best Pong player ever" to propose a challenge to other players. Another may name their room as "Come and play, my friend" to friendly ask someone to play with them. Some may name their room "covfefe".
  - Originator: Thien.
  - Fit Criterion: The title of the room should be able to display at least 10 words.
- Users can chat in lobby.
  - Rationale: Sometimes people may just want to socialize or take a break. Chatting is a good way to satisfy their needs.
  - Originator: Thien.
  - Fit Criterion: Players should always feel ready to start a conversation in the lobby.
- Users can use emoji in chat and title.
  - Rationale: Text alone is not expressive, so little emoticons would make it more interesting, and it's also fast and easy to be embeded.
  - Originator: Thien.
  - Fit Criterion: Users should be able to insert at most 5 emoticons in the title of the room or in a single message.
- Room owner can invite other people into the room.
  - Rationale: The game only start if it has at least two players.
  - Originator: THANH PHAM.
  - Fit Criterion: Owner should be able to invite at least 1 player.
- Host can set password when creating a room.
  - Rationale: Setting room password will prevent unwanted players to join.
  - Originator: Thien.
  - Fit Criterion: Players should feel comfortable to host a room.
- Users have the ability to quit the waiting room.
  - Rationale: There may be some toxic player.
  - Originator: THANH PHAM.
  - Fit Criterion: I do what I want.
- Users who create a room and await for other players can see the global chat (lobby chat).
  - Rationale: Showing global chat helps players know that server is still online, also he or she can ask other players to join.
  - Originator: Thien.
  - Fit Criterion: Players should see the global chat continously updated.
- Users have to enter their names at the homepage, before going to the lobby.
  - Rationale: The game does not require players to create user account, so they have to enter their name everytime they come to the web game.
  - Originator: Thien.
  - Fit Criterion: Users should be able to create names using alphanumeric characters.
- Players in the room should see each other's names on each side.
  - Rationale: Since the pong game is drawn in black and white only, not showing which side the player is playing will lead to confusion.
  - Originator: Thien.
  - Fit Criterion: Players always see each other's name easily.
### Nonfunctional Requirements
- Real-time chat must be quick.
  - Rationale: If communication is delayed, it would cause hassle to the participants.
  - Originator: Thien.
  - Fit Criterion: The message should be sent and displayed at the other side within 500ms.
- Pong gameplay must not seem lagging.
  - Rationale: Lagging would cause confustion to players when they know they got it, but they fail it because of lagging.
  - Originator: Thien.
  - Fit Criterion: Gameplay smoothly display players activity.
