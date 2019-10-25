# Features

This is a requirements documentation that lives with the repository. Any and all features that are added to the product need to be updated here.

## Functional

- Given that a Reddit user is authenticated, when a schedule is run and/or a button is pressed, provide the ability to sync a personal database with all saved comments, links, images, videos, and otherwise (henceforth known as a "resource").
- Given that a Reddit user is authenticated, when a webhook endpoint is hit, a single resource is stored in the database.
- Given that a Reddit user is authenticated, when a new resource is stored, when applicable, it is downloaded and saved for offline usage.
- Given that a Reddit user is authenticated, when a request for resources arrives, it can be filtered, sorted, and grouped by subreddit.

## Non-Functional

- Privacy is paramount. Encryption isn't required for links but it should not be possible to link it to a Reddit account immediately.
