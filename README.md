# ooux-object-wiki
A boilerplate for rapid prototyping of OOUX objects and their relationships

## What is it?

This boilerplate is a [TiddlyWiki] (tiddlywiki.com/) - a lightweight wiki that is built into a single .html file.

It contains templates and examples useful to quickly constructing an object model like the one's described in Sophia Voychehovski's articles [\[1\]](http://alistapart.com/article/object-oriented-ux "Object-Oriented UX") [\[2\]] (http://alistapart.com/article/ooux-a-foundation-for-interaction-design "OOUX: A Foundation for Interaction Design") about Object-Oriented UX which appeared on A List Apart in 2015 and 2016.

## Why did you make this?

I realise that I wanted a tool that would allow me to rapidly move from post-it notes to a live OOUX diagram that I can view from two perspectives:
* a clickable journey view I could use to explore the structure
* "bird’s eye" system view of all objects

I want to use this tool to confirm consistency in an object model for a UX project, and to potentially use it as a lo-fidelity test with customers. 

FWIW, from a consistency perspective, it's already shown it's value - in the DIY example there's an inconsistency in Sophia's labeling of objects ("challenges" vs "projects") that I picked up converting the post-it notes into an object wiki.


## What's in the box?
You'll find these two examples set up as linked objects.

### DIY Example
![DIY Example from Voychehovski 2015 article] (http://alistapart.com/d/431/image8-stickynotes.png)

### Recipe Example
![Recipe Example from Voychehovski 2015 article] (http://alistapart.com/d/431/image3-recipes.png)


## Hints

* Using an application like [TiddlyDesktop] (https://github.com/Jermolene/TiddlyDesktop) makes a big difference - allows you to avoid the proliferation of files that comes with editing a TiddlyWiki in your browser. TiddlyDesktop also does automated backups, by default.
* Create an overview tiddler - this is where you put your photo of your post-it note session
* Tags are tiddlers themselves, so use the name of your overview tiddler (in the examples these are "DIY Model" and "Recipe Model") as the tag to connect all other tiddlers in the model back to your overview. This also allows you to quickly jump between objects in the same model. Try clicking on the "DIY Model" tag to see what I mean.


## Limitations

TiddlyWiki is not a sophisticated wiki, so this should be treated as a prototyping tool, rather than a documentation tool.
For example:
* modifying the name of an object (e.g. "Challenges" to "Projects") doesn't modify all the references to that object - you need to go through and update these manually (though it will quickly show you broken links - which are italicised). If you need that kind of sophistication, use a more mature wiki, like [Confluence] (https://www.atlassian.com/software/confluence).
