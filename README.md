# ShakespearePlusYear Plan

## A plan to read all of Shakespeare plus more playwrights

I've seen a fair number of "Read all of Shakespeare in a year" posts- 

I added the **Plus** for two reasons:

1. You don't have to set the parameters to one year- you can still work through the complete works, on your own pace. I'm doing **one** a month. 
2. There's more to plays than Shakespeare. I'm also **reading one play by another playwright a month** and it's been a great combo

The sequence I'm using was created by Benjamin McEvoy and his post is in the source link I'm including here ⤵️ He also lists reccomended movies for each play, and those excellent reccs are credited as well.  

Reading Sequence Source: https://benjaminmcevoy.com/read-complete-works-shakespeare-year-recommended-reading-order/

Building off of his list, I'm adding a smoother way to parse the data, other ways to portray a reading plan, other data fields like year and genre, and other cool things that I find and make. 


### Data considerations

#### Years

Years are approximate. There's a considerable amount of scholarly work about this; a number of plays continued to be worked on and changed over the years as they were in production during Shakespeare's time. You'll frequently see the `Play+ThisYear` data range a bit in various books and sites, depending on whether the year is considered `"First year of known performance,"` `"First year Shakespeare may have started writing it,"` or a number of other factors. Years in my dataset are based on the earliest year listed in the approximate date attribution range for each play from the Enclycopedia Britannica: 


Source for the listed year: https://www.britannica.com/topic/list-of-plays-by-Shakespeare-2069685

#### Wordcount 
Wordcount is mostly accurate, with some caveats:

1. There are different versions of the plays- both during Shakespeare's time and the years shortly after his death, and now. Depending on the editor, how many stage directions are included, and other factors, you'll see word count range a bit.
2. For the narrative poems and sonnets, those are estimates. If you find an accurate wordcount source and can link to it, open a pull request and let me know


Source for most of the wordcount data: https://www.opensourceshakespeare.org/views/plays/plays_numwords.php

#### Pagecount (go by wordcount instead!)
Plays are much less dense than most other forms of writing, so if you're using wordcount or pagecount to estimate reading time, my reccomentation is to go by wordcount, especially as that data should only refer to the play, not any supplemental writing also in a book. 

Source for the pagecount data is drawn from the [Folger editions of Shakespeare's plays](https://www.folger.edu/folger-shakespeare-library-editions). The Folger editions include introductory essays, lots of notes, illustrations, one or two scholarly essays at the end, and a bibliography, sometimes with paragraphs of text explaining the books _in_ the bibliography. 

So, if you see 400 pages, the play is not that long. Charge ahead!




