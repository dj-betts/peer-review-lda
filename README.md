# peer-review-lda

This a morning project to attemt use LDA to do topical analyist of peer reviews. Corpus is peer reviews collected over a 3 month data science immersive. 

01/22 after copy + pasting reviews into txt file. I copied the NLP jupyter notebook file that I used for a random forest classifier that I built for a unrealted project. 

Inital findings at 3 topics, no min/max df were unclear. With ngram range (2,4), .9 maxdf, and minor additions to the stop_word_lda list I start to see more interesting topics. 

---

Topic 0:
very good at working through good at worked together fun work very good stats week seems understands problem discusses it same things can really relate
Topic 1:
willing ask ask questions up for all find solution exceptional team mate worked enjoyed working betts enjoy when on team all future assignments case would like pair when on
Topic 2:
great work like working very similar will make other lot what you great handle on material addition any group getter that what you skill levels

---

Next steps.
1. develop stop word list for ngram range (1,1).
2. test various ngram ranges
3. plot min/max df v. feature count to tune min/max df.