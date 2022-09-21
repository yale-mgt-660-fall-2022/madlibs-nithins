# Madlibs Activity
For this activity, you will use what you've learned about git to work collaboratively.
We're going to write some funny [Madlibs](https://en.wikipedia.org/wiki/Mad_Libs)-style stories.

## How to complete this activity

1) Kyle will put you into breakout rooms. You should choose one person who will share screen with others. Only
the person sharing their screen in your breakout room needs to follow these instructions (but all should read them 🤣)

2) Fork the starter repository on GitHub. Forking means to make a copy of the code but in your own GitHub repository so that you can make changes. Technically you are "cloning" the starter repo. GitHub calls this "forking" because they add some other
bells and whistles on top. You should see a grey button at the top that says "fork"---that is what you want. If you need more information, look at [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/). **Make sure you fork the code to the yale-mgt-xxx-fall-2022 organization**, where "xxx" is 656 or 660. That way, you can use some paid features of GitHub 😀. Please give your fork a good name like "madlibs-sarah" if your name is Sarah.

3) Take a look around at the files. Familiarize yourself where everything lives. 

4) View your Madlibs web app.  If you want to view your app on Codespaces, consider using the built-in Python webserver in order to 
serve your html/css/js. You can do that with `python3 -m http.server` in the terminal. Or, if you're comfortable, you might prefer to work locally
on your computer instead. In that case, just clone the repo to your computer and  you can open the `index.html` file
in a browser (there's no need to run a webserver on your local computer).

5) Veryify that the web app works!

6) Please edit the code! I'd like to to create new stories, verbs, nouns, adjectives, or adverbs! The instructor will likely
assign you to one of these. Before you do your work, checkout a new branch with a descriptive name. This will be a command like

   ```
   git checkout -b bald-chicken-new-verbs
   ```

   Here, I named my branch "bald-chicken-new-verbs". You should name yours something *different*, no spaces. E.g.
   your branch name might be "fire-lion-new-stories" or "rad-verbs-for-class-by-sleek-deer".


7) If you want to add a new part of speech, it's likely easiest for you to create a new file. You can also edit existing files, but that will make our merging harder. If you want to make a new file of verbs, you might make a file at
`/js/verbs/bald-chicken.js` and in that file, add new verbs. You should choose a name other than "bald-chicken.js". Of course, to _use_ that javascript file, you'll need to include it in your `index.html`.

8) Check your code works. Did you break the app? No? Great! 

9) Commit your changes and share them

   First, take a look at the status of your work

   ```
   git status
   ```

   It should show what files are new and what files are changed. Now, you want
   to add the new files, try the `git add` command. You'll need to supply a file name.

   Once you've added your changes to the "staging area", you want to make a commit. This
   is a command _something like_

   ```
   git commit -m "Added some verbs for class"
   ```

   Now, push your changes up to GitHub.

   ```
   git push origin BRANCHNAME
   ```

   where `BRANCHNAME` is the name of your branch.

10) Go to GitHub, find your repo and the new branch, then make a pull request. Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

11) The instructor will merge in everybody's work. 
