# bungiehelp2mastodon
Infrequently updated copy of my Twitter-to-Mastodon bash script (held in local Gitea) with local/history removed.

Uses a local Nitter instance with RSS enabled plus sundry local command line utilities which I may list here at some point.

Requires local files of the name curl.TWITERHANDLE.token containing just the Mastodon development API token needed to post (permissions are read write:media write:statuses).

I run it locally via systemd in a dedicated tmux session so I can monitor it.
