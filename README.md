
# My Website 

Source code for my website located at : http://prashantkhurana.github.io/

Built using hugo.

## Steps to run locally

* Clone the repo with recursive flag i.e. `git clone --recursive  https://github.com/prashantkhurana/my-website`. 
* Make sure you have [hugo](https://gohugo.io/getting-started/quick-start/) installed.
* Running `hugo server -D` will start a hugo server with the contents of the website.
* Running `hugo` will put the contents in public directory[^fn1]
* cd to public directory and push the changes and then push the state of the new submodule to the main repo.


## Add new blog post
Run `hugo new blog/blog-title.md`

[^fn1]: If needed , clear the public directory first (`rm -rf public/*`) and then run hugo.