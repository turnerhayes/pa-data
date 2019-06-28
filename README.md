# Warning
DO NOT SHARE THE DATA YOU GET OR PUT IT PUBLICLY ONLINE (like in a public repo). This is for analysis only and it will be anonymized.

# You need
to have these on your computer

## nodejs

Use homebrew if you've got it (you'll know if you do). Installing globally is easiest.

If you don't know how to install it already, download it manually: https://nodejs.org/en/download/. It may get put in a hidden folder. We're trying to figure that out.

## git

### New instructions!
1. Make an account on Github
2. Download the Github desktop application: https://desktop.github.com/
3. Open the application and log-in
- After you log-in it’ll show your username and some other information associated with your account – you can keep this information just as is it is
4. On the far right of the screen select “clone repository”
5. Move over to the “URL” tab and enter the URL for our project: https://github.com/knod/pa-data
- You can also assign a file location for the folder your are cloning
6. Click “Fetch origin” at the top of the page to make sure you have cloned the most up-to-date version of the code

### Fallback
Same kind of deal here.

Download here (https://git-scm.com/download/win) into the same folder as nodejs? We're working on figuring this out.

## halp us!

If you know sites with tutorials to do this better, let us know!


# Do
- make sure your computer isn't going to go to sleep
- plug your computer into power

## nodejs
- If you downloaded nodejs manually, find where it got installed on your computer. May be in a hidden folder. We're working on figuring that out.

## Get code
1. go to https://github.com/knod/pa-data
1. If you know how:
  - clone the repo
1. If not:
  - click 'clone or download'
  - click 'download zip'?
  - extract folder
  - If you downloaded and extracted: put it where node is
  - DO NOT DELETE THIS FOLDER

## Directories
1. **if it's not there already, add a folder called `data-mdj`**
1. Somewhere completely different on your computer, make another folder. Call it whatever you want. `pa-data-data` is one idea and is how I'll talk about it from now on. Later you'll see you're going to move the data there periodically. Thumb drive is good if you don't want it on your machine.
1. Make a folder inside `pa-data-data` called `data-mdj`

## Command prompt/terminal
1. open command prompt
1. navigate into extracted folder
1. type: `npm install`
1. press enter
1. wait
1. type what michelle says to type (will be something like: `node mdj-names.js 6 10 15000`)
1. press enter
1. this will take a long time
1. there will be a lot of errors that don't matter

## Errors to Worry About
There will be a bunch of errors. As long as the number after the text 'new pg at end' keeps changing, it's good.

Bad errors have this as their first line: Error: `Error: failed to find element matching selector "#ctl00_ctl00_ctl00_cphMain_cphDynamicContent_cphDynamicContent_participantCriteriaControl_lastNameControl"`

If that happens press `ctrl` and `C` at the same time, then message michelle


# Keeping Data

You don't really want to keep the data hanging around the project folder. What if you accidentally overwrite it with a `git pull origin master` or something weird. So...

**When your program is stopped**

1. **move** the pdfs from the project's `data-mdj` folder into the `data-mdj` you made in `pa-data-data`.
1. **copy** the 'mdj-named-dockets-used.txt' into just the `pa-data-data` folder. Replace an older version if you need to.

# If something is weird and you're not sure
don't hesitate to message michelle. She wants your sweet sweet messages.

