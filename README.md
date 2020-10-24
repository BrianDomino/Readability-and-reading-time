# Readability-and-reading-time
Calculates estimated reading time and automated readability index for a webpage or file.

To help my students with time-management, I like to include an estimated reading time and
readability index for the reading assignments. This short program first asks for the URL
of the reading. The program works only with publically accessible, non-password protected pages (like Wikipedia).

It saves the page to a file and then gives you a chance to edit it. I've done this because I often do not
have my students read the entirety of page. This also gives you the opportunity to remove
other portions that students do not typically need to read (like bibliographies). Because I use readings from a variety
of sources, I didn't think it was worth automating this (I also don't think I could).

Alternatively, you could create a file named `cleaned reading.txt` in the working directory, and then
run the code from after the cleaning prompt. You would need to run the first cell if you've not done
so already.

The program then prints something like this to the screen:

> Estimated reading time: 59.76 minutes; approximate US grade level: 12.40 (what's this?).

Obviously the numeric portions would differ depending on the text used.

The "what's this?" I use to link to an explanation in the CMS:

> For the reading assignments you are told the estimated reading time, and the approximate US grade level for that reading. The reading time is simply the number of  words in the reading divided by 200. I do not think that this is particularly accurate since it ignores the difficulty of the reading. To compensate, I am also 
> including the US grade level for that reading, which I have calculated using the [automated readability index](https://en.wikipedia.org/wiki/Automated_readability_index). There are many 
> readability indices and I am not qualified to say which is the most accurate. I have chosen this one because it matches my intuitions about the reading levels of  the assignments. Other scales, such as the Flesch-Kincaid, tend to downplay the difficulty in my opinion. Please note that reading level is not the same thing as  your current grade level. For example, a high school graduate does not automatically have a 12th grade reading level. They may read at a higher or lower level. 
> This is also true if you know more than one language. Your reading level in each language probably varies.
