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
- Room owner can kick other people out of the room.
  - Rationale: The game only start if it has at least two players.
  - Originator: THANH PHAM.
  - Fit Criterion: Owner should be able to kick at most 1 player.
- Users have the ability to quit the waiting room.
  - Rationale: There may be some toxic player.
  - Originator: THANH PHAM.
  - Fit Criterion: I do what I want.
### Nonfunctional Requirements
- Real-time chat must be quick.
  - Rationale: If communication is delayed, it would cause hassle to the participants.
  - Originator: Thien.
  - Fit Criterion: The message should be sent and displayed at the other side within 500ms.
- Pong gameplay must not seem lagging.
  - Rationale: Lagging would cause confustion to players when they know they got it, but they fail it because of lagging.
  - Originator: Thien.
  - Fit Criterion: Gameplay smoothly display players activity.
