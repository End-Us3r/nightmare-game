# adventure game

Adventure Game Description:

    Overview: The adventure game allows the player to navigate between various locations and make choices that influence the game's outcome.

    Game Flow:
        The game starts from the main function, displaying a welcome message and prompting the user to begin.
        Initially, the player is situated in the field location.
        From the field, the player can move to either home or forest.
        From home, choices include moving to the forest or retrieving a sword item.
        In the forest, players may encounter a bear event or proceed to the mountain.
        At the mountain, options include returning home or entering the cave.
        Upon entering the cave, the game concludes with a final message.

    Code Elements:
        The game employs functions like 'field', 'home', 'forest', 'mountain', 'cave', and 'bearAttack' to represent different locations and events.
        A boolean variable 'hasSword' tracks whether the player has acquired the sword item.
        The Sleep() function from windows.h library is used to pause output, enhancing immersion.
        User input is handled via cin, with error messages and recursion ensuring valid commands.
