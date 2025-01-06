### A reminder

The start of each message ID was changed to ```NJX-```. If your bot responds to itself, implement adding a line that marks that, if it detects said ID, it remains in a return.

```Javascript

// Example
if (m.id.startsWith('NJX-')) return;

```
