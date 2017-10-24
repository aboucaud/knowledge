# Javascript for Automation
Still learning it. [This](https://github.com/JXA-Cookbook/JXA-Cookbook/wiki/Foreword) is a great reference.

## Useful snippets
### get the URL of the frontmost chrome tab
```Javascript
Application('Google Chrome').windows\[0].activeTab.url()
```

### get selected text in Chrome
```Javascript
Application('Google Chrome').windows[0].activeTab.execute({javascript:'window.getSelection().toString()'})
```

# Notes
- [get frontmost tab’s url and title of various browsers](https://www.alfredforum.com/topic/2013-how-to-get-frontmost-tab%E2%80%99s-url-and-title-of-various-browsers/)