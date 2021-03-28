# [HTML2TW5](https://mistermochi.github.io/HTML2TW5/)

This is a very proof-of-concept prototype of a tool to convert HTML text to tw5 wikitext. [Jump right into the latest release.](https://mistermochi.github.io/HTML2TW5/)

It aims at bridging the gap between "real world" documents in the form of online articles/ MS word documents and Tiddlywiki, making it easier for other platform users to get a head start with tiddlywiki. It also aims to greatly reduce the effort required to edit certain formatting components, e.g. merged tables, resized images... in a more user friendly, WYSIWYG manner.

The following features are currently out of the scope of this project:
* Round trip conversion of HTML > TW5 > HTML
* Implementing an alternative editor for TW5 -- This could be a long term goal, but it seriously falls short at implementing the special macros & widgets TW5 has to offer.

## Dependencies

This project currently depends on two other javascript-based tools:

* [Turndown](https://github.com/domchristie/turndown) MIT License
* [TinyMCE](https://github.com/tinymce/tinymce) LGPL-2.1 License

> Note: since this project is still a proof of concept prototype, it currently directly modifies the code from Turndown. The long term plan is to abstract the code of HTML2TW5 from Turndown for a easier to maintain code base & more stable behavior.

## Plans of adaptation

For a detailed list of wikitext behavior and respective markup please [see here](https://tiddlywiki.com/static/WikiText.html).

* Full: Plans for final product to exactly behave like TW5 markup
* Partial: Some basic behaviors will be implemented, but further advanced behaviors may be dropped in favor of a simpler solution.
* No plan: Will not be considered in final product, either (1) there is no 1-to-1 HTML solution to that format or (2) such a behavior depends on TW5 internals to work.

|Wikitext Component|Plans|
|------------------|-----|
|Block Quotes|FULL|
|Code Blocks|FULL|
|Dashes|No plan|
|Definitions|FULL|
|Formatting|FULL|
|HTML|No plan|
|Hard Linebreaks|No plan|
|Headings|FULL|
|Horizontal Rules|FULL|
|Images|FULL|
|Linking|Partial|
|Lists|Partial|
|Macro Calls|No plan|
|Macro Definitions|No plan|
|Macros|No plan|
|Paragraphs|No plan|
|Styles and Classes|No plan|
|Tables|Partial|
|Transclusion|No plan|
|Typed Blocks|No plan|
|Variables|No plan|
|Widgets|No plan|
