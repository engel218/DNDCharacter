# D&DCharacter
Application for creating a virtual Dungeons & Dragons character sheet.

# Requirements definition
The D&DCharacter application has separated folders, also called games, which consist of the character sheets for player characters in that game. There are two types of user profiles: Game Master (GM) profiles that can see all character sheets in a game they’ve created and Player profiles that can see only the character sheet they have created.

Users can:
* register and log in to the system
* see their own character sheets or games depending on their profile type
* create a new character sheet
* add an existing character sheet to a game
* GM users can create a folder (game) for players to add their character sheets into

The character sheet includes:
* fillable text fields for basic information such as name, race, class, etc.
* number field for character level that calculates the proficiency bonus for character
* number fields for character’s ability score, the app calculates character’s ability modifier based on this number
* number field for tracking character HP
* equipment that can be defined an ability and dice it rolls with

The application has dice functionality for the following dice (number indicates the sides of the dice): D20, D12, D10, D8, D6, D4

The application saves information locally, its purpose is to allow game nights to focus more on roleplaying and less for repetitive maths functions such as rolling damage in a fight!
