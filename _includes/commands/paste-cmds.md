
| Command                   | Description                                                                                                                                                                               |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| mceInsertClipboardContent | Triggers a paste event at the cursor location or over the current selection. The command requires an object with: `content` containing the HTML content, or `text` containing plain text. |
| mceTogglePlainTextPaste   | Toggles paste as plain text.                                                                                                                                                              |

**Examples**

```js
tinymce.activeEditor.execCommand('mceInsertClipboardContent', false, {
  content: '<p>Hello, World!</p>'
});
tinymce.activeEditor.execCommand('mceTogglePlainTextPaste');
```
