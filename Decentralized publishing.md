# Decentralized publishing

## Idea

What if browser would a content authoring tool like it Netscape did back in a days. Modern version that would allow users to write & publish posts in similar way to how medium.com (just because it seems the most popular platform today) allows you to do this.

### Features

* Every single edit can have it’s own content addressable URL (a la IPFS).  User does not need to know that though, it’s just ones user decides to share draft unique URL can be revealed.
* Unpublished drafts can easily be shared with anyone via content addressable link. That would allow users to share drafts with anyone and request a review. Reviewer can provide a feedback in form of inline notes or even propose specific edits (a la github pull request).
* Author then publish a draft under a human readable address (a la git branch / IPNS).
* Visitors of the published content could see a complete revision history (a la git change log). History will contain only published drafts though not an every edit.
* Bookmarking such content could:
    * Save a URL to the source (IPNS link)
    * Save the snapshot of the current revision content (IPFS pin)
    * Subscribe to the future updates (IPFS pub/sub)

	That way user revising page will be able to:
    * View content exactly is it was when bookmarked.
    * Provide information about new version if it was published since.

* Drafting and Review of the post could occur while collaborating peers are offline, but under the same network.
* Publishing can also happen offline although it would replicate across the network eventually, only when one of the peers would go online.
* Users could subscribe to be notified about updates (distributed RSS without xml).
* Content is verifiable by the address.
* Content could be optionally encrypted to restrict access to only specific set of peers.

### Possibilities

* Wikipedia with almost no maintenance costs.
* Medium where publishers own their own data.
* Project documentation pages (a la https://www.gitbook.com)
* Distributed Youtube (Certainly possible if content could embed submission template for proposed edits / changes)
