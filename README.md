# Sherlock Holmes: Hounds of The Baskerville - word frequency and distributions (an on-going project)

### Table of contents:
- [Project overview](#project-overview)
- [Data sources](#data-sources)
- [Tools](#tools)
- [Key findings](#key-findings)
- [Limitations](#limitations)

### Project overview:

<img width="1754" alt="Screenshot 2024-07-29 at 17 56 03" src="https://github.com/user-attachments/assets/23621b5c-251f-43f2-868a-0d9c6c656ec6">

The aim of this project is to explore the word distibutions of sherlock holmes books and their counterpart on the BBC TV series Sherlock. Starting with The Hound of the Baskerville.
So far I extracted to frequency of appearnces of each word in both the book and the episode in the series, and created a dashboard to vizualize it. 
Future plans include understanding the frequency within which words appear together. 

[Link to Tableau dashboard](https://public.tableau.com/app/profile/omri.meir/viz/worddistribution_17222561342020/Dashboard1?publish=yes)

### Data Sources:
1. The Sherlock Holmes: Hounds of The Baskerville book came from [The Project Gutenberg](https://www.gutenberg.org/cache/epub/2852/pg2852-images.html).
2. The transcript of Sherlock Series 2 Episode 2 came from [HERE](https://arianedevere.livejournal.com/28352.html)

### Tools:
 - Jupyter notebook - fetching the text, proccessing it and counting the words
 - Tableau - Dashboard to visualize frequencies of words

### Key findings:
#### Book:
 - there are a total of 5535 unique words in the book and 26895 words in total(20.58%).
 - the 3 most common words are: 
 1. sir: 336 times 
 2. upon: 316 times
 3. said: 240 times
 
 The top 2 most common words are both words that appear much more in writing then in speaking, they also better represent the time of the writing of the book (25 March 1902)
 
#### TV Show:
 - 2976 unqiue words in the series episode and 11725 words in total(25.38%).
 - the 3 most common words are:
 1. sherlock:273 times
 2. john:242 times
 3. henry:158 times
 
 The 3 most common words are names of the main characters, which is very represtative of TV shows. 

#### Worth mention-ables:
 - The words Sherlock and John are much less common in the book than the tv show. This is likely because the books were written in times when even close friends used to call each other by last names. 
 - The words sir appears very little in the TV show, prehaps because it was much more common to call people sir back than. The word upon does not appear at all in the TV show transcript. 

### Limitations
- This is not a viable comparison, because that will be comparing book to script. This is more of an overview of both texts. 
- In the book, the narrator is John Watson, so his name doesn't appear as much. In the series there's no narrator, so John's name pops out a lot more. 
- The book contains more words and probably uses a much more descriptive language than the script.
