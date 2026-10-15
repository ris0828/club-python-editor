Club Python Editor

What it is
A single web page where students write Python, type the program input, see the output, and save their code as a .py file. It runs Python inside the browser, so nothing needs to be installed and no account is needed. Works on school laptops, personal laptops, Chromebooks, tablets and phones.

Put it online so students can open a link
Upload everything in this folder, keeping the pyodide folder next to index.html.
Option 1, Netlify Drop: go to app.netlify.com/drop and drag this whole folder onto the page. You get a link right away.
Option 2, GitHub Pages: create a repository, upload all the files, then in Settings choose Pages and publish from the main branch.
Option 3, test on your own computer only: open a terminal in this folder, run   python -m http.server 8000   and visit http://localhost:8000

About the pyodide folder
It holds Python itself (about 14 MB). With it next to index.html, the page loads Python from your own link, which is the safest choice on school networks. If you upload only index.html, the page loads Python from the jsDelivr network instead, which needs internet access that the school does not block.

How students use it
1. Type code on the left.
2. Type what the program should read as input in the top right box, one line for each input() call.
3. Press Run (or Ctrl+Enter). Output and errors appear in the bottom right box.
4. Press Save .py to download the file. Open file loads a .py or .txt file from their computer.
5. Drag the thin bars between the panels to resize them. Double click a bar to reset it.
Their work is also kept in the browser on that device, so a refresh does not lose it.

Limits
Python standard library only (no numpy or other extra packages). The program cannot ask for input while running, so answers must be in the input box first. Stop ends a program stuck in a loop.
