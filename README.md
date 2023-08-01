# JSON Server Template

## Repository
https://github.com/gisellec60/json-server-template

## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Seeding Data

To set up your database, update the `db/seeds.json` file to contain an object
with a key pointing to an array of data, like this:

```json
{
  "shortcuts": [
    {
      "id": 1,
      "task": "Quick Open, Go to File...",
      "keys": "Ctrl+P",
      "decriptions": "Searching for a specific file, especially as the project gets larger, can chew up a lot of time. Even if you already know where the file is, it’s definitely handy to learn this keyboard shortcut to easily open files in your project.",
      "category": "general",
      "os":"Windows"
    },
    {
      "id": 2,
      "task": "Close Window",
      "keys": "Ctrl+Shift+W",
      "category": "general",
      "description":"Close current instance of window",
      "os":"Windows"
    },
    {
      "id": 3,
      "task": "Close Window",
      "keys": "command+W",
      "category": "general",
      "description":"Close current instance of window",
      "os":"MacOS"
    },
    {
      "id": 4,
      "task": "User Settings",
      "keys": "Crtl+,",
      "description": "Visual Studio Code comes with a lot of features and settings that you can change to fit your needs. This keyboard shortcut makes it easier to get to the settings whenever necessary.",
      "category": "general",
      "os":"Windows"
    },
    {
      "id": 5,
      "task": "User Settings",
       "keys": "command+,",
      "description": "Visual Studio Code comes with a lot of features and settings that you can change to fit your needs. This keyboard shortcut makes it easier to get to the settings whenever necessary.",
      "category": "general",
      "os":"MacOS"
    },
    {
      "id": 6,
      "task": "Cut Line",
      "keys": "Ctrl X",
      "category": "basic",
      "description":"Cut the selected line into clipboard",
      "os":"Windows"
    },
    {
      "id": 7,
      "task": "Cut Line",
      "keys": "command + X",
      "category": "basic",
      "description":"Cut the selected line into clipboard",
      "os":"MacOS"
    },
    {
      "id": 8,
      "task": "Copy Line",
      "keys": "Ctrl c",
      "category": "basic",
      "description":"Copy the selected line into clipboard",
      "os":"Windows"
    },
    {
      "id":9,
      "task": "Copy Line",
      "keys": "Command+C",
      "category": "basic",
      "description":"Copy the selected line into clipboard",
      "os":"MacOS"
    },
    {
      "id": 10,
      "task": "Move Line up/down",
      "keys": "Alt+ Up/down arrow key",
      "category": "basic",
      "description":"A lot of times you might need to move a line from one position to another. Instead of copying or cutting and pasting the line into another position, this shortcut offers a faster solution. Just place the cursor on the line.",
      "os":"Windows"
    },
    {
      "id": 11,
      "task": "Move Line up/down",
      "keys": "option + up/down arrow key",
      "category": "basic",
      "description":"A lot of times you might need to move a line from one position to another. Instead of copying or cutting and pasting the line into another position, this shortcut offers a faster solution. Just place the cursor on the line.",
      "os":"MacOS"
    },
    {
      "id": 12,
      "task": "Copy Line UP/Down",
      "keys": "Shift+Alt+ Up/Down arrow key",
      "category": "basic",
      "description":"What if you need to copy a line and paste it below or above? Instead of having to actually copy and paste the line, this shortcut duplicates the line either below or above it, based on the direction chosen with the arrows.",
      "os":"Windows"
    },
    {
      "id": 13,
      "task": "Copy Line UP/Down",
      "keys": "Shift+Option+Up/Down arrow key",
      "category": "basic",
      "description":"What if you need to copy a line and paste it below or above? Instead of having to actually copy and paste the line, this shortcut duplicates the line either below or above it, based on the direction chosen with the arrows.",
      "os":"MacOS"
    },
    {
      "id": 14,
      "task": "Delete Line",
      "keys": "Ctrl+Shift+K",
      "category": "basic",
      "description":"Delete the current line",
      "os":"Windows"
    },
    {
      "id": 15,
      "task": "Delete Line",
      "keys": "Command+Shift+K",
      "category": "basic",
      "description":"Delete the current line",
      "os":"MacOS"
    },
    {
      "task": "Insert Below",
      "keys": "Ctrl+Enter",
      "id": 16,
      "category": "basic",
      "description":"Insert a line below the current line",
      "os":"Windows"
    },
    {
      "task": "Insert Below",
      "keys": "Command+Enter",
      "id": 17,
      "category": "basic",
      "description":"Insert a line below the current line",
      "os":"MacOs"
    },
    {
      "task": "Insert Above Line",
      "keys": "Ctrl+Shift+Enter",
      "id": 18,
      "category": "basic",
      "description":"Insert a line above the current line",
      "os":"Windows"
    },
    {
      "task": "Insert Above Line",
      "keys": "Up Arrow+Command+Enter",
      "id": 19,
      "category": "basic",
      "description":"Insert a line above the current line",
      "os":"MacOs"
    },
    {
      "id": 20,
      "task": "Find",
      "keys": "Ctrl F",
      "category": "search",
      "description":"Open Find box",
      "os":"Windows"
    },
    {
      "id": 21,
      "task": "Find",
      "keys": "Command F",
      "category": "search",
      "description":"Open Find box",
      "os":"MacOS"
    },
    {
      "id": 22,
      "task": "Replace",
      "keys": "Ctrl H",
      "category": "search",
      "description":"Show search and replace option",
      "os":"Windows"
    },
    {
      "id": 23,
      "task": "Replace",
      "keys": "Command + Shift + H",
      "category": "search",
      "description":"Show search and replace option",
      "os":"MacOS"
    },
    {
      "id": 24,
      "task": "Find Next/Previous",
      "keys": "F3/Shift+F3",
      "category": "search",
      "description":"Find the next/previous instance of the selection",
      "os":"Windows"
    },
    {
      "id": 25,
      "task": "Find Next/Previous",
      "keys": "Command+G/Command+Shift+G",
      "category": "search",
      "description":"Find the next/previous instance of the selection",
      "os":"MacOS"
    },
    {
      "id": 26,
      "task": "Select All Occurance of Find Match",
      "keys": "Alt+Enter",
      "category": "search",
      "description":"If you are using the find feature to do certain modifications with all the find results, this keyboard shortcut allows you to select all the find results.",
      "os":"Windows"
    },
    {
      "id": 27,
      "task": "Select All Occurance of Find Match",
      "keys": "Option+Enter",
      "category": "search",
      "description":"If you are using the find feature to do certain modifications with all the find results, this keyboard shortcut allows you to select all the find results.",
      "os":"MacOS"
    },
    {
      "id": 28,
      "task": "Add selection to next Find Match",
      "keys": "Ctrl D",
      "category": "search",
      "description":"Selects the word at the cursor, or the next occurrence of the current selection. ",
      "os":"Windows"
    },
    {
      "id": 29,
      "task": "Add selection to next Find Match",
      "keys": "Command+D",
      "category": "search",
      "description":"Selects the word at the cursor, or the next occurrence of the current selection. ",
      "os":"MacOs"
    },
    {
      "id": 30,
      "task": "Move last selection to next Find match",
      "keys": "Ctrl+K Ctrl+D",
      "description":"The Move Last Selection To Next Find Match command in VS Code moves the current selection to the next instance of the selected text.",
      "category": "search",
      "os":"Windows"
    },
    {
      "id": 31,
      "task": "Move last selection to next Find match",
      "keys": "Command+K Command+D",
      "description":"The Move Last Selection To Next Find Match command in VS Code moves the current selection to the next instance of the selected text.",
      "category": "search",
      "os":"MacOS"
      
    },
    {
      "id": 33,
      "task": "Toggle case-sensitve/regex/whole word",
      "keys": "Alt+C/R/W",
      "description":"",
      "category": "search",
      "os":"Windows"
    },
    {
      "id": 34,
      "task": "Toggle case-sensitve/regex/whole word",
      "keys": "Option+C/R/W",
      "description":"",
      "category": "search",
      "os":"MacOS"
    },
    {
      "id": 35,
      "task": "Insert Cursor",
      "keys": "Alt+mouseClick",
      "description":"This keyboard shortcut allows you to insert an additional cursor at any point in the file.",
      "category": "multicursor",
      "os":"Windows"
    },
    {
      "id": 36,
      "task": "Insert Cursor",
      "keys": "option+mouseClick",
      "description":"This keyboard shortcut allows you to insert an additional cursor at any point in the file.",
      "category": "multicursor",
      "os":"MacOS"
    },
    {
      "id": 37,
      "task": "Insert cursor above/below",
      "keys": "Ctrl+Alt+up/down key",
      "description":"Insert cursor above or below each of the current cursor positions.",
      "category": "multicursor",
      "os":"Windows"
    },
    {
      "id": 38,
      "task": "Insert cursor above/below",
      "keys": "Command+Option+Up/down Arrow key",
      "description":"Insert cursor above or below each of the current cursor positions.",
      "category": "multicursor",
      "os":"MacOS"
    },
    {
      "id": 39,
      "task": "Undo last cursor operation",
      "keys": "Ctrl+U",
      "description":"What if you inserted a cursor by mistake, or realized later that you do not want to insert the cursor at that position anymore? This keyboard shortcut allows you to undo the last cursor insert. This is very helpful when you’ve inserted multiple cursors, as it allows you to keep the others in place and just removes the last inserted one.",
      "category": "multicursor",
      "os":"Windows"
    },
    {
      "id": 40,
      "task": "Undo last cursor operation",
      "keys": "Command+U",
      "description":"What if you inserted a cursor by mistake, or realized later that you do not want to insert the cursor at that position anymore? This keyboard shortcut allows you to undo the last cursor insert. This is very helpful when you’ve inserted multiple cursors, as it allows you to keep the others in place and just removes the last inserted one.",
      "category": "multicursor",
      "os":"MacOS"
    },
    {
      "id": 41,
      "task": "Insert cursor at end of each line selected",
      "keys": "Shift+Alt+I",
      "description":"Insert the cursor at the end of a highlighted selection.",
      "category": "multicursor",
      "os":"Windows"
    },
    {
      "id": 42,
      "task": "Insert cursor at end of each line selected",
      "keys": "Shift+Option+I",
      "description":"Insert the cursor at the end of a highlighted selection.",
      "category": "multicursor",
      "os":"MacOS"
    },
    {
      "id": 43,
      "task": "Select current line",
      "keys": "Ctrl+L",
      "description":"A lot of times you need to select the entire current line your cursor is at. This keyboard shortcut makes it very simple.",
      "category": "multicursor",
      "os":"Window"
    },
    {
      "id": 44,
      "task": "Select current line",
      "keys": "Command+L",
      "description":"A lot of times you need to select the entire current line your cursor is at. This keyboard shortcut makes it very simple.",
      "category": "multicursor",
      "os":"MacOS"
    },
    {
      "id": 45,
      "task": "Select all occurances of current seletion",
      "keys": "Ctrl+Shift+L",
      "description":"With this keyboard shortcut, all you need is to have one occurrence of the text you’re looking for in the file selected. Then, by pressing the keys of the shortcut, you will select all its occurrences in the file.",
      "category": "multicursor",
      "os":"Windows"
    },
    { "id": 46,
      "task": "Select all occurances of current seletion",
      "keys": "Command+Shift+L",
      "description":"With this keyboard shortcut, all you need is to have one occurrence of the text you’re looking for in the file selected. Then, by pressing the keys of the shortcut, you will select all its occurrences in the file.",
      "category": "multicursor",
      "os":"MacOS"
      },
      {
      "id": 47,
      "task": "Select all occurances of current word",
      "keys": "Ctrl+F2",
      "description":"This keyboard shortcut allows you to do the same as the previous one, but without having anything selected. While the cursor is placed on a word, you can press the keys of this shortcut and the current word with all of its occurrences in the current file will be selected.",
      "category": "multicursor",
      "os":"Windows"
    },{
      "id": 48,
      "task": "Select all occurances of current word",
      "keys": "Command+F2",
      "description":"This keyboard shortcut allows you to do the same as the previous one, but without having anything selected. While the cursor is placed on a word, you can press the keys of this shortcut and the current word with all of its occurrences in the current file will be selected.",
      "category": "multicursor",
      "os":"Windows"
    },
    {
      "task": "Show Command Palette",
      "keys": "Ctrl+Shift+P,F1",
      "description":"With this keyboard shortcut, you can easily open the command palette. The command palette allows you to search through the commands you can use and execute them.",
      "category": "general",
      "id": 49,
      "os":"Windows"
    },
    {
      "task": "Show Command Palette",
      "keys": "Command+Shift+P,F1",
      "description":"With this keyboard shortcut, you can easily open the command palette. The command palette allows you to search through the commands you can use and execute them.",
      "category": "general",
      "id": 50,
      "os":"MacOS"
    },
    {
      "task": "Keyboard Shortcuts",
      "keys": "Ctrl+K Ctrl+S",
      "category": "general",
      "description":"Enable keyboard shortcut sequence",
      "id": 51,
      "os":"Windows"
    },
    {
      "task": "Keyboard Shortcuts",
      "keys": "Command+K Command+S",
      "category": "general",
      "description":"Enable keyboard shortcut sequence",
      "id": 52,
      "os":"MacOS"
    },
    {
      "task": "New Window /Instance",
      "keys": "Ctrl+Shift+N",
      "category": "general",
      "description":"Open new instance of Visual Studio Code editor in new window",
      "os":"Windows",
      "id": 53
    },
    {
      "task": "New Window /Instance",
      "keys": "Command+Shift+N",
      "category": "general",
      "description":"Open new instance of Visual Studio Code editor in new window",
      "os":"MacOS",
      "id": 54
    },
    {
      "id": 55,
      "task": "Quick Open, Go to File...",
      "keys": "command + P",
      "decriptions": "Searching for a specific file, especially as the project gets larger, can chew up a lot of time. Even if you already know where the file is, it’s definitely handy to learn this keyboard shortcut to easily open files in your project.",
      "category": "general",
      "os":"Mac"
    }
  ]
}
```

