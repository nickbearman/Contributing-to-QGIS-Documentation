# Using Git Locally

We can clone our repo and use it locally on our machine, then sync (push) the changes to the web. 

- Download Git from https://git-scm.com/downloads
- Install it
	- Set editor to `Nano`

- Fork repo (on GitHub)

- Clone repo (`username/Contributing-to-QGIS-Documentation.git`)
	- Go to wherever your folder is
	- Right click - Git Bash
	- Type in 

`git clone https://github.com/nickbearman/Contributing-to-QGIS-Documentation.git`

This will copy the files over to your machine. 

Make a change. 

Save it. 

Use `git status` to look at current status

Stage it
- `git add ....<file>`
  
Commit it (with a description).
- `git commit`
  
Push it.
- `git push`

Then try adding an image in RST. See `example-1.rst` for an example. 
