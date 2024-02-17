# Task-Fragmentation

My Pick - Fragmentation of UI

## My Reasons for Fragmentating it like that is:- 
1. Improved Readability: Breaking down the UI into smaller, self-contained components makes the code easier to understand and maintain. Each fragment has a clear purpose, making it easier to identify and modify specific parts of the UI.
2. Separation of Concerns: Each fragment handles a specific aspect of the UI, promoting cleaner separation of concerns and better organization.

## Fragmented Components and Reason for it:
1. BurnButtonBar Component: This component contains elements related to initiating the burn process, including the input field for entering the amount to burn and the button to execute the burn. Separating it into its own component makes it clear what functionality it encompasses.
2. BurnStatsContainer Component: This component encapsulates elements related to displaying statistics about the token supply and its distribution. By separating it into its own component, the main component's readability improves, and it becomes easier to understand what information is being presented.
3. TransactionTable Component: This component handles the rendering of the transaction table, which is a significant portion of the UI. Separating it out makes the main component less cluttered and easier to comprehend.

