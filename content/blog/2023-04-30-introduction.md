<!-- title: How I'm Hosting This Blog -->
<!-- author: Dave -->

## How This Blog Began
My goal was to see if I could accomplish one mission: generate a static site and auto deploy it on git commit. To seasoned web developers, this probably seems very trivial, but I wanted to see how far I could push the limits of my comfort. After all, I'm coming into this project with no knowledge of deploying sites.

![alt text](/images/cat.jpeg)

## The Constraints

I wanted to be able to accomplish the following
- a pipeline that auto deploys my site on merge to a production branch
- the ability to highlight code snippets, both with `code blocks` and with code snippets. 
- the ability to trigger an automatic build and merge (which in turn triggers the auto deploy) when something, somewhere detects that a new blog post has been uploaded
- how would my system know that a new blog post has been published? I have yet to think about that

```py
def function():
    return None
```

