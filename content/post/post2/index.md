---
title: 'IELTS Reading Band 9 Tips — An End to End Self-Study Guide'
subtitle: How I used Machine Learning techniques to improve my reading skill.
date: 2020-09-12
math: false
diagram: true
image:
  placement: 3
  caption: 'Photo by [Thought Catalog](https://unsplash.com/@thoughtcatalog?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)'
---

### Introduction

IELTS, which stands for International English Language Testing System, is a standard international English test that assesses English skills in four sections reading, writing, listening, and speaking. Most international institutes and universities put an IELTS minimum requirement for their international applicants, so they become sure that no communication issues happen for non-English speakers after the recruitment process.

Last year was so tough for me. Struggling with the undergraduate thesis, working on a research paper, communicating with professors and universities for my graduate program, and taking required tests were intensely overwhelming. I took IELTS because it was compulsory for my graduate study, and I succeeded in achieving the overall band score of 7.5. The impressive part of my result was the reading section, which I hopefully got a full mark score in that. IELTS Reading consists of 3 sections, 40 questions, 60 minutes

* Each section contains one long text.

* Texts are authentic and are taken from books, journals, magazines and newspapers. They have been written for a non-specialist audience and are on academic topics of general interest.

* Texts are appropriate to, and accessible to, candidates entering undergraduate or postgraduate courses or seeking professional registration.

* Texts range from the descriptive and factual to the discursive and analytical. Texts may contain non-verbal materials such as diagrams, graphs or illustrations. If texts contain technical terms, then a simple glossary is provided.

