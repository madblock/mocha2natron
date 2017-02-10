# mocha2natron
Converts tracking data in Clipboard got from Mocha to Natron's XML data to paste it to node graph.

USAGE: 
1. Press "Export tracking data" in Mocha
2. Select format "After Effects Corner Pin (corner pin only, supports RG Warp and mochaImport) (*.txt)"
3. Press "Copy to Clipboard" button
4. Run mocha2natron.exe
5. Enter number of first frame of your Natron composition
6. Paste CornerPin node to Natron's node graph 

To operate properly you must have proper template "m2n_template.xml" in active directory.

Built on Visual Studio 2015 C++ using MFC classes CString, CFile etc.
