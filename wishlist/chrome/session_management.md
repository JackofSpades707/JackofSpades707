## Session management

Why do this?

I'm a power user, that browses a lot, and opens a lot of tabs I intend to return too at a later time.
This can lead to massive amounts of tabs, reducing productivity in my workflow.
I can somewhat mitigate this by using Chromium to quickly search through open tabs. but that isn't the best solution.
I can also use tab groups, but that requires keeping the tabs open all the time as well, not the best solution but better when paired with chromium.
So, as a last ditch effort, I was thinking something like [Session Buddy](https://chrome.google.com/webstore/detail/session-buddy/edacconmaakjimmfgnblocblbcdcpbko/related?hl=en) would be a good finishing touch.

Being able to save my session, and manipulate the session into groups of sessions that I can restore/save on-demand per topic.

This is good, although it doesn't seem to allow me to have fine grained control over editing my sessions, and even if it does and I'm missing something, It's not intuitive at all to do so (other than merging them together)

So, This is the criteria for my wishlist extension for this job:

* Write different sessions to disk
* Restore sessions from disk
* Group sessions together easily
* Split sessions apart easily
* Keybind to bring up a prompt of different "commands" for various things to maximize convenience and minimize interupting thought processes, this will behave like rofi and use either fuzzyfinding or regex
* Minimal & Intuitive UI allowing for simple quick control as well as fine grained control
* Is aware of seperate windows

Optionally:
* Is aware of tab groups (Might not be possible?)

### commands (for prompt activated via-keybind)
* QuickSave current session
* Restore session X
* Restore quicksave session
* Restore session X (replaces current browsing session)
* Restore quicksave session (replaces current browsing session)
* Create new session X
* Overwrite session X


