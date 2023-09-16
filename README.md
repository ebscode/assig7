# question discuss


question: Discuss how you managed the state in your assignment project
ans:

1. Component-Level State (useState):

For managing local state within a component, React provides the useState hook. You can declare a state variable and update it using a setter function. This is suitable for managing small pieces of component-specific data that don't need to be shared with other components.

2.

Prop Drilling:

send props from parent to child. react has  only  a one-way data transfer system 

When you need to share state between parent and child components, you can pass state data as props to child components. However, if you have a deeply nested component structure, this can become cumbersome and lead to prop drilling.


3. useEffect use for fetching data from API


ques: Add at least 3 Project features

1. select a course only once time
2. there is limited credit hour for adding a course
3.the cart shows how many credit hours you used
