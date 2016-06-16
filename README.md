# Lakehead University Computer Science Club
This repository contains the source file for the website hosted at 
http://p24601.github.io/ComputerScienceClub/

If you find any bugs, issues or have concerns with the site, please submit an issue to us through GitHub, and we will deal 
with it as quickly as possible


## Editing the Website
The site is built using a MkDocs (http://www.mkdocs.org/). Follow the installation instructions on their main site.

#### Step 1
Clone the main repository

If you're unfamiliar with Git, do this:

You will need to have git installed, and gits root directory in your PATHS.

* Navigate to the directory you want the files to be stored. Shift-Right-click and select open command line here.
* Type the command: ```git clone https://github.com/p24601/ComputerScienceClub```
* You will have to enter your github username & password here (because this is a private repository)

#### Step 2
After making your changes, check your edits locally with ```mkdocs serve```

*This just opens a server at port 8000 so you can check out the site.

#### Step 3
Generate new HTML files. From the src directory execute: ```mkdocs build```

#### Step 4
To push the changes to the live site, execute ```mkdocs gh-deploy --clean```

