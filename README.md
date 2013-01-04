The Ultimate Manager
===

Introduction
====

Everything in life has to be managed.

This project first started as an idea about applications management, something close to what we usually know as packages managers in the Unix world, but that we can also find everywhere, especially knowadays with the concept of Apps Markets.

Then, it turned out to managing any kind of data, like musics (more generally multimedia), documents (administratives for instance), projects and so on: we call all of this contents. Therefore, we come to a known concept: Content Management System (CMS). However, the goal is clearly to manage content, not to build a website (this would be only the GUI part).

The thing is that managing contents is a problematic well known with current CMS, DBMS... Thus, the focus has to be done on concepts, design... and on the (G)UI part. This has to be efficient and ergonomic, centered around human workflows.

This led to managing components of an applications, like intelligent auto-building modular systems, focused on End User Programming. This is related to current frameworks to build applications.

Finally, doing such a project, as any project IMHO, requires a good management of knowledge.

As you see, everything has to be managed: contents, components, knowledge, etc.

Key requirements/features
====

* Data
  * Management: [CRUD](http://en.wikipedia.org/wiki/Create,_read,_update_and_delete), data conversions/adaptation (kind of views on data, often called models)
  * Everything is data: content, part of the applications, more internal things...
* GUI
  * Editors: focus on the type of data to edit
  * Everything must be done and seen in real-time (dynamism)
* Full logs/traces: everything that has been done must be stored at the moment it has been done, with comprehensive information - it's easier to store every information at the right moment, barely possible to do it after the event (we can still adapt this information later if necessary). Thus, we can access every version, interact with _old_ versions (go back to a previous version for instance, still keeping the one before), view the history

Tools stack
====

Try to stick to one thing: an unlimited but powerful and highly scalable programming environment.

This means I consider for instance HTML and CSS as serialization, exchange or whatever languages, not as to be used by end users.

I think through models, and just want the best way to manipulate them. Model is the core. All the rest is an interface (browser engine, languages, ...)

* Environment
   * _Web_
      * Programming: JavaScript based
         * [LiveScript](http://livescript.net/)
      * Server-side: [Node.js](http://nodejs.org/)
      * Client-side: main browsers

Libraries/Framework
=====

* [Underscore.js]()/[Lo-Dash](http://lodash.com/)
* [jQuery](http://jquery.com/)/[zepto.js](http://zeptojs.com/)
* [Backbone.js](http://backbonejs.org/)?: I don't think so, but find an equivalent among the world of [AngularJS](http://angularjs.org/), [Ember.js](http://emberjs.com/), [SproutCore](http://sproutcore.com/), ... See comparison studies.
  * [Meteor](http://www.meteor.com/) seems really interesting!!

Key models
====

* [Graph theory](http://en.wikipedia.org/wiki/Graph_theory)
