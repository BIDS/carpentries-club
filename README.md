# The Berkeley Carpentries Club

This is the website for the Berkeley Carpentries Club at the
University of California - Berkeley. The rendered website can be found
[here](http://bids.github.io/carpentries-club). The code for the website (using GitHub pages) is in /docs.


### Join us

If you'd like to add yourself to the list of instructors, make a [pull 
request](https://help.github.com/articles/creating-a-pull-request/) on our who.md page. 
If you know how to do that, please go right ahead. If you aren't sure about 
forks and pull requests, here are some detailed instructions:

#### Uploading Example Code

1. Go here: 
[https://github.com/BIDS/carpentries-club](https://github.com/BIDS/carpentries-club)
2. Press the Fork button ([you'll need a github account](https://github.com/signup))
3. In your terminal, execute `git clone https://github.com/YOURUSERNAME/carpentries-club.git`
4. Enter the new directory with `cd carpentries-club`
5. Add the Carpentries Club remote with `git remote add bcc https://github.com/BIDS/carpentries-club.git`
6. Fetch information about the THW remote with `git fetch bcc`
7. Now, you need to check what branch you're in `git branch`
8. Edit the `who.md` file in the `_docs` directory.
9. Add the file to the repo: `git add <path to file>`
10. Commit them. `git commit -m "I added myself"`
11. Git push to your origin with `git push origin master`
12. Navigate in your browser to https://github.com/YOURUSERNAME/carpentries-club and press the pull request button

#### Build the site locally

- Install Jekyll: `gem install jekyll`
- Run the jekyll server: `jekyll --server`

You should have a server up and running locally at <http://localhost:4000>.

## About this website.

It's all based on something @katyhuff forked. It's called Left.  It uses
jekyll.  It was extracted from [zachholman.com](http://zachholman.com/). That
is, we use Left to lay out this jekyll. 

Left is a clean, whitespace-happy layout for
[Jekyll](https://github.com/mojombo/jekyll).

We forked it for the Data Analysis Tools Series, and then forked it for the Carpentries Club.

### Left Licensing

The Left layout is [MIT](https://github.com/holman/left/blob/master/LICENSE) with no
added caveats. Left is the work of Zach Holman [@holman](https://twitter.com/holman).

![Left](http://cl.ly/image/3S2r1p2C0E2B/content)

