# SkeletonSchool

In this document I'm going to teach you all you need to know about Skeleton, what it can do and how you can get started as soon as possible!

## How to get started

To get started with this small tutorial I highly reccomend you check out the small website I made to explain to you how to get started, aswell as being a tiny example site for you to check out! You can find it at: http://geertsoetens.nl/skeleton/

There you'll find how to download skeleton, as well as showing you what it can do in a small example. As you might've read on that page, the real deal is here.

## Setting up the development environment

If you're already a relatively experienced developer, this is not necessary. At that point you already know how to quickly set up a small development enviroinment.

If you're brand new, I reccomend sticking around as I'll quickly get you up to date on how to set up and use a git environment, which is highly useful for developers, especially colaborative projects.

First, start a Github project. You can do that on this site, first by signing up, and then creating a new project. You can make this project private if you wish, but that'll cost you money. I recommend making it public. During the process of creating a project I also recommend creating a `.md` file. A `.md` file is the document you're reading now. It's your source of information about the project, or can even be you trying to get people to try it! During the process of creating a new project, you'll also get the chance to choose a license. This isn't necessary, but Skeleton allows you to use it for whatever purposes you want, so go crazy.

After you've created the project, you'll be looking at a nice empty project! Save for the `.md` and license file you might have added. If you have a folder where you stick your projects, now's the chance! Open it and get ready for what magic I'm about to show you.

Open your preffered bash in your projects folder. If you do not know what this is, and you're using windows, simply go to the top left of your window and click "file". There you'll see an option "Open Windows Powershell". Click that. It'll open a handy little bash inside your folder. Now go back to your github project online. There should be a "clone or download" option at the right of your project, above the file browser. Click that, and copy the URL that shows up.

Now's time for the git magic! Pay attention, now it'll get technical. Go back to the powershell window you opened. Type `git clone [url]`, replace `[url]` with the url you just copied. Press enter. Wait a few seconds... And voila! You've got your git project downloaded! But that's not all! Because it's cloned you can update the online page with whatever updates you make locally and vice versa. How you'll do that I'll tell you in a second, patience! (Don't close your powershell or bash yet, you're gonna need it).

Now, it doesn't have skeleton yet. So you want to go to the location you downloaded and extracted skeleton (if you followed the steps on http://geertsoetens.nl/skeleton/), and put the files into your git project's folder. Now, if you check the online page, there'll be no updates. That's because git won't run a scan every second to see if something updated and upload that. In fact, it does know what you changed, but it won't apply these changes ever unless you want to! If you want to push these changes to your git project online on github, open up your powershell again. First, you'll have to add your changes to git. You can do this by typing `git add [file]`, or if you're feeling pretty risky, you can use `git add -a`. `git-add-a` adds all new files to git. This is risky in bigger projects, as certain files are only required for the development, and would waste space online if you can just download them locally with a package.json or composer file. But you won't have to worry about any of this with a small skeleton project! If you're satisfied with the files you've added, we can move on to the next step.

Which is, actually getting the files online. To do this, first you'll have to commit the files, you do that by typing `git commit -m [message]`. Typing just `git commit` won't do the same, and will just be more confusing for new users. This adds all the files you've just `git add`-ed to the commit. When you're ready to launch, type `git push`. This pushes all the files to your project online. And that's it, there's a lot more that comes to show when you work on a collaborative project, but I won't get into that now, this file is already becoming long.

## Using Skeleton

Fortunately, using skeleton is the easiest part of this entire project! Skeleton is a very simple CSS responsive boilerplate. It has everything you need to get started on a responsive project. I've worked with it for a short while now and I'd tend to recommend using it for smaller projects, as if you want to get into in-depth php projects you're better off using a php framework. Or if you want a interactive web app you'll be better off with javascript frameworks.

However, that doesn't mean Skeleton is useless! As I've mentioned before, skeleton is great to quickly set up responsive websites, it's incredibly useful that way. I'll tell you about a few features that it has here, and hopefully you can get started from there!

