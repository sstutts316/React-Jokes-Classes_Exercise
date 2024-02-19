# React_History_Exercise

# **CheeZJokes App**

[react-jokes-classes-starter-code.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e8111a3-9f45-4dcc-b332-496812b25c3c/react-jokes-classes-starter-code.zip)

We’ve built an app that lets people view and vote on cheesy jokes. To generate jokes, it uses the [ICanHazDadJoke API](https://icanhazdadjoke.com/api).

- When the page loads, it display a spinner until joke data has loaded from the API.
- The application fetches 5 jokes, making sure that no joke appears more than once on the page. When 5 jokes have been loaded, the spinner disappears.
- The application lists the jokes, along with a “vote-up” button, a “vote-down” button, and the net score *(up - down)* for each joke. Users can vote, and the net score updates.

Right now, the application is written using class components. Refactor the app to use functional components with hooks.

## **Further Study**

If you have time left, add features to your hooks version of this project.

- Store the list of jokes, with votes in local storage. When users visit the app, it should show saved jokes, rather than fetching new jokes. However, the user should still be able to generate new jokes via the button, and these new jokes should replace the ones in local storage.
- Add the ability to reset the vote counts by clicking on a button. This should also clear out local storage.
- Add the ability to “lock” a joke with a lock button, so that you can keep jokes on the page when you request new jokes.
