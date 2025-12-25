
## Submitting changes

If you know how, you can reach out to michael, otherwise just open an issue via
the github issue tracker.


### The website

The website is a static html page, so you can edit the source files directly.

It's very basic but we're currently working on modernizing and cleaning up the html.
Also we have been moving design implemtation to CSS.

While there is some JavaScript in the HTML, we've avoided heavy dependancies on
JS for the time being as this makes the site portable and easy to move without
majorly breaking anything.  

The website has been up for 30 years and it's still viewable by the public, at
this point we'd like to keep it that way as long as possible.

### Current needs
At this point we need
- Updates for any links, especally for ele_mental folks listed in /who or
  /orbits
- Updates for any names dj or otherwise!
- If you're one of the persons listed and don't want to be listed, please let
  us know.
- Current projects! What are you doing?  We want to know.

### "Pull Requests"

You can submit changes directly using the github "Pull Request".  Note this
does require a github account and some knowledge of github, but not too much.
There are also tools to make it easier. 

We welcome contributions but be aware that this is a volunteer project and it
can take some time to get merged and as we are trying to update the codebase
and simplify things a change especally to the design might be hard to merge.
If you have a major proposal, please open an issue first.

The basic steps are:

1. Fork the repo.  That is create a copy of the repo on your own github account.

- Optionally you can download your forked repo and make changes locally.

2. Create a branch for your changes.

- if you're using the command line: `git checkout -b my-changes`
- if you're using the Github web interface: create a new branch from the main branch

3. Make your changes with the editor of your choice or using the github web
interface and save them.

- Note: You may have some problems with line endings, especally on windows.
  Reach out if you have any issues.

4. Commit your changes. That bundle up all your changes into one commit.  The
commit can contain many changes and multiple files but it's best to keep it simple.

- Example: Fixing links for ele_mental folks 
- from the command line: `git add ./file_i_changed.html && git commit -m "This is what I did"`

5. Open a pull request.

- If you're using the command line: `git push --set-upstream origin my-changes`
- If you're using the github web interface: "create a pull request"


Here's [the full "official" instructions from github](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) if you need a deeper explanation.

Note: The codebase is designed to be run from a webserver.  If you
just look at the files in a browser, the styling will look broken.

One way to handle this is to run a local server from the command line with `python3 -m http.server 2122`

Make sure you're in the directory as the website code.  Then you can open a browser and go to http://localhost:2122




