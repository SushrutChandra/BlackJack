# BlackJack
This project is an object-oriented Java implementation of the classic Blackjack (21) game. The focus of the project is on building a fully functional game engine that handles shuffling, dealing, hand evaluation, betting, and game status. A pre-built Swing-based GUI is used to interact with the engine.

🎯 Features
Complete backend implementation of the Blackjack game:

Multi-deck support

Player actions: hit, stand

Dealer logic and hand evaluation

Bet and account management

Game outcome resolution

GUI integration (provided)

Interacts with engine through the BlackjackEngine interface

Displays real-time card updates, scores, and game status

🧠 Object-Oriented Design Highlights
Blackjack class implements BlackjackEngine interface for clean separation between logic and UI

Encapsulated state: deck, hands, bets, account

Use of enums for card suits and values (CardSuit, CardValue)

Card class manages properties like face orientation and printed representation

🧰 Data Structures & Techniques
Arrays (Card[]) to manage hands and decks

Enum types for clarity and type safety in card representation

Custom class hierarchy (Card, Blackjack, etc.) following standard OOP principles

Event-driven programming in the GUI (not written by me, but integrated via interface methods)

💻 Technologies Used
Java 8+

Swing GUI (provided template)

Java standard libraries (Random, Array, AWT/Swing, etc.)
