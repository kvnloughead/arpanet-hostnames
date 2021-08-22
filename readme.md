# Arpanet Hostnames Data Cleaning

## Intro

This is an attempt to convert the hostnames lists (and potentially other data) from the [Arpanet Directories](https://www.google.com/books/edition/ARPANET_Directory/AHo-AQAAIAAJ?hl=en&gbpv=1&dq=arpanet+directory&printsec=frontcover)<sup>1</sup> of 1976-78 into a machine readable format.
It seems that a lot of this information is not readily available.

## Background

Recently I had the idea to try to create a map of early computer networks. Maybe a time series of maps, showing the evolution over time. Early timeshare networks, Plato, Arpanet, etc. Interactive, of course, allowing users to click on nodes to see more information about them. Of course, this would be an enormous undertaking. Especially since I don't actually really know how to do it.

So it occurred to me to start smaller. The Arpanet began as only two nodes, and those are known. You can get the names and locations for the first x nodes<sup>2</sup> (or _hosts_, as they were called). But after the first x it is more difficult. I spent more than a few hours scouring the internet. I won't detail the results of that research here. I'll just say that it wasn't very successful.

But it wasn't completely unsuccessful. There are lots of scanned copies of Arpanet documents out there. They include the Arpanet Directories, which were a Yellowpages of sorts. The started being compiled (I believe) in the mid-70's, at SRI (Stanford Research Institute). I found some, but not all, versions. Google books had the 1976 version. I downloaded it and have been trying to massage it into decent dataset. In the process, I realized that the document I had actually contained the Directories from 1976 all the way to 1978. 


<sup>1</sup> This pdf actually contains the directories from 1976-1978, although this is not indicated on the Google books page.

<sup>2</sup> For x equals 10 or 20? I forget.