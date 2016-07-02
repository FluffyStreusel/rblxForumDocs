# rblxForumDocs
Writeup on the forums.

# Forums General Info
The ROBLOX Forums run on a subdomain of [forum.roblox.com](https://forum.roblox.com), and if you go to [www.roblox.com/forum](https://www.roblox.com/forum) you will be redirected to the subdomain.

When a new thread button is pressed, it will do redirect the page to *href="/Forum/AddPost.aspx?ForumID=SUBFORUM"* where SUBFORUM is the the subforum. OT is 18.

The reply button code:
`<a href="/Forum/AddPost.aspx?PostID=THREADID&amp;mode=flat" class="btn-control btn-control-medium verified-email-act">Add a Reply</a>`
Where THREADID is the thread's ID, in the URL bar.

If you change an unlocked thread's ID to a locked thread's ID, it will redirect you to the locked thread, not allowing you to respond to the locked thread.
