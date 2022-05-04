# CasualStories
a dataset of personal stories extracted from [r/CasualConversation](https://www.reddit.com/r/CasualConversation/) (from 2011 01.12 to 2021 01.12).
The thread contains posts on general topics: what movie to watch, how my day was e.t.c. I tried to clean the dataset (delete links, vocatives, questions on what movie to choose e.t.c) and extract the stories from it.
This dataset aims to provide human-written personal stories for training neural networks.

the structure is: _id_, id, title, text, length (in words)

Cleaning steps:
1) 149 < post length in charactes < 1000
2) delete markdown, duplicates, usernames, subreddits mentions, tldr
3) delete texts with (nsfw, death, dead, dying, died, dies, suicide, self-harm, f\*ck, b\*tch, \*ss, \*sshole, wh\*re)
4) delete requests, questions, thanksgiving (reddit discourse marks: 'want to hear', 'any ideas', 'tell me' etc)

Sample story:<br>
_Title_: I just bought my first stock!
_Before_: I have been doing a couple weeks of learning and discussing stocks with someone who has been doing it for a couple of decades. I have been patient and waited to make my first move of hopefully plenty more in years to come :) I am excited to see how it goes. I have stacked the odds in my favor and I hope it works out. 

Have you taken steps towards something new recently?

_After_: I have been doing a couple weeks of learning and discussing stocks with someone who has been doing it for a couple of decades. I have been patient and waited to make my first move of hopefully plenty more in years to come :) I am excited to see how it goes. I have stacked the odds in my favor and I hope it works out.



