# Text Expander Components

A Single React component named TextExpander that is used to expand and collapse text

### App Component:

This is the main component that renders the TextExpander component multiple times with different props.
It imports useState hook from React and a CSS file named index.css.

### TextExpander Component:

This component uses the useState hook to manage the state of text expansion (isExpanded).
The text content is either fully shown or truncated based on the isExpanded state.
A button is provided to toggle the state of isExpanded, changing between expanded and collapsed states.
This compoent takes several props:

- **collapsedNumWords:** Number of words to show when the text is collapsed (default is 10).
- **expandButtonText:** Text for the button to expand the text (default is "Show More").
- **collapseButtonText:** Text for the button to collapse the text (default is "Show Less").
- **buttonColor:** Color for the button (default is "#1f09cd").
- **expanded:** Initial state of the text (default is false).
- **className:** CSS class name for styling purposes (default is false).
- **children:** The text content to be expanded or collapsed.

### Usage:

The TextExpander component is used multiple times within the App component.
Each usage of TextExpander provides different props to customize its behavior and appearance.
