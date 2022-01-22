---
layout: post
title:  "MalaOS"
date:   2022-02-22
excerpt: "MalaOS, optimized operative system"
project: true
tag:
- jekyll 
- moon
- blog
- about
- theme
comments: true
---


    
<center><b>MalaOS</b> an optimized operative system</center>
     
 I'm a spanish student learning optimization of operating systems, web development and Lua

## What is MalaOS?
* MalaOS is an optimized operating system dedicated for people who have average, low-resource PCs that often suffer from slow performance, stutters. This system has additional tools that it will be good for us to have to optimize our PC and also for people who play video games since MalaOS will allow us to optimize them.
      
## Installation
* Download [MalaOS Iso](https://github.com/TaylanTatli/Moon/fork)
* Download [Rufus](https://rufus.ie/)
* Open rufus and select `MalaOS.iso` file. Partition scheme in `GPT` and Target System `UEFI`, File System `FAT32` and Cluster Size `default`.
* Click the `start` button and wait.
* Once the USB is booted, we will proceed to install the operating system. For this we need to enter to boot the computer with the USB, we have to identify which is the boot key with USB of our computer, in my case it is F12.
* Now the computer boots with a windows installation interface but we will be installing MalaOS. Just follow the steps the interface/GUI gives you    
     
That's all. Now go to the Post Install Steps

## Preview

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png
	https://cloud.githubusercontent.com/assets/754514/14509717/61ad05ae-01d6-11e6-85ae-5a817dd8763b.png
	https://cloud.githubusercontent.com/assets/754514/14509714/61a89708-01d6-11e6-8fcd-74b002a060df.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=3 %}

---

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509718/61b09a20-01d6-11e6-8da1-4202ae4d83cd.png
	https://cloud.githubusercontent.com/assets/754514/14509715/61aa9d00-01d6-11e6-81a6-c6837edf2e84.png
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=2 %}      
      
See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.      

## Post Install Steps
A quick post install of the files/configuration you’ll will need to install to get up and running correctly.    

### Site Wide Configuration
`_config.yml` is your friend. Open it up and personalize it. Most variables are self explanatory but here's an explanation of each if needed:

#### title

The title of your site... shocker!

Example `title: My Awesome Site`


### Comments
To show disqus comments for your post add `comments: true` to your post's front matter.

---

## Questions?

Found a bug or aren't quite sure how something works? By all means [file a GitHub Issue](https://github.com/TaylanTatli/Moon/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the MIT License. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer.
