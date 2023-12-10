---
title: Physical Caches
layout: page
date: 2023-12-10
---

I've been taking a computer architecture class this semester and its got me thinking lots about caches. Being in ghoul mode studying for finals this week, I'm starting to see caches everywhere. 

Take for example, the company Amazon. Their entire business model is basically just a cache for physical goods. 
In their warehouses all over the world, items with *high temporal locality* (best selling items)
and *high spacial locality* (customers in Canada more likely to buy a snow shovel, Arizona not so much)
are stocked and ready for ~access~ *purchase*.

It also plays out into prefetching. Around chirstmas every year, amazon probably has some YOY stride predictor that says every 12 months certain toys are usually bought. So they make a timely prefetch in November place a big order. I guess it is likely the vendors that actually do this, thats besides the point. 

But what I'm saying is pretty obvious. Everyone has already known this. Why does English choose to use the word store? A store is called a *store*, because it stores things. And sometimes when the store doesn't have an item, you have to wait for inventory. Then maybe when the item is back in stock, they send you a message. Then your processor broadcasts the item on the CDB and wakes up the sleepy instructions... or maybe not.

Back to studying,

Justin