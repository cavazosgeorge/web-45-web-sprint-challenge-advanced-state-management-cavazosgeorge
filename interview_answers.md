# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

- Context API removes the need for prop drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

- Actions are objects that are dispatched to reducers after being called. Reducers then take the action and follow the instructions from the action. Store is immutable state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

- Redux-Thunk allows us to use to make API calls from our action creators. It changes the action creators by making them perform asynchronous API calls using middleware.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

- The Reducer Pattern has been my favorite so far because all the data is easy to find and easy to apply. I like the flow of the Reducer Patter and I like how it is easy to find a bug when your code breaks.
