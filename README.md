# Youtube-clone
Implemented [Nxt Watch application](https://nxtwatchsru.ccbp.tech) which is a clone for YouTube where users can log in and
can see a list of videos like Trending, Gaming, Saved videos, and also can search videos and
view specific video details, and users can toggle the theme (Light/Dark).
● Implemented Different pages like Login, Home, Trending, Gaming, Saved videos
using React components, props, state, lists, event handlers, form inputs.
● Authenticating by taking username, password and doing login post HTTP API Call.
● Persisted user login state by keeping jwt token in local storage, Sending it in headers
of further API calls to authorize the user.
● Implemented different routes for Login, Home, Trending, Gaming, Saved videos,
Video item details pages by using React Router components Route, Switch, Link.
● Redirecting to the login page if the user tries to open Home, Trending, Gaming, Saved
videos, Video item details routes which need authentication by implementing
protected Route.
Technologies used: React JS, JS, CSS, Bootstrap, Routing, REST API Calls, Local Storage,
JWT Token, Authorization, Authentication