* There are three texts and 40 questions. [[reference]](https://www.examenglish.com/IELTS/IELTS_Academic_reading.html)

I will explain some tips that I used in my self-study to achieve this score in the current post.

The critical factor that makes this post unique is the fast achieving self-study approach that I will explain. For my undergraduate thesis, which resulted in an [ACL2020 WiNLP](http://www.winlp.org/winlp-2020-workshop) paper, I used ML approaches to gain the best result to detect individuals’ personality traits based on their essays. You can read the final version of my paper [here](http://www.winlp.org/wp-content/uploads/2020/final_papers/40_Paper.pdf). Since I was overwhelmed with several tasks , I did not find much time to focus on my IELTS study. So, I decided to leverage my ML skills to build a focused study plan to improve my IELTS result. Hopefully, it worked, and here, you can read my self-designed method.

This method is inspired by the Deep Learning models training process and consists of four parts: weight initialization, forward pass, backpropagation and error analysis, and optimization.

### The Start Line — Weight Initialization

{{< figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/master/static/media/psycho-pass.jpg" title="Two Main Characters (Kogami and Mikishima) in Psycho Pass. Photo from [wallpaperaccess](https://wallpaperaccess.com/psycho-pass)" >}}


When you want to learn a new subject, you should have a brief understanding of what you are going to do and how to start. That is the exact process that is used for training deep models too.

{{< figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/master/static/media/psycho-pass.jpg" title="Two Main Characters (Kogami and Mikishima) in Psycho Pass. Photo from [wallpaperaccess](https://wallpaperaccess.com/psycho-pass)" >}}

First, pick the dataset you want to learn. There are numerous test packs for IELTS, but none are as genuine as the original [Cambridge IELTS](https://ieltspracticeonline.com/download-all-cambridge-ielts-books-pdfaudio-1-14/) test books. As far as I know, 15 versions have been published, and each year, a newer version comes out based on the recent actual tests.

The second essential criterion before the beginning is how to start it? How can you commence something that you do not have any idea about it? That is easy! Just use what you have known before from your prior successful test experience and try to reuse it. For example, I remembered that I used to read the questions first and highlight the keywords before jumping into the text for my undergraduate university entrance exam. If you think that you are totally lost, you can get some help from these free resources, but keep in mind not to spend much on them at this phase:

* [New insight to IELTS](https://www.cambridge.org/us/cambridgeenglish/catalog/cambridge-english-exams-ielts/new-insight-ielts)

* [IELTS Liz](https://ieltsliz.com/ielts-reading-lessons-information-and-tips/)

* [IELTS Simon](https://ielts-simon.com/ielts-help-and-english-pr/ielts-reading/)

* [E2 IELTS](https://www.youtube.com/playlist?list=PLdawRnR9ilZDh4mWAjOm8MsqaJt03-YMR)

A similar method is also used for Deep Learning. Weights of the model are sometimes randomly assigned, and sometimes, which usually result in better accuracy, they are obtained based on the pre-trained models on other tasks. That is the exact thing you will do when you remember your previous experience to use it for this new test.

### Take a Sample Test — Forward Pass

{{< figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/b3ae473bb7177446b2416b4e73f7d56ffb792763/static/media/hope.gif" title="Photo from [shutterstock](https://www.shutterstock.com/)" >}}

Unfortunately, that is true. Suppose a kid who is trying to be a literature teacher, but his talent is in mathematics. A perfect model will decide that he is expected to be a mathematician rather than a poet or a literature teacher. From a broader perspective, each individual might only have a few options to pursue to build the most productive community. Sadly, our models are not capable of understanding our feelings and senses. They merely can interpret them by using the way we express ourselves in a limited manner. This is not sufficient, nor is it proper for understanding someone’s inner feelings.

### 2. No one will think outside of the box anymore

{{< figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/4774499face7ac420ac86348714d6c47cfc94adb/static/media/box.jpg" title="Photo by [Markus Spiske](https://unsplash.com/@markusspiske?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/)" >}}

Creativity is a common phenomenon that we realize is much more than just producing some apparently new things by combining the available ones. [GAN](https://en.wikipedia.org/wiki/Generative_adversarial_network) and [DeepFake](https://en.wikipedia.org/wiki/Deepfake) models are trying to do so, as well as [GPT-3](https://en.wikipedia.org/wiki/GPT-3) for Natural Language Generation. Suppose a sage who knows everything on the internet. Does a generative model like GPT-3 produce a novel article or even a paragraph that surprises the sage? The answer is no. Because everything it generates is somehow available on the internet. You first may become amazed by reading the Guardian’s [“why humans have nothing to fear from AI”](https://www.theguardian.com/commentisfree/2020/sep/08/robot-wrote-this-article-gpt-3) article . But the truth is that the model just decides which concepts and words are appropriate to be written by remembering the memorized texts. If you disagree, have a look at this [scientific explanation](https://www.youtube.com/watch?v=SY5PvZrJhLE) by Yannic Kilcher. Some new methods such as [SenticNet](https://sentic.net/senticnet-6.pdf), tried to combine human logic into subsymbolic AI, to make models that understand more and can predict better in the way we think. The idea is inspired by this wise saying:

**“you do not get discoveries in the sciences by taking huge amounts of data, throwing them into a computer and doing statistical analysis of them: that’s not the way you understand things, you have to have theoretical insights.”**   *Noam Chomsky*

Despite all these efforts, the problem has not been solved yet. You may think that this limitation is not a significant concern. But as we go further, the situation becomes more serious. Our models will become more accurate, and then they will monitor our activities. Imagine the case that you write a pure novel book, completely different from all the previous ones. Models will now evaluate your manuscript to identify where should it deserve to be published. Since your work is unalike from the prior successful publications, it probably will not get accepted as valuable work. Hence, your creativity will be suppressed. All of this is because it does not understand more than what has been learned before. It cannot digest the creativity.

**“We shape our tools and, thereafter, our tools shape us”**    *Marshall McLuhan*
    
### 3. Freedom in a cage, the myth of evolution

{{<figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/master/static/media/cage.png" title="Freedom Cage published November 27, 2012 by Sherif Arafa politicalcartoons.com" >}}


This is one of the consequences of the previous topic. Let me rephrase the quote above: They shape our tools; thereafter, our tools govern us. That is the fact. Keep in mind that your current wellbeing is for the sake of previous revolutions, people who tried to change the situation to make a better world. When censorship became automatic, by using methods such as Deep Packet Inception, nobody will be free anymore. This is not only the creativity that is suppressed but also the freedom, and everything that endangers the benefits of current government will be sacrificed. Rulers become cruel, and they eliminate everything that threatens their dictatorship. That is not a complex problem because the models magnify their acts, and they only should be concern about reducing False-negative predictions, individuals who are capable of rebellion and labeled as innocent. ‘Recall’ should be high, and anything else does not matter. If we reach this state, the evolution of society will be halted.

### 4. The distance between social classes will be fixed, or gradually widen.

{{< figure src="https://raw.githubusercontent.com/amirmohammadkz/starter-academic/master/static/media/penam.gif" title="Districts of Panem. Photo from [businessinsider](https://www.businessinsider.com/10-things-you-need-to-know-about-the-hunger-games-2012-3?international=true&r=US&IR=T#the-characters-live-in-districts-4)" >}}

This heading is partially connected with the first one. The problem arises when you are restricted to perform specific tasks based on your background. If we scrutinize this issue, the tasks are chosen based on our ancestors’ previous successful experience. It means, if you were born in a wealthy family, higher-quality jobs are probable to be assigned to you, and if your family is not wealthy, you might not have a chance to improve it. Rich people become richer and poor ones become poorer. This issue can also be extended to other areas such as social classes because all these problems are somehow intertwined. This social class division is demonstrated in [The Hunger Games](https://en.wikipedia.org/wiki/The_Hunger_Games) series of novels and movies. This issue encompasses not only individuals but also communities. Each society section will become isolated, and all unnecessary interactions between districts might be eliminated. And a day may come that you will not understand situations and things beyond your own community, and you may not know that they exist.

## Conclusion

This post may be somehow pessimistic, somehow far from reality, but anyway, these are concerns that I think this issue deserves more attention. Some of them may be wrong, but I believe devoting some time to think about our field’s probable destination, even if it might be wrong, is necessary.

If you disagree with me or have recommendations and comments, I appreciate if you write it in the comments.

### Did you find this page helpful? Consider sharing it 🙌
