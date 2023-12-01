Create your own custom hook, usePrevious

The starter code for this app contains code that will display the day of the week within an h1 heading, for example: "Today is: Monday".
There is also a button under this heading, that reads "Get next day".

When a user clicks on this button, the h1 heading updates so that the message shows the next day in the sequence.

Your task is to complete the custom hook named usePrevious so that the h1 heading shows both the current day and the previous current day before the update.

**\*\***usePrevious**********\*\*\***********
Purpose:

usePrevious is a custom hook that helps in keeping track of the previous value of a state or any other variable.
How it works:

It uses the useRef hook to create a mutable object that persists across renders.
The useEffect hook is used to update the ref.current with the current value whenever the provided value changes.
