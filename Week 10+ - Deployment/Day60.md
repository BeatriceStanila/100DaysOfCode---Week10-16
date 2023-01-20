✅ Learned how to pass data deeply with useContext hook 🪝

🔸 lets you read and subscribe to context from your component

🔸Reference
useContext(SomeContext)

🔸 Usage

- Passing data deeply into the tree

- Updating data passed via context

- Specifying a fallback default value

- Overriding context for a part of the tree

- Optimizing re-renders when passing objects and functions

🔸 Troubleshooting

- My component doesn’t see the value from my provider

- I am always getting undefined from my context although the default value is different

🔸Parameters

- SomeContext: The context that you’ve previously created with createContext. The context itself does not hold the information, it only represents the kind of information you can provide or read from components

- useContext returns the context value for the context you passed. To determine the context value, React searches the component tree and finds the closest context provider above for that particular context.

✅ Learned how to create and use custom hooks

- are reusable functions that can be use to add special and unique functionality to the React applications

BENEFITS:

🔸 REUSABILITY

- offer reusability as when a custom hook is created, it can be reused easily, which makes the code cleaner and reduces the time to write the code

- also enhances the rendering speed of the code as a custom hook does not need to be rendered again and again while rendering the whole code

🔸 READABILITY

- can provide a cleaner logic and a better way to understand the relationship between data and the component

🔸 TESTABILITY

- allow you to combine containers and components into one component

- it also makes it easier to write separate unit tests for custom hooks

- using custom hooks also makes it easier to mock hooks when compared to mock HOCs as it is similar to mocking a function
