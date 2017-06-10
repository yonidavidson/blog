---
title: Post WWDC-2017 thoughts on AI?
date: "2017-07-10"
layout: post
path: "/ai-client-review/"
category: "AI"
description: "A review I did (and sent to my co-workers) after WWDC-2017"
---

So Apple announced they are adding a framework for iPhones to do AI – Why would them?

TL;DR: Client side AI is the next frontier. 

In the last few years (around 3) - AI as become the main acceleration vector for companies like google,microsoft and Facebook.
They have invested huge amounts of money in talent acquisition and they are actually running the biggest research facilities in the world for AI and deep learning.

First frontier to be conquered was the server side AI where Google, AWS, Microsoft, and IBM have all created or bought Image, voice, and text recognition abilities and they are giving it for cheap.
The abilities are Amazing - Full feature recognition in videos, Voice emulation , Conversation bots etc.

The next frontier is client side – and mobile in particular (On PC’s its rather easier since you have a lot of HD space and memory).
This is shown in image recognition ('Face-Swap' is a good example how you take amazing tech and turn it into a profitable and stupid feature) and voice recognition is turning more and more client based (This will make the response time much faster).

The main idea behind this logic is the understanding that to get a very good feature quality you have to let machines design the algorithms and not humans (Deep learning and how it took over AI is another email) - And the amount of data that this companies have lets them train AI to build the features for them (think about it next time you upload your images to google photos and you wonder why its free).

So what are the big companies doing about it:

Facebook – they developed Caffe2go – A framework for AI on mobile. https://code.facebook.com/posts/196146247499076/delivering-real-time-ai-in-the-palm-of-your-hand/

Google – Tensorflow light- This is an implementation of Deep learning framework TF but running on mobile (Today’s its possible but it’s rather heavy and not developer friendly) https://techcrunch.com/2017/05/17/googles-tensorflow-lite-brings-machine-learning-to-android-devices/

Apple with the latest announcement: https://www.theverge.com/2017/6/5/15725994/apple-mobile-ai-chip-announced-wwdc-2017

AWS – they are investing in a framework called Mxnet- which is so small you can transpile it to javascript and run on the web: http://www.allthingsdistributed.com/2016/11/mxnet-default-framework-deep-learning-aws.html.

So what do you care?
* Look around you – most startups today write deep learning on the front page (And not for a good reason).

* AI is not for PHD candidates anymore – you can do it too – frameworks today are getting more and more high level and are oriented for application engineers rather then researchers.
* There is a lot of free quality code out there – just look for it - https://github.com/facebookresearch/fastText .