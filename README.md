# Waterway-Pioneers
Discover and share the best trails for the optimal outdoor occasions while warning others of potential hazards in this app
On this app, kayakers report the routes they travel on rivers and lakes. They can trace their routes and set map markers to denote inconveniences / dangers such as fallen trees blocking the waterway, rapids, hornets nests, put-in locations, take-out locations, etc. The app helps kayakers learn from others' experience to determine if routes are navigable, find new routes, and always come prepared.
### MVP (Minimal Viable Product)
- One grand kayak map displays  all routes and markers
- Can filter map by different types of markers
- Can set map to display color-coded put-in take-out location pairs (ideally with the route line connecting them, but see Roadblocks below)
- Users “report” routes by tracing their path on a map (put-in and take-out locations are added as markers); they can add other useful information such as length of time the route takes, difficulty level, description, etc.
- Users “report” markers by selecting a location on a map and assigning a marker type; description with more info is optional
- Marker types include: “fallen trees”, “rapids”, “put-in location (free)”, “put-in location (paid)”, etc.
- Users can search for posted routes by put-in location, take-out location, or both
- Users can comment on, validate, invalidate (upvote or downvote system?) markers posted by others (rationale: someone may report a marker that is inaccurate or no longer valid, such as trees that blocked a waterway but were then removed)
- Users can search for “routes near me” to find routes other kayakers have traveled in the past
### Aditional Features or Stretch Goals
- User profiles
- Route lines are displayed on general map along with markers (this is difficult because it would require a way to filter through routes and determine which ones are identical; identical routes travel the same waterway path, but the users will not draw them in the same way)
- A credibility system adds/removes markers from the map if they get enough upvotes/downvotes
- Badges reward users for things like reporting a marker, traveling a new route, etc.
- Users can mark that they traveled a route someone else already traveled rather than making a new route
- Social media aspects like following other kayakers, liking trips, etc.
- Similarity detector determines if two different markers mark the same thing; if so, merge them
- Display “uncharted territory” on general map---waterways that no one has posted information about
### Resources
- Google Cloud Maps API -> https://developers.google.com/maps/documentation/javascript/overview
- Plotly -> https://plotly.com/
- ReactJS -> https://reactjs.org/
- Firebase -> https://firebase.google.com/
- MongoDB -> https://www.mongodb.com/

Demo screenshots below:
![Screen Shot 2023-01-27 at 1 36 05 AM](https://user-images.githubusercontent.com/70988841/215032824-c231b1e6-55ba-4eb1-9eb9-6c4ec9782e75.png)
![Screen Shot 2023-01-27 at 1 36 28 AM](https://user-images.githubusercontent.com/70988841/215032904-6b76693b-e695-4dec-93b2-afb5b4186880.png)
![Screen Shot 2023-01-27 at 1 36 56 AM](https://user-images.githubusercontent.com/70988841/215032966-e213ea3a-d1b6-4e25-bdfb-340c917c3b86.png)
![Screen Shot 2023-01-27 at 1 37 09 AM](https://user-images.githubusercontent.com/70988841/215032986-6c962d16-f23a-4338-983b-ee582f517754.png)
![Screen Shot 2023-01-27 at 1 38 13 AM](https://user-images.githubusercontent.com/70988841/215033161-bfd89130-92df-4821-b8ca-4a3dc111a7e3.png)
