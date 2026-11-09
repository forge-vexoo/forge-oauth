# forge-oauth

OAuth redirect relay pages for the Forge desktop app.

`slack/` forwards Slack's `?code=&state=` to the Forge app's local listener (`http://127.0.0.1:47815/oauth/callback`). Nothing is stored; the code is useless without the PKCE verifier the app keeps.
