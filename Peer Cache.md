# Peer Cache

## Problem

Once you're offline you loose access to the content unless it is open in your browser in the tab (or it is alive in the navigation cache). Often times this means you can't even access a page you visited an hour ago. Your browser is pretty much useless unless you happen to organize all the content you may need in tabs and even then your computer or browser could crash. 

## Idea

What if browsers cached every page you visit pretty much permanently (well we'd have quota and a compactor and garbage collector to reduce necessary disk space usage). That way if you are flying to conference and forgot to keep the schedule tab open, no problem, you could still do that although browser would provide semi interactive version (selectable text, images, but probably innactive JS) with a note above telling you that browser is unable to load live version from server but it was able to load a version from 3 days ago.

What if we just leveraged technology like IPFS for the caching instead and made it available to peers ? That would allow other user on the same plane heading to the same conference load the schedule even if they never visited it.

In fact if during conference site providinvg schedule will go down everyone would still be able to load a version from when server was still up from peers that have loaded it.

# Features

- On a plane user shares a link with other user that will load same version from peer cache.
- Site went' down but user still can load version from when it was still up from peers.
- Longer the site is down the larger the peer network grows hosting version from when it was up.
- If page was taken down due to censoring (inappropriate policing video, President elect comment he decided to delete) version from when it was available still can be loaded from peers (assuming there are peers that have it).
- Even though content under the URL can change browser colud still provide a revision history via peer cache.
- In developing contries with poor internet access, this could improve access to a lot of users.

# Risks

- How do we verify peer is sharing genuent content for the adrress.
- We don't want to share private sessions like bank account or an inbox.
