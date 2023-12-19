---
title: Physical Caches
layout: page
date: 2023-12-10
---

I've been taking a computer architecture class this semester and it has me thinking about caches. Being in ghoul mode studying for finals this week, I'm starting to see caches everywhere. 

Take for example, the company Amazon. The entire business model is basically just a cache for physical goods. In warehouses all over the world, items with *high temporal and spatial locality* are stocked and ready for ~~access~~ *purchase*.

Keep the pencils stocked next to the erasers, next to the staplers. If a customer buys school supplies the access is simple. Warehouse overflowing? Its spring time and no one has bought a snow shovel in months, we can evict the *Least Recently Used* shovel, unfortunately the next customer may have to get it from secondary storage.

Customers are somewhat predictable. Every spring we put the snow shovels away, then panic when the first now falls and a million orders are rushing in. A stride predictor with a stride of 12 months solves our problem. Just make a timely prefetch in November and place a big order. I guess it is likely the vendors that actually do this, thats besides the point. 

But what I'm saying is kinda obvious and is not exclusive to Amazon. Why do we call a store a store? *Because it stores things*. When the store doesn't have an item, you have to wait for inventory, then maybe when the item is back in stock, they send you a message. Then maybe your processor broadcasts the item on the CDB and wakes up the sleepy instructions... Ok maybe thats a stretch.

Back to studying,

Justin