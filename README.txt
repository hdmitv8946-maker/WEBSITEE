CHARAN FF ESPORTS + MSG91

Player registers -> Owner clicks ACCEPT -> backend calls MSG91 -> approval SMS is sent.

Flow ID:
6aa020a145f2bfb7190009a3

IMPORTANT:
- Keep MSG91_AUTH_KEY on the server only.
- Do not put the Auth Key in index.html.
- The MSG91 template must be approved.
- The template variable used here is "tournament".
- Use HTTPS in production.

Run:
npm install
set MSG91_FLOW_ID and MSG91_AUTH_KEY as server environment variables
npm start

The owner login in this demo is client-side. A real public site should use server-side authentication.
