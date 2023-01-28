# postMessage-demo
A simple demo about postMessage. Same origin.  You see 2 pages: index.html and iframePage.html.  The index.html has a button that calls DoScroll() function, which scrolls the iframe to the botton.  The iframePage.html has a function DoScroll2() which calls parent.postMessage() handler.  This handler calls the  DoScroll() handler on the parent index.html page again.
