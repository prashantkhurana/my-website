
# My Website 

Source code for my website located at : https://prashantkhurana.com

Built using [hugo](http://gohugo.io/) and deployed via [netlify](https://www.netlify.com/). 

## Steps to run locally

* Clone the repo with recursive flag i.e. `git clone --recursive  https://github.com/prashantkhurana/my-website`. 
* Make sure you have [hugo](https://gohugo.io/getting-started/quick-start/) installed.
* Running `hugo server -D` will start a hugo server with the contents of the website.
* Running `hugo` will put the contents in public directory[^fn1]. Make sure the new post is not a draft. `draft:false`
* Git push. Netlify listens to the public directory and will handle the deploy


## Add new blog post
Run `hugo new blog/blog-title.md`

[^fn1]: If needed , clear the public directory first (`rm -rf public/*`) and then run hugo.