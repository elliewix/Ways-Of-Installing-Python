# Ways of installing Python

I find myself having to go over methods of installing Python over and over, so I'm going to document as many as I can in this notebook.  Each installation method should be in a separate section so instructors can link to whichever one you are supposed to you.  However, if you are on your own, I'll try to provide some guidance.

## The hedges

This is not going to attempt to be a corpus of every possible method, tool, or program, so there will be omissions.  I'm going to focus in the tools that I usually mention to my students first, and may add some in later.

Any commentary I provide is also biased toward the academic/research envirionment and not meant to speak toward full development shops. They have their own needs and can speak for themselves.

## There is no right answer

Unless you're being told to use something specific by an instructor or boss, then there is no one right answer for which tool to use.  Try a bunch out and go with the one that you like the most.  Also remember that it is normal for experienced users to have multiple tools that we utilize to match the task.  Your multiple tools should fall along a use spectrum from experimental, to light weight, to heavy development.

# Basic installation framework

At a very high level, you're going to have to install two things to work with Python:  Python itself and a tool for interacting with Python.  There are some built in methods of interacting with Python, and they'll work in a pinch, but most people will choose to use additional tools as their primary form of writing in Python.

# Step 1:  Install Python itself

I'm going to keep this simple: unless you're being told otherwise, just use Anaconda with the most recept version of Python (e.g. avoid the 2.x versions).

1. Go here: https://www.continuum.io/downloads
2. Download the visual installer for Python 3.6 (or above).
3. Wait, because this is a giant download
4. Install like a normal application thing.
5. Test your install with Appendix 1.
6. Once your installation is done and tested, install your IDEs of choice.

Anaconda provides an installation of Python in your system, but you don't usually directly interact with Anaconda to write Python. You will use specific editor tools to write Python, and those tools are connected (in a variety of ways) to your installation of Python.  Thus, those tools will launch Python and execute the code.  So the installation of Anaconda is necessary, even if it doesn't look like you'll be using it.

You'll start interacting with Anaconda more directly once you need to start doing more advanced envirionment managment, and is the subject for many tutorials and documentation that is not necesary to repeat here.

# The Grand Trio of Tools

This is at least how I like to think about it, and you're welcome to disagree.  I usually recommend having three levels tools in mind for use:

1. The "heavy" tool, an [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment) that you like and can help you keep track of things in a large project.  This may start as your sole tool as you're learning Python and can use the help of an IDE and then you start incorporating other tools as you get more advanced skills.
2. The light weight tool, which is likely just an advanced plain text editor rather than a full IDE. This tool is good for short/simple programs, or for code you need to have running for days on end (e.g. web scraping or large processing tools).
3. An interactive tool for experimentation, exploration, testing proof of concepts, etc.

I encourage you to have a combination of 1 & 3 or 2 & 3 depending on your preferences.  Some full IDEs also have interactive Python tools built in, so a single program might satisfy 1 & 3.  I will provide recommendations for each category.

For example, my personal trio is:

1. I actually have two:
	* PyCharm education edition for large processing scripts and instruction
	* Jupyter Notebooks for data exploration/munging
2. Sublime Text Editor
	* For large webscraping projects to run for ages or when I'm writing a one-off tool.
3. IPython
	* Interactive console that I will use in conjunction with 1 or 2 to experiment or check how data types interact.

## Heavy editors

There are many full IDEs for Python, so if you care about a specific feature to be present in an IDE, I suggest you search for that feature among lists of IDEs.  I aim to keep this list short becuase when you're a beginner long lists can be difficult to navigate.

Summary:

1.  Are you doing scientific python?
	* Yes:  Spyder or Jupyter Notebooks (try both see which works the best for your projects)
2.  Are you doing data anlysis/science and want the pandas things to be pretty?
	* Yes:  Jupyter Notebooks
3.  Are you just getting started with programming?
	* Yes: likely PyCharm Edu or Wing 101 will suit you the best, presuming that you're using traditional educational materials.  You might want to do Jupyter Notebooks if you're going down the data analysis track.
4. I DNGAF and just need to start somewhere
	* PyCharm Education edition

### PyCharm

Links: https://www.jetbrains.com/pycharm/

I usually have my students use PyCharm Education edition because it:

* has a cleaner interface
* less noisy with warning, style prompts, etc.
* as a nice big green button for running scripts
* still capable of connecting to anaconda environments
 
* Pros
	* Several free versions
	* Can be connected to anaconda environments
	* Good hooks to version control
	* Has a built in IPython interactive console
	* Project oriented enforced file structure
	* has a lot of pro tools as you move up to more complex tasks
	* Looks the same for mac/windows (as an instructor, this pleases me)
	* Looks like a normal application that you double click to open
* Cons
	* Sometimes too many style warnings, etc.
	* Complex setup windows
	* Project oriented enforced file structure (yup, repeating this as it might annoy some people, or be too much for quick/small scripts)

### Spyder

Links: http://pythonhosted.org/spyder/

This is not an evironment I've used much, but some people really like it.  This is an IDE designed for scientific computing, and will feel very similar to RStudio or Matlab.

* Pros
	* Free and comes as part of the anaconda installation
	* Variable view can be great for beginners
	* Has console and scripting view in a single display
	* Works very nicely with plots/data viz
	* Will feel very comfortable to an R or Matlab switcher
* Cons
	* Can be resource intesnsive, so not great for smaller computers
	* Requires command line to launch, which not all users will have permissions to do
	* Interface might be cluttered to some newcomers
	* Not as many syntax error warnings as PyCharm

### Jupyter Notebooks

Some will argue that this isn't a 'real' IDE, and my response to that is "I don't care." I don't need to repeat any of the glory of Jupyter Notebooks for data analyis, and there are other great tutorials worth spending time with if you like this.

* Pros:
	* Interactive exploration
	* Many tools automatically display nicer in the notebook envirionment
	* Heavily used and the standard tool in some scientific/data communities.
	* Easily sharable analytics
	* Inline data viz
	* Has nice presentation tools
	* You can store markdown content to capture narrative, documentation, etc. all in one document
* Cons:
	* Best for solo work, shared editing not awesome yet
	* Not quite plain text (it's giant json), so you have to interact with it rendered in a web browser
		* there are ways to export it out to HTML for easy sharing, but that's static and not interactive
	* The cell interaction can be confusing to some beginners and allows for accidental non-linear traps if y ou aren't prepared

### Others I haven't used

Not to just dump a bunch of links in here, but that's exactly what I'm about to do.

* Eclipse has Python plugins
* Wingware (http://www.wingware.com/)
	* They also have Wing 101 for beginners, which is a minimal editor for beginners: http://www.wingware.com/downloads/wingide-101

## 


# Appendix 1: Testing your Python installation

TODO.

# Appendix 2:  Hooking PyCharm to your anaconda environment


