HOW TO WRITE A POST
===================

One .txt file per post in this folder (tales/posts/). Edit it, then tell
Claude "push <slug>" (or "push the AI post") and it syncs the file into
tales/index.html, updates the timeline, and pushes to main.

FORMAT
------
Three header lines at the top, then a blank line, then the body:

    title: The headline of the post
    date:  16 November 2026
    slug:  ai-in-private          <- lowercase-with-dashes, used in the URL

BODY
----
- Separate paragraphs with a blank line.
- _wrap words in underscores_ to italicise them.
- Use plain straight quotes ' and " -- Claude converts them to the
  proper curly quotes when syncing.

IMAGE
-----
Drop a line wherever you want an image to appear:

    [image: filename.png | alt text describing the picture]

The file itself lives in tales/img/ (e.g. tales/img/ai-in-private.png).
The alt text after the | is optional but good for accessibility.

NEW POSTS
---------
Make a new .txt here (newest posts go at the top of the page). Tell Claude
to add it; it also builds the social share card and per-post share page.
