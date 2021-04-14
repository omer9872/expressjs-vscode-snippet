# expressjs-vscode-snippet
Key binding to perform CRUD methods faster.

Paste your own combination to "Open Keyboard Shortcuts (JSON)"
Control + Shift + P then type "Open Keyboard Shortcuts (JSON)"

```
[
  {
    "key": "ctrl+numpad1",
    "command": "editor.action.insertSnippet",
    "when": "editorTextFocus",
    "args": {
      "snippet": "app.get('/get', (req, res) => {\n\n});\n\napp.post('/insert', (req, res) => {\n\tconst [] = req.body;\n\n});\n\napp.put('/update', (req, res) => {\n\tconst [] = req.body;\n\n});\n\napp.delete('/delete', (req, res) => {\n\tconst [] = req.body;\n\n});\n"
    }
  }
]
```

with "control + Numpad 1" key combination cursor will insert this snippet:
```
app.get('/get', (req, res) => {

});

app.post('/insert', (req, res) => {
  const [] = req.body;
  
});

app.put('/update', (req, res) => {
  const [] = req.body;
  
});
  
app.delete('/delete', (req, res) => {
  const [] = req.body;
  
});
 ```
