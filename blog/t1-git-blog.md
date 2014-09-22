<!-- This template is in markdown, not html, so
  it will not render beautifully when you copy and
  paste it into your github.io site, but it will at
  least be published. Next week you'll be creating a
  blog template using HTML and CSS and you'll be able
  to copy and paste the blog posts from week 1 in there
  to make them pretty next week.

  For now, please replace the title, subtitle (if desired),
  and date with the text you would like. Markdown is pretty
  simple, so you can just feel free to type. =) -->


Git and GitHub for beginners: the Software itself and a Virtual Hangout that Uses it 
September 21, 2014

WHAT IS GIT AND WHY WOULD I USE IT?

I heard the term 'git' referred to many times before I actually understood what it meant, and briefly entertained the illusion that it was a mysterious folkloric creature, like a Yeti. Git is much more awesome though!

Plain old Git is a 'version control' software program that you can download to your pc like any other sotware - skype, textmate, etc. It allows you to record edits to any kind of file you're changing by taking periodic snapshots whenever you tell it to. A stream of gits might look like one of those youtube montages of a kid taking a selfie everyday for a year. This snapshot is called a 'commit.' 

The cool thing about commits is that you can return to them. In this way, a commit is like a checkpoint in a videogame: you save where you're at so that if you'd like to return to it in the future, you can. Not only does Git let you save changes, it also keeps a log of all commits made and who made them. Git can be used locally (without connection to the internet) to track changes in a document, and it works for any kind of file - a photo of your cat, a word doc, or powerpoint. It just so happens that programmers use it for tracking changes in code.

SIMULTANEOUS COLLABORATION WITH GITHUB - MASTER DOCUMENTS AND CLONES

In contrast, GitHub is a place.  It's a virtual hangout that allows developers to exchange versions of documents and collaborate. GitHub is also a bit like dropbox, in that it's a space where you can create a profile for yourself, store files, and share them with others. The virtual folders for these are called repositories and they're structurally like local folders on your pc.

The awesome thing about GitHub is that it lets groups of people start with the same master document (saved in GitHub) and then make a clone, which they save locally. Then, they can add changes to the clone, and finally submit these to other teammates for review. If all looks well, the new changes will be merged into the master document. 

The result is that many people can simultaneously edit different parts of a single file. (Picture us virtually editing a portrait. I make the eyes blue while you draw in the ruby slippers, and our friend Dan adds a quirky arm tattoo. In the end, we pull all of these pieces together into an updated master.) Furthermore, since developers can work on the clone locally (i.e. even without the comforting proximity of wifi and the fresh aroma of Starbucks), they can be bold and daring in their changes. If they screw up, they can start over, and will have only interfered with a local copy anyway. 

As Stephanie at Stephanie Writes Code puts it (http://stephaniehoh.github.io/blog/2013/10/07/git-vs-github-for-dummies/), editing these clones of the master copy is a bit like getting to spend the next five years leading 7 virtual lives in parallel universes, and then at the end, sticking with the one that worked out best.

Those are the basics. Remember that it's pretty easy to work with git and connect to GitHub via the command line once you get the hang of it (get familiar with the command line first if you aren't already). Once you've installed git on your computer and created a GitHub account, you can open your terminal, type 'git' and then whatever commands you'd like to execute. Here's a preview of some of the ones you'll be using most: 

BASIC GIT COMMANDS

git clone <url> #creates a new clone of your virtual GitHub repository in whatever folder you've navigated to via the command line

git remote add new-remote-name <url>   #lets you create a new remote, basically pointing you toward the GitHub site repository where you'd like to 'push' or submit your new, changed clones (feel like Dr. Frankenstein yet?)

git status #lets you see the status of what repository you're in, and what's been tracked as changed, and what changes have been prepped to be saved as a commit (this prep work is called 'staging' your changes)

git add <name of changed file>' #preps pr 'stages' changes to be saved in a commit. Once you've staged a change, you can check by entering 'git status' again. The staged item should appear in yellow. Now it's ready to be saved in a commit via: 

git commit -m "message describing your changes" #saves your changes in a new commit

git push origin master #sends your commit to the 'master' repository in GitHub to be considered for merging. You'll need wifi for this;)

There are a lot of awesome web resources and tutorials on git and GitHub. Visuals are especially useful. Hope this introduction provides a start!







