# aidan_assignment_3
# Alfred Lord Tennyson Poems
In this assignment, I scraped a corpus of Alfred Lord Tennyson poems from the internet. In my attempt I struggled to scrape it from the specific website I used, due to the complexity of its layout in HTML. So I used a sample of 5 poems, and web scraped each of them from their own individual URL's. The poems were from https://www.simple-poetry.com/, which is an open online library of poems and other works of famous poets. There were many more poems by Lord Tennyson on this website which I was unable to include, an issue which I can deal with in the future by being more meticulous in my search for a more simple website that provides transcripts of these works.

# Description
These poems were all publsihed by Lord Tennyson in the 19th century and all cover broad topics, but are generally tonally quite melancholic. In this repository I have listed a .ipnyb file with the code I used and a csv file contaning the data I scraped from the web. This repository may serve as a guide for anyone interested in the works of Lord Tennyson.

# Method
I labelled 5 URL's with the title of each of their respective poems and successfully created a dataframe coating these linked datapoints. Once made, I scraped the links to get the raw version of the poems. In this same code I added a for loop to clean up the text and get rid of excess text. Then I added this to the wider dataframe which contaiend 3 columns, the poem name, the URL and the actual text. Then finally I converted it into a csv file.

I analysed the terms and condition of the website, and apart from the privacy statement, I found nothing pertaining to the actual use of the data. It is more broadly a platform for poets to share their work with the world. Lord Tennysons works were also published in the 19th century, so there are no applicable copyright laws.
