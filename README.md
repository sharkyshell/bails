### A reminder

The start of each message ID was changed to ```NJX-```. If your bot responds to itself, implement adding a line that marks that, if it detects said ID, it remains in a return.

```Javascript

/* Regularly used method. */

let m.isBot = m.id.startsWith('BAE5') && m.id.length === 16 || m.id.startsWith('3EB0') && m.id.length === 12 || m.id.startsWith('3EB0') && (m.id.length === 20 || m.id.length === 22) || m.id.startsWith('B24E') && m.id.length === 20;

/* Method implementing the "NJX-" */

let m.isBot = m.id.startsWith('BAE5') && m.id.length === 16 || m.id.startsWith('3EB0') && m.id.length === 12 || m.id.startsWith('3EB0') && (m.id.length === 20 || m.id.length === 22) || m.id.startsWith('B24E') && m.id.length === 20 || m.id.startsWith('NJX-');

if (m.isBot) return;

```
