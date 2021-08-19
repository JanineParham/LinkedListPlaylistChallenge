# LinkedListPlaylistChallenge
This project is from a Udemy course called Java Programming Masterclass. It is one the challenges presented in the course. I used this challenge to practice basic manipulation of a Linked List in Java.

## Create a program that implements a playlist of songs.

###  To start off, implement the following classes:
1. Album
- It has three fields, two Strings called name and artist, and an ArrayList that holds objects of type Song called songs.
- A constructor that accepts two Strings (name of the album and artist). It initialises the fields and instanties songs.
- And three methods 
  - addSong(), has two parameters of type String(title of song), double (duration of song) and returns a boolean.Returns true if the song was added succesfully or false otherwise.
  - findSong(), has one parameter of type String (title of song) and returns a Song. Returns the Song if it exists, null if it doesn't exist.
  - addToPlaylist(), has two parameters of type int (track number of song in album) and LinkedList(the playlist) that holds objects of type Song, and returns a boolean. Returns true if exists and it was added successfully using the track number, or false otherwise.
  - addToPlaylist(), had two parameters of type String (title of song) and LinkedList(the playlist) that holds objects of type Song, and returns a boolean. Returns true if it exists and it was added successfully using the name of the song, or false otherwise.
  
 2. Song
 - It has two fields, a String called title and a double called duration.
 - A constructor that accepts a String (title of song) and a double (duration of the song). It intialises title and duration.
 - And two methods, they are:
  - getTitle(), getter for title.
  - toString(), Songs overriding toString method. Returns a String in the following format: "title: duration"

### Once the songs have been added to the playlist, create a menu of options to: -
- quit
- skip forward
- skip backward
- replay the current song
- print the current playlist
- print the menu options
- delete the current song

