Adding a 5x2 board array for production. 
The board separation method is milling.
The distance between the boards is specified in the array parameters. 
Gerber files and NC drill file.

## Description of decryption of gerber file formats
The top copper layer is 'gtl';
The bottom copper layer is the 'gbl';
Soldering mask - soldermask_top - 'gtp', soldermask_bottom - 'gbp';
Silkscreen printing - silkscreen_top - 'gto', silkscreen_bottom - 'gbo';
Drilling holes - drilling - 'drl';
Keep Out Layers - 'gko';
Midlle layers - 'G1', 'G2'; 
