# Text-to-Speech

#how to run this


1. Open the file directly
(That will launch your default browser pointed at the file.)
start index.html

2. Serve the folder over HTTP
Useful if you want to avoid  restrictions (e.g. for fetch, audio APIs, etc.).
py -m http.server 8000

With Python 3 (if installed):

or
python -m http.server 8000

Then open http://localhost:8000 in your browser.