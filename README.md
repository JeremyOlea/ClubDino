# ClubDino
Created for CalgaryHacks 2022
Won Best UX/UI Design
https://devpost.com/software/club-dino
## Inspiration
We all loved online web MMOs as kids - Club Penguin, Habbo Hotel, the list goes on! They were representative of a simpler time, where you could hop on, meet your friends, make new ones, and play fun games. 

## What it does
Club Dino is a multiplayer game where anyone can have the University of Calgary experience - with no installations, right on the web. Users can visit two iconic U of C locations - TFDL and Mac Hall - where they can chat with others, play ping pong, and even study! And, to make sure students don't get too lost in our virtual world, studying earns Dino Creds, our virtual currency. In the future, students can even use Dino Creds to purchase cool customizations for their character, and food in our (virtual) Mac Hall.

## How we built it
Club Dino uses JavaScript and Phaser to run the game - that's right, it runs right in the browser. It uses socket.io to communicate in real-time with our Express server, which manages our lovely multiplayer experience. We also used Tiled to turn our collection of art assets into the real, playable map that you see here. 

## Challenges we ran into
This was our first time using Phaser, and for many of us, our first game development experience! We had to learn a lot of its fundamental concepts (like scenes, and importing sprites) from scratch. We also had a lot of challenges making it a multiplayer game where players can see everyone else's movement and chat.

## Accomplishments that we're proud of
It works! As you can see in our demo, it's capable of handling quite a few players spending time at iconic UCalgary locations and chatting away.

## What we learned
Game development is very hard! (One of us had to label every frame of animation in the character's walking animations). Also, game development is very fun.

## What's next for Club Dino
- Character customization
- Temporary buffs ("food") that recreate the Mac Hall Experience
- More fun mini-games, like Wordle :)
- Full account creation and signup
