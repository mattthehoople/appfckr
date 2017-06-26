+++
draft = false
date = "2017-06-26T22:55:22+01:00"
title = "creating a static site with hugo"

+++

A longtime ago, when I started my career, I spent most of my time creating sites that displayed a bit of content. Sometimes this content was clever, sometimes it was dumb, but more often than not it was little more than a bit of information of some form or other, marked up in html and made to look not-terrible with a bit of css and some images. Sometimes, if we were feeling particularly daring, we'd use a bit of javascript to make it move around in some awe-inspiring way or other, but bottom line it was just content, and it was good.

Then, sometimes, the client, in their infinite wisdom, decided that they didn't want to pay us cold hard cash every time they wanted this content changed, and so they asked for this thing they'd heard of that would let them do that. "We need a CMS", they'd say, and it was not good.

"You don't want a CMS", we'd say, because we were nice like that. "CMS's need databases and some form of scripting languages and a server that supports such things, and a person to support that server, and all of that costs money and pain and heartache and it's a lot of effort for a bit of content that hardly ever changes."

"No", they'd say. "We want a CMS."

"Fuck", we'd say, but quietly. Then we'd make them a CMS, and we'd charge then some money for it, and they'd never ever use it.

And so started my long standing hatred of CMS's.

Things have changed a lot since then though, now we can create changeable sites for people that don't need databases or scripting languages and supporting servers and persons. Now we can give them the tools to generate the static pages they actually need without the need for computational power to create those pages from scratch every time they need to be served. Now we can just use a teeny bit of power whenever they do the editing, which as, we've discussed, they will never ever do.

But we're not them. We're us. And we've promised ourselves we're going to create lots of great content that will make to world a better place. So we will generate a static site, and in time we're going to do something clever with aws and s3 and lambdas to automagically regenerate our site whenever we change it. But first we need a static site generator. And for that we're going to use Hugo.
