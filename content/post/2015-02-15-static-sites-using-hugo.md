{
    "title": "Static Sites Using Hugo",
    "date": "2015-02-15"
}

[Hugo](http://gohugo.io/) is "A Fast &amp; Modern Static Website Engine" or basically a static site generator it's built using [Go](http://golang.org/) and generates static HTML files with no dependencies on expensive backend runtimes like PHP, Ruby or Python and without the need for a database.

Hugo uses Markdown files for content and generates the flat HTML files for pages, posts and whatever you have setup in the configuration. With Hugo being built with Go the static HTML files can be generated in seconds and it can generates 1000s of pages in seconds too.

For my latest attempt at running a blog, I didn't want the complexity of a system like Wordpress or other similar blog platforms. I also didn't want implement my own blog platform using a framework. I wanted a simple flat static site with HTML to reduce the risk of vulnerability to bugs. Using a framework or blogging platform would mean I'd need to update the system if a bug was reported.

They're many different static site generators out available; [Jekyll](http://jekyllrb.com/), [Octopress](http://octopress.org/), [Pelican](http://blog.getpelican.com/) and many more. I personally went with Hugo because of it being built with GoLang. GoLang is a programming language am looking to learn and use, so I thought running a blog generated with Hugo would be a good way to learn the language.