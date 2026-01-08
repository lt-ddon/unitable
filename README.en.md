# Overview
Unitable is a Unicode character table designed for quick lookup of character codes.
Created as a minimalist tool useful when implementing character encoders/decoders.

# Usage
## UNITABLE 1
This is the first version of the table; it displays all blocks of a given plane. That places a heavy load on the browser, so I recommend using it on high‑performance hardware.
Usage: press one of the "Generate plane" buttons, open the browser's find function (Ctrl+F), and enter a character or its Unicode code. The browser will locate the character.

Rendering such a large number of characters consumes RAM and CPU, so use caution.
## UNITABLE 2
Second, refined version. Usage differs completely from the first version. Characters can be searched by browsing blocks with the "Previous block" and "Next block" buttons.
To find a character by its hexadecimal code, enter the code in the field next to the "Find code" button and then press that button.
To find the hexadecimal code for a character, paste the character into the field next to the "Find character" button and then click the button.
## Legend
The displayed tables show Unicode blocks. After finding a character, a red frame will indicate the character's position within the block.
### B (Block)
The top‑left corner of a block shows the value "B:" indicating the block ID. The diagram at the top of the page shows a map of blocks and their contents.
### O (Offset)
The top header row of the table shows values labeled "O:" representing the high hexadecimal digit of the Unicode codepoint.
### L (Line)
The left header column shows the row values. Values labeled "L:" represent the remaining hexadecimal digits of the Unicode codepoint.
