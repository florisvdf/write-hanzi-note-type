# write-hanzi-note-type

This repository contains a single card deck and the main components of the note type for practicing writing hanzi that relies on the [hanzi-writer](https://github.com/chanind/hanzi-writer) library. I created this for myself to be used alongside a sentence mining deck. The purpose of this repository is therefore to provide users with a very minimal note type that they can use to add their own cards of hanzi they wish to practice.

The current version is a very quick and dirty implementation, as I virtually have no knowledge of html, css or javascript. I used much of the [anki-xiehanzi](https://github.com/krmanik/Anki-xiehanzi) code as a source of inspiration and prompted ChatGPT to arrive at a functioning version of the note type. If you are looking for a premade deck with many more fleshed out features, I highly recommend checking out anki-xiehanzi. 


# Features

- Practice writing hanzi by drawing strokes
- Add up to four characters in a single card
- Reveal the character or stroke order by pressing the "toggle character" button
- An image field for adding images of the source of the mined character to the back of the card
- Two audio fields: One for the word and one for a spoken mined sentence when one exists
- A border around the character container indicating the status of the character (red: character not loaded, green: character loaded, blue: problems importing the hanzi-writer library).

## Front
![Front](https://github.com/user-attachments/assets/4b7ebc61-fd75-45e6-a6d0-fccd60cd55b1)


## Back
![Back](https://raw.githubusercontent.com/florisvdf/write-hanzi-note-type/main/assets/back.png)


# Missing features/issues
- Character container alignment and sizing
	- The character container is not large enough
	- The character container changes location after the first character when the card contains more than one character (center to top left)
	- The character container does not fit the screen dynamically when used on mobile (anki mobile, ankidroid)
- Characters are fetched online, therefore the user needs to be connected to the internet in order to use the deck

Contributions to address these issues are very much appreciated! Just send a pull request with a short description of the changes.

