# Game of the Generals

## AI Assistance
This project was built with the assistance of AI (Claude by Anthropic). 
I directed the design and made the decisions about features, rules, and scope, and AI helped with parts of the code and planning. 
I reviewed and tested the results myself.

## Overview
This project is a browser-based adaptation of Game of the Generals (also known as Salpakan), a two-player Filipino board game of hidden information and deduction. 
The game is deployed as a website where players connect by joining a shared room with a 5-digit passcode. 
Original rankings, piece designs, and artwork are kept as close to the board game as possible. 
This is a non-commercial alpha, and the game's rights are not held by the developer.

## Features
Multiplayer is peer-to-peer using PeerJS, with a dedicated relay server to connect players when a direct connection is not possible. 
Players can also play solo against AI opponents. 
Since pieces are hidden from the opponent, clicking an enemy piece opens a checklist of the ranks it could still be, based on what has been revealed during play. 
This keeps track of the deduction a player would otherwise do mentally.

## Tech Stack
The game is written in vanilla JavaScript and CSS, with no front-end framework. Multiplayer uses PeerJS, and the relay server is hosted separately from the client.

## Roadmap
The current goal is a small, polished alpha to gauge demand (e.g. on itch.io). 
If there is interest, the next step is to approach the game's creator's family about securing the rights, with a possible Steam release afterwards.

## Credits
Game of the Generals was created by Sofronio H. Pasola Jr.
