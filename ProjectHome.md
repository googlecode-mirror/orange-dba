A generic database viewing and administration tool. Use phpMyAdmin for changing the structure, use this tool for looking at (and changing) the data.

I built this because I was tired of phpMyAdmin's clunky data admin pages... (love the structure mods though)..

[screenshot](http://imgur.com/LW9Il.gif)

## General ##
  * Easy to use interface.
  * Zero page reloads.
  * Open each table in it's own in-page tab
  * Easy searching with 'like' on text fields and support for > & < operators in numeric fields
  * In-page editing of rows. If you can see it, you can edit it RIGHT THERE!
  * **HTML in your database?** FCK-Editor WYSIWYG editor integration on double click for some fields (configurable)
  * Color coded feedback _as you type_ in search fields..  (the table has a field with this value.. or doesn't base on bg color) If the db conforms to the orange schema for foreign keys will even tell you if the table being pointed at has a row with the id you've just typed.

## Written in PHP for MySQL using ##
  * jQuery
  * Orange-j
  * Orange-Orange