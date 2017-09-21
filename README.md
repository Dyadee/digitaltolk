This README file contains my general suggestions about code improvements and comments about code quality

1. The file BookingRepository.php contains very long codes. Some lines also are very long containing too many characters.
	This file can be refactored by breaking down into separate files containing related functions for a particular concern.

2. Some functions contains similar codes with other functions. This similarity can be refactored outside the functions and make the function refer to it.
	This will make the function shorter.

3. Some function contains too many if/elseif statement making it harder to trace logic. There are even several ifs that can be combined.

4. Some variables is declared and initialised in the middle of a code block. They must be written at the beginning of a code block.

