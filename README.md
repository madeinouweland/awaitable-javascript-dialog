# awaitable-javascript-dialog
Using a promise to create an awaitable dialog that returns the dialog result

![awaitable](https://github.com/madeinouweland/awaitable-javascript-dialog/blob/master/awaitdialog.gif)

```
let dialog = new Dialog(document.getElementById('dialog')); // dialog = placeholder div
let result = await dialog.show("Would you like to make an awaitable dialog?");
console.log("coming back from dialog. result:", result);
```
