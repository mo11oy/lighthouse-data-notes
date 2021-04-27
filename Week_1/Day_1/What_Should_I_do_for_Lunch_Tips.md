### Tips

I could not commit to http into github, I think its the two step verification (it needs a token) The way around was to use a url, but to use a url, I first had to delete the http by:

* git remote -v
* git remote remove origin
* git remote add origin git@github.com:mo11oy/lighthouse-data-notes.git
* git push -u origin master
After pushing once, this wouldn't work either, because git knows where to push.
So the process becomes...
* git add README.md (or -A)
* git commit -m "weblink update"
* git push


Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

