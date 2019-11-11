# SaveIt

Reddit saves management service.

## Rationale

> See the [features document](FEATURES.md) for more specific information about the purpose of this software.

A lot of Reddit saves management applications exist, but none of them are quite accurate enough to be a full Reddit saves replacement. There are a few core features that we believe are missing from Reddit saves that we will try to rectify:

- You should be able to sort, filter, group (by subreddit), and search your Reddit saves.
- You should be able to have an arbitrary (read unlimited) amount of saves.
- You should be able to archive most types of content for offline viewing.
- You should be able to view comments and their context. If they still exist, a link to them is better.
- You should be able to host it on your own servers.

Deploy this API service to some server, log in (OAuth2), and access saves.

### Frontend Considerations

`saveit` is a database-connected service offering a RESTful API. That's it.

There's no reason Reddit-like communities could not also sync to this service. I am considering implementing a basic one as a web application, but I welcome applications developers to go for it.

### Cloud Version

If this is popular enough in the future, we may consider creating a Cloud version of this. It would be a paid service but it would not require self-hosting. In that case, we would still offer this as free and open-source software for self-hosting.
