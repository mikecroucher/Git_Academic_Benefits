# Academic Benefits of using git and/or GitHub

Many people suggest that you should use version control as part of your scientifc workflow.  This is usually quickly followed up by recommendations to learn git and to put your project on GitHub.  Learning and doing all of this for the first time takes a lot of effort. Alongside all of  the recommendations to learn these technologies are horror stories telling how difficult it can be and memes saying that no one really knows what they are doing!  

There are a lot of reasons to **not** embrace the git but there are even more to go ahead and do it.  This is an attempt to convince you that it's all going to be worth it alongside a bunch of resources that make it easy to get started and academic papers discussing the issues that version control can help resolve.

This document will not address**how** to do version control but will instead try to answer the questions **what** you can do with it and  **why** you should bother.

# Improvements to individual workflow

Ways that git and GitHub can help your personal computational workflow -- even if your project is just one or two files and you are the only person working on it.

## Fixing filename hell

Is this a familiar sight in your working directory?

```
mycode.py
mycode_jane.py
mycode_ver1b.py
mycode_ver1c.py
mycode_ver1b_january.py
mycode_ver1b_january_BROKEN.py
mycode_ver1b_january_FIXED.py
mycode_ver1b_january_FIXED_for_supervisor.py
```

For many people, this is just the beginning.  For a project that has existed long enough there might be dozens or even hundreds of these simple scripts that somehow define all of part of your computational workflow.  Version control isn't being used because 'The code is just a simple script developed by one person' and yet this situation is already becoming the breeding ground for future problems.

* Which one of these files is the most up to date?
* Which one produced the results in your latest paper or report?
* Which one contains the new work that will lead to your next paper?
* Which ones contain deep flaws that should never be used as part of the research?
* Which ones contain possibly useful ideas that have since been removed from the most recent version?

Applying version control to this situation would lead you to a folder containing just one file

```
mycode.py
```

All of the other versions will still be available via the commit history.  Nothing is ever lost and you'll be able to effectively go back in time to any version of `mycode.py` you like.

## A single point of truth

I've even seen folders like the one above passed down generations of PhD students like some sort of family heirloom.  I've seen labs where multple such folders exist across a dozen machines, each one with a mixture of duplicated and unique files.  That is, not only is there a confusing mess of files in a folder but there is a confusing mess of these folders! 

This can even be true when only one person is working on a project.  Perhaps you have one version of your folder on your University HPC cluster, one on your home laptop and one on your work machine.  Perhaps you email zipped versions to yourself from time to time.  There are many everyday events that can lead to this state of affairs.

By using a GitHub repository you have a **single point of truth** for your project.  The latest version is there.  All old versions are there. All discussion about it is there. 

Everything...one place.

The power of this simple idea cannot be overstated.  Whenever you (or anyone else) wants to use or continue working on your project, it is always obvious where to go.  Never again will you waste several days work only to realise that you weren't working on the latest version.

## Keeping track of everything that changed

## Always having a working version

## Tracking down what went wrong with your code

## Providing a back up of your project

Try this thought experiment:  Your laptop/PC has gone! Fire, theft, dead hard disk or crazy panda attack.

It, and all of it's contents have vanished forever.  How do you feel? What's running through your mind?
If you feel the icy cold fingers of dread crawling up your spine as you realise **Everything related to my PhD/project/life's work is lost** then you have made bad life choices.  In particular, you made a terrible choice when you neglected to take back ups.

Of course there are many ways to back up a project but if you are using the standard version control workflow, your code is automatically backed up as a matter of course.  You don't have to remember to back things up, back-ups happen as a natural result of your everyday way of doing things. 

## Making your project easier to install

## Automatically run all of your tests

# Collaboration and Community

How git and GitHub can make it easier to collaborate with others on computational projects.

## Control exactly who can see your work

## Faciliate discussion about your work

## Allow others to contribute to your work

# Reproducible research

How git and GitHub can contribute to improved reproducible research.

## Which version gave these results?

## Making your software citable

## Building a computational environment based on your repo

# Further Resources

**Graphical User Interfaces to git**

PLACEHOLDER FOR GIT DESKTOP, GIT KRACKEN AND ALL THAT JAZZ

**Further discussions from scientific computing practitioners that discuss using version control as part of a healthy approach to scientific computing**

* [Good Enough Practices in Scientific Computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510) - 
* [Is Your Research Software Correct?](https://mikecroucher.github.io/MLPM_talk/) - A presentation from Mike Croucher discussing what can go wrong in computational research and what practices can be adopted to do help us do better
* [The Turing Way](https://www.turing.ac.uk/research/research-projects/turing-way-handbook-reproducible-data-science) A handbook of good practice in data science brought to you from the Alan Turning Institute
* [A guide to reproducible code in ecology and evolution](https://www.britishecologicalsociety.org/wp-content/uploads/2017/12/guide-to-reproducible-code.pdf) - A handbook from the British Ecological Society that discusses version control as part of general good practice

**Learning version control**

Convinced? Want to start learning?  Let's begin!

* [Git lesson from Software Carpentry](https://swcarpentry.github.io/git-novice/) - A free, community written tutorial on the basics of git version control


