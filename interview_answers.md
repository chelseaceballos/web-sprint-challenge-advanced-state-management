# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
context API is more simple in the way that you can avoid prop drilling. You can pass state down without having to pass props.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
actions - carry the payload of information from the app's store. An action is an JS object that must have a type to declare the action performed
reducers - Reducers update the store with the value of the action that contains the information payload.
store - Store holds the entire state tree of an application, state, actions, and reducers. There is only one store in the entire app. 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
redux thunk is middleware that returns functions within in redux. It is mostly used for handling promises or actions in a non-synchronous manner. For example GET request.
Thunk passes dispatch() and getState() into action creators.

4. What is your favorite state management system you've learned and this sprint? Please explain why! My favorite thing that i learned this week was the reducer patterns from module one. It really felt like a huge building block for the rest of the sprint. I felt like really getting Actions and Reducers down, were huge in understanding the rest of the weeks curriculum. 