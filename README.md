# pyplayingcards
Repository for the pyplayingcards module on PyPi.

This module allows you to create and modify playing cards and dice objects in Python. With only the standard library module random as a dependency, the pyplayingcards module is an easy-to-use, well documented way of adding playing cards to your code.

As this is a simple project, the documentation is within the code itself. Feel free to fork, clone, copy and use any of the code in the module. For more information, see the LICENSE file on the GitHub page.

I learnt a lot of good coding practices from this project, and I hope it will help you have an easier time doing whatever card thing you're doing. Enjoy!

**Installation:**

`pip install pyplayingcards`

**How to use, basics:**

There are four classes in the pyplayingcards module:

PlayingCard

PlayingCards

Deck

Die

All four of these classes are relatively simple to use.
The PlayingCard class defines a simple class for normal playing cards.

The PlayingCards class defines either a randomly generated list of PlayingCard objects or a user-defined list of PlayingCard objects, with various other features.

A Deck is inherits from the PlayingCards class, but with the default values of a normal deck of cards and other methods.

A Die is a pathetically simple class for, well, a die, added only for completion.


For an actual understanding of the inner-workings of the pyplayingcards module, it is recommended that you look at the source code on the GitHub page, as it has a ratio of documentation to code of nearly three.

_Happy coding!_

**The GitHub page I keep talking about:**

https://github.com/DaJodhi/pyplayingcards
