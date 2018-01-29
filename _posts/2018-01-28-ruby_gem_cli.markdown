---
layout: post
title:      "Ruby Gem CLI"
date:       2018-01-28 19:17:30 -0500
permalink:  ruby_gem_cli
---

1/28/18
Starting my ruby gem cli project tonight. This is very exciting. The first thing I'm going to do is search for some cool ideas. I want to do something special or at least something cool. Some initial ideas are a Kids Eat Free Gem that scrapes the web for restaurants that are having a kids eat free night on that particular night, A movie rater gem that scrapes the web for popular ratings and returns an avg rating of a particular movie, some type of facial recognition scraper that would take in a photo and return any profiles with that face ( OpenCV Ruby gem for automatic face detection). I really like this last one so i think i will go ahead and make this decision for beginning my project. 

1/29/18
And inspiration strikes! So have you ever been in line at the bank or say walking your dog at the park and you this this devastatingly handsome gentleman (or beautiful gentlewoman for you guys) and maybe you even exchange some small talk. There is chemistry and even the all important ring finger method is returning false but can you ask for his or her number? Of course not! After all you've only just met, I mean how desperate are you? BUT there happens to be this new ruby gem "Search By Face" so you, in true stalker style, snap a photo when said beautiful person isn't looking. Pop the photo in "Search By Face" and behold said beautiful person's Learn Profile! What luck! Now you can crawl all over said beautiful person's github and see if their coding cred meets your ridiculously high standards - why your still single in the first place. Ha! So I'm excited to get started. Ideally this gem would return more than one type of profile so this project has definite extendability potential and many applications besides dating and or stalking. Today I'm going to code along with Avi here: https://learn.co/tracks/full-stack-web-development-v3/object-oriented-ruby/final-projects/cli-data-gem-walkthrough where he explains how to get started. Also I need to find a screen capture tool real quick so I can be recording my coding to meet the 30 min recording requirement. Ugh so finding a screen capture tool is not turning out to be as easy as i thought. I run Ubuntu and so far every package I have tried to install is an epic fail... Yay for this website: http://www.upubuntu.com/2016/11/6-best-screen-recordercapture-software.html where I found exactly what I needed for my Ubuntu 16.04 operating system. I recorded a quick video and the screen capture tool "recordMyDesktop" works perfectly. I had to increase the frames per second option to get rid of some cuttiness I saw in the video (yes that's a word today). An option to pause sound recording during the screen capturing would be nice but I can always just turn off the mic if I need to. Okay so screen capture tool is good to go. I shall now begin my gem coding adventure. Ps. Who the heck didn't code some type of spellcheck functionality into this blog application?? I can't splell all by myself!


So this blog is turning out to be quite useful for documentation. Sooo I built my gem project with the bundle gem command Avi shows us in the video mentioned above. All of that went quite smoothly. I linked the files and got a stubbed out cli working (yay for progress) and then I got to the point where I'm asking the user for a jpeg (probably) and I thought I better start aquainting myself with the ruby gem opencv that i will be using for the facial recognition portion of my gem. So first thing first install the gem right? wrong. This took almost 2 hours. There were libraries and dependencies that i dont quite understand and just when I thought all was lost I found this little gem (heh) https://github.com/ruby-opencv/ruby-opencv/issues/79 where somebody was having my same exact issue and their solution was also my solution so yay finally gem installed. Now I just have to figure out how to use a gem inside a gem....




















