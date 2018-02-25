# funfunquiz // Setup Finished, Work in Progress
Quiz App powered by hackable Json data of users of funfunforum.com

To participate, edit your `hackable_json` to include a `quiz` field with categories like `javascript` and `css` and questions, like so:

```json
{
    "quiz": {
        html: [{
                "question": "",
                "answers": ["", "", "", ""],
                "correct": 1,
                "hint": "",
                "explanation": ""
            },
            ...
        ],
        css: [{
                "question": "",
                "answers": ["", "", "", ""],
                "correct": 1,
                "hint": "",
                "explanation": ""
            },
            ...
        ],
        es6: [{
                "question": "",
                "answers": ["", "", "", ""],
                "correct": 1,
                "hint": "",
                "explanation": ""
            },
            ...
        ],
    }
}
```

The app is hosted here: WIP

## Contributing
Feel free to open up a PR if you want to help feel free to participate.

### Contributing, start to finish

1. Fork and clone the project. This will put the project on your desktop so you can work on it. I recommend [GitHub Desktop](https://desktop.github.com/) if you haven't done this before.

2. Install [node.js](https://nodejs.org/). This will also install `npm`, the node package manager.

3. Open up a command line window in the project directory. Run `npm install`. This will install all the third-party modules this project depends on. (If there's an error here, something is probably broken in the project! Please let us know on the issues page!)

4. Run `npm run build` to create build folder.

5. Hack away! When developing, you can run `npm start` in the command line to start up a dev server with hot reloading (meaning when you write new code, it will show up in the browser window without you needing to refresh the page. (For most types of code changes. It's not perfect.))

6. When you're ready, go ahead and open up a pull request. I will review your work and request some changes if necessary. When everything looks good, the code will be merged in. The production app should pick up your changes automatically within a minute or two. Thanks for contributing!
