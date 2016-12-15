# Content Pinning 

## Problem

Bookmarks are totally broken. Users don't trust them & rightfully so, as content under the saved URL may change or dissapear. Often times users want to save or share a fragment of the page that contains relevant information. When there is an anchor links to that section it's somewhat doable, but often times there is not. According to user study Mozilla performed most users resort to screenshots instead.

Often when sharing a URL with someone user needs to provide additional instructions on how to get to the relevant fragment on the loaded page. In majority cases users resort to a screenshot and anotation highligting a relevant information. In fact there is no better option that even advanced users could use when desired fragment is under authentificated session.

## Idea
 
What if we could leverage distributed networks like IPFS for sharing actual content instead of URL to it & then sharing URL for that content instead. In other words what if user colud select desired fragment of the page and pin it (a la pinterest) or just share it with anyone with one click (generate content URL and share that). That would resolve most issues associated with bookmarking and sharing that exist today:

1. Saved / Shared content will look exactly same as it did when it was selected.
2. Shared content will appear exactly the way at appeared to user sharing it.
3. Users would be able to share only relevant fragments and avoid all the uncessery instructions.
4. Saved / Shared fragments can be behind authentificated session (UX would have to highlight risks of those actions).

To take things even further we could allow edits & anotations so that users could further highlight details / add notes to the saved / shared content.

### Features
 
 - pintereset.com (without lock-in or ads)
 - content can be encrypted to restrict access only to desired receipents.
 - browser could visually outline pinned / annotated content on the visited page.
 - allow annotation feeds (feeds of anotations users could subscribe to, for examlpe there could be a service that provides fact checking on articles to help identify fake news).
 - organizing fragments (galleries / notetaking)