Then, run `npm run seed` to copy data from the `db/seeds.json` file to the
`db/db.json` file. `json-server` uses the `db.json` file to create your RESTful
API, so make sure your `db.json` file is always up to date!

Any time you want to reset your database back to your original data, run
`npm run seed` again. Doing this will overwrite all the data in your `db.json`
file, so make sure you don't have any data in that file that you don't mind
losing!

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```
If for some reason you are having problem starting your server run the command below to make sure you have killed anything using that port:

```sh
npx kill-port port#
```

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3000](http://localhost:3000). Check it out in the browser to
make sure your server works!

## Deploying

Free services like Render make it simple to deploy your Node server. Render also
works nicely with Rails, which you'll learn later in the program.

### Sign Up for a Render Account

You can sign up for a free account at
[https://dashboard.render.com/register][Render signup]. We recommend that you
sign up using GitHub as that will make it a little easier for you to connect
Render to your GitHub account. The instructions below assume you've done that.

[Render signup]: https://dashboard.render.com/register

Once you've completed the signup process, you will be taken to the Render
dashboard.

In order to connect Render to your GitHub account, you'll need to click the "New
Web Service" button in the "Web Services" box. On the next page, you will see a
GitHub heading on the right side and below that a link labeled "Configure
account". (If you didn't sign up using GitHub, it will say "Connect account"
instead.) Click that link; a modal will appear asking you for permission to
install Render on your GitHub account. Click "Install." You should then be taken
back to the "Create a New Web Service" page, which should now show a list of
your GitHub repos.

### Deploy the Server

Find the GitHub repo for your json server in the list and click Connect. Give
the web service a name and make sure the Environment is set to Node. Everything
else can be left as is. Scroll down to the bottom of the page and click "Create
Web Service." The build process will begin automatically.

The URL for your deployed server is shown in the upper left corner of the page,
e.g., `https://my-server.onrender.com`. Once the build is complete, you will be able to
make fetch requests to that URL.

### Making Updates

Since Render deployment integrates with your GitHub repo, you can easily deploy
changes to your database. First, commit and push your code up to GitHub:

```sh
git add .
git commit -m "Updated database"
git push
```

Then launch the build process by going to the page for your server on the
Render dashboard, clicking the "Manual Deploy" button in the upper right corner
of the page, and selecting "Deploy latest commit."
