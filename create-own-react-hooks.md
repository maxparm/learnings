# React Effect Hooks

* Hearing a lot about React Hooks: blog posts, ligthning talks
* Whole collections of React Hooks being created, packages available on npm
* `useState` seems simple, but more complex components always involve "effects"
* `useEffect` are here to handle side effects into your components
    * Data fetching, setting up a subscription, and manually changing the DOM in React components are all examples of side effects
* Motivation is to:
    * simplify react class components to be function components
    * to separate side effect concerns out of component rendering
    * Help extracting "unrelated" logic into reusable functions
* Think `useEffect` Hooks as an equivalent of `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`

# Firebase

* I've been using it on personal projects
* Many services to create a back-end for your front-end apps
    * Realtime database
    * Hosting
    * Analytics
    * Handle authentication with Google, Facebook, Twitter...
    * Etc...

# Show Login Status with React Effect Hooks

Here we want to show the user login status: "Online" or "Offline" in a navigation bar depending on whether the user is logged with Google or not.

##### Firebase

* https://console.firebase.google.com/project/geese-test/authentication/providers
* See `firebase.js` file

# Links

* https://medium.com/@sampsonjoliver/firebase-meet-react-hooks-db589c625106
* https://overreacted.io/a-complete-guide-to-useeffect/
* https://codesandbox.io/s/p2wqnk3zqj?from-embed








