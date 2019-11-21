This is a template for the EDAV final project. It is based on the template created with *File   New Project... New Directory    Book Project using bookdown* in RStudio. 

## ABSOLUTE ESSENTIALS

### GitHub pages setup

On the home page of your repo, click Settings. Scroll down to the GitHub pages section and change **Source** to **master branch /docs folder**.  The URL of your book will be displayed in the green bar above **Source**. (Although the URL is displayed immediately, sometimes there is a delay until the book is actually published.)

### File edits

Clone the repo and make the following five changes to these files:

`index.Rmd`:

Change YOUR TITLE HERE to your title  

Change YOUR NAMES HERE to your names

`_bookdown.yml`:

Change YOUR GITHUB USERNAME to your GitHub username

Change YOUR GITHUB REPO to your GitHub repo name

`_output.yml`:

Change YOUR SHORT TITLE to a shortened version of your title

(Leave the "after:" line as is)

### Render the book

Render locally with `bookdown::render_book("index.Rmd")` and then push the `docs` folder and any other changes to GitHub. You will need to do this every time you wish to update the book online.


## Nonessentials

See ... for a quick summary of additional bookdown features relevant to this project.

For the official guide to **bookdown** see: https://bookdown.org/yihui/bookdown.

