# Bug report

use `npm run dc` to start `gatsby clean && gatsby develop` with one easy command.

When starting gatsby develop with `gatsby-config` as is, the process will run through. It will log some messages, including canvas etc. into the console.
Look into `gatsby-node`, if you want to see, whats happening.

To reproduce the bug, un-comment the other `plugins`-Array in `gatsby-config`, activating `gatsby-plugin-sharp` and then start `gatsby develop` again.
