# hide-reddit-comments

![Screenshot](/screenshots/example.png?raw=true "Screenshot")

This chrome extension hides all links to the comments on Reddit.com. The motivation behind this extension is to reduce the total amount of time spent on Reddit, and also to improve the quality of time spent on Reddit. Reddit comments are a huge time sink and the discussions are oftentimes only tangentially related to the original post. By removing access to comments, users are forced to read the article (increasing quality of time) and are able to avoid getting caughtup in Reddit threads (reducing total time spent).

This extension was initially implemented as a script, but comment link elements were still appearing momentarily since it took time for the script to remove the link elements. Implementation via CSS allows the link elements to be hidden before they are even loaded.