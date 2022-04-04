# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a good way to manage state of BIG APPS. It uses Reducers to break up our state into smaller pieces, Actions, which are performed to update that state, and Types, which are the definition of the actions being performed.

2. What packages do we install to use Redux?

```

We installed two dependencies, react-redux and redux

```

3. In your own words, describe the flow of how Redux is used to manage state.

```

We have our initial state that we set up, we pass that to our reducer as the first argument, the second argument is the action, we then use a switch statement to check the type of action, and then our reducer returns a new object with our state!

```

4. What do we use in order to manage different pieces of state?

```

Reducers

```

5. What do we use to perform an update to state?

```

Actions

```

6. How do we access state from Redux?

```

Redux Devtools

```

7. In your own words, describe how to set up Redux for a React App.

```

First we create our store directory inside of our src folder, which will hold our actions, types, and reducers. We also need to create an index.js file inside of the store folder. Then in the react app index.js (which is different!!), we gotta put our root.render() in there. then we wrap our <App /> in <Provider store={store}>

```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
```
