## Debounce Search (Angular)

This component demonstrates the **debounce technique** in Angular to optimize search input handling.

When the user types in the input field, the `keyup` event triggers a function, but the actual processing is delayed using `setTimeout`.

Each new keystroke clears the previous timer using `clearTimeout`, ensuring the search logic runs **only after the user stops typing for 1 second**. This prevents unnecessary repeated function calls and improves performance.

If the input field is empty, the result is cleared. Otherwise, the component displays and logs the search query.

### Key Concepts
- Angular Component
- Event Binding `(keyup)`
- Debouncing using `setTimeout`
- Conditional rendering using `*ngIf`