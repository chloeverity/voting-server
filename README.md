# Voting Server

React/Redux tutorial by https://github.com/teropa

App that organises live votes, putting options together in pairs, like bracket voting. When there's just one left, that's the winner.

Will use 2 separate user interfaces: Voting UI and Results UI.

The system will consist of 2 applications, there's a browser app (React) that provides both the UIs, and a server app that handles the voting logic (Node). The communication between the two will be handled using WebSockets. Redux will be used to organise the application code on both the client and on the server. For holding the state we'll use Immutable data structures.

### Aims for this project
* Improve my TDD instincts for React
* Get the hang of Redux
* Get a better understanding of WebSockets
* Get more familiar with Mocha and Chai
