# Research Questions #

In this paper,I will discuss 3 research questions; how spellcheck systems are different for various languages, how the quality of spell checkers are evaluated, as well as how the design of a spellchecker can reflect the classic debates in linguistics on the nature of the lexicon.

## Summary ##

Spellcheck systems differ across languages due to the fact that the languages themselves differ as well. The process of how the language itself is produced should then be reflected in a spellcheck program designed for that language. English, as an example of a language with an extensive lexicon, with rather few rules to accompany them is quite different than Inuktitut, which could be classified as a language that has a relatively small lexicon with many rules, and the spellchecking system should reflect those. For languages that are reliant on their lexicon "more" than their rules, such as english, this is relatively straight forward, a system is put in place to compare typing errors to close equivalents stored in the system's lexicon, while also taking into consideration the stored grammar rules, in the most efficient way possible. For a system such as an Inuktitut one, it would be completely different: the system would have to account for how exactly the (comparatively) few morphemes would behave when subjected to the more extensive list of rules. This difference in production, while perhaps seeming to be not too important for what exactly a spellcheck system would have to address, is actually quite different; a system, no matter how good it is for English, would be quite terrible when applied to a language that differs in that way, such as for Inuktitut or Finnish. The system for English would rely on having a rather large lexicon along with functions designed to then compare the errors in typing to the lexicon, in the most economical way possible. The system for Inuktitut on the other hand, would rely more on the complexities of how well it can process the outcome of what has been produced through the various rule orderings and steps involved in the production. This difference could best be summed up by stating an English system would look more on the finished product that has been typed out, comparing it to a list of the words it has stored, whereas a system for Inuktitut would see the typed utterance and then have to compare it to the numerous possibilities of how exactly the many rules of the language can combine, it is focused more on the "How" of a spelling error whereas an Inuktitut system would focus on the "Why", as well as the "How" of an error.

Though the systems themselves may vary from language to language, the ways one would characterise and evaluate their efficiency does not, every system has to correct as much as possible, in the shortest amount of time possible, while using as little space as possible. Though this is the ideal that all spellcheck system are held to, the differences in the language's methods of word production are reflected in just how close to the ideal a system can come to, as it requires much more computing power, as well as time to evaluate the output of the rules that were involved that lead to that errors and its relation to the intended output.

The design of a spellchecker can reflect the classic debates in linguistics on the nature of the lexicon due to the fact that a spellcheck system essentially is a "mind" of that language, as its sole function is to examine a corpus and then improve on it where possible. The complex nature of this task is extremely comparable to the production of that language itself, as it is essentially the same thing but in reverse. This fact that production of a system is similar to the production of a speaker of a language then opens up the debate of what exactly constitutes a language's lexicon, as well as what is necessary to produce words in that language, aside from what the finished product is on the surface. The real world creation of a system that has tangible effects, planned out by the creator of the program, necessitates acknowledging what exactly is necessary to produce words in that language, with exact certainty as to what is required and in what order; the creation of a language's spellcheck system forces a deliberate and thorough examination of what is behind speech production for a speaker, in no uncertain terms.

# Future Work #

One potential direction is to work on a Hunspell implementation for Inuktitut.
"Hunspell is the spell checker of LibreOffice, OpenOffice.org and Mozilla Firefox 3 & Thunderbird, Google Chrome, and it is also used by proprietary softwares, like Mac OS X, memoQ, Opera and SDL Trados." [1](http://hunspell.sourceforge.net/) There are some tools to put together a Hunspell, and it's implementation is rather straightforward:  "each hunspell dictionary comes in two files. The .dic file which is the list of words, and the .aff file which is a list of rules and other options. You will normally only need to add to the .dic file, but you may need to refer to the .aff file for several things." [2](http://dev.chromium.org/developers/how-tos/editing-the-spell-checking-dictionaries)

Building a collaborative lexicon would be very helpful for the community, so adding tools to grow the Inuktitut Wiktionary which currently has around 250 articles would be a good addition to a Hunspell dictionary. The first step to building a tool for contributing to Wiktionary in context of other webpages, would be to implement Chrome Extension [3](http://www.youtube.com/watch?v=e3McMaHvlBY), [4](https://chrome.google.com/webstore/detail/ipdjaafajlfiopcppipdinmcjbcpofhd) to highlight unknown words [5](http://www.youtube.com/playlist?list=PL209AE945353645CA&feature=edit_ok). The second step would be to have the Chrome Extension present a segmentation to the user so that the word could be looked up in the Inuktitut (or auto-detected language) Wiktionary. The articles in Wiktionary could then be used to create the .dic file for the Hunspell dictionary.



# References #

  1. http://hunspell.sourceforge.net/
  1. http://dev.chromium.org/developers/how-tos/editing-the-spell-checking-dictionaries
  1. http://www.youtube.com/watch?v=e3McMaHvlBY
  1. https://chrome.google.com/webstore/detail/ipdjaafajlfiopcppipdinmcjbcpofhd
  1. http://www.youtube.com/playlist?list=PL209AE945353645CA&feature=edit_ok



# Log #

  * **Refine** what exactly is needed in the input for Inuktitut spell check software.
  * **Familiarize** yourself with the aspects you find necessary.
  * **Immerse** yourself in the comforting arms of github/git
  * **Begin** to put all those together
  * **Cement** a beginning to the software.
  * **Learn** more about JavaScript
  * **Read** as many of the pages you have bookmarked as possible.
  * **Build** playlist of relevant videos.