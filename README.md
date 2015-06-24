# Perch Emmet Snippets

A file with a collection of Emmet snippets for use with the excellent [Perch CMS](http://grabaperch.com/ "Perch")

####Installation - [Adobe Brackets](http://brackets.io/ "Brackets")

1. Copy the file to a folder on your system
2. In Brackets, go to Emmet > Preferences, and enter the file path for the folder with the json file in. In my case on my mac it is _/Users/mikeharrison/Documents/Snippets/_
3. Restart Brackets

####Usage

Use the snippets as with standard Emmet snippets. For instance to create a set of 3 Blocks, an input of:

`perchblocks>perchblock*3`

Would output

```
<perch:blocks>
  <perch:block></perch:block>
  <perch:block></perch:block>
  <perch:block></perch:block>
</perch:blocks>
```
####Commands

|Command   | Result  |
|---|---|
| perchafter  | `<perch:after> </perch:after>`  |
| perchbefore  | `<perch:before> </perch:before>`  |
| perchblocks|  `<perch:blocks> </perch:blocks>`  |
|perchblock|  `<perch:block> </perch:block>`  |
|perchcontent|`<?php perch_content(''); ?>`|
