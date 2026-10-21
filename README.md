

<img src="/assets/icon.png" alt="Description" width="4%" /> $\color{#c45181}{\text{Let Me Learn}}$

I recently created a language learning app in Swift for macOs and plans to alter the UI to support iOS and maybe visionOS. The underlining architecture is written to work in all those platforms just the UI is not laid out to support those different form factors.

I always wanted to learn Japanese since I was a kid but never gotten to do it. And tried  a bunch of language learning platforms and really liked wanikani's approach to learning through spaced repetition, but money and only offer Japanese.

> **Note:** The reason there is not code in the repo is I am not sure yet whether I want to have this as an opensource project or not.

![alt text](/assets/07.png)

### $\color{#60c451}{\text{Features}}$

__Mastery Levels__

There is a $\color{#6286da}{\text{stats}}$ block on the right, there are few mastery levels, words the learner has reviewed x amount of times [the learner can change this amount] in the settings see the image

![](/assets/02.png)

| Mastery Level | Description |
| :-------------: | :-----------: |
| Review | Words in review these are words recently learned or words from other master levels in circulation |
| Guru | These words are no longer in the immediate review circulation but will be added occutionally after x amount of review circles |
| Master | These words will be add occutionally to the review circle after x amount of review circles but less than level guru, the learner is considered proficient with them |
| Grand Master | These words will not be added to the review circle. |


<div style="background: #568d62; border-radius: 10px; padding: 10px;">
    Learn and Review
</div>

<br>

> **Note:** The learn can view the word and its meaning etc during the learning/reviwing process of they have forgotten how to write the word or what it means

![](/assets/06.png)

__Review__
+ Based what you previously have learned and that word is yet to be mastered. if you look at the image, the learner will be quized on knowing how to write the word and the meaning. The review will include words from other matery levels after a certain amount of rotation so they do not forget the words.

__Learn__
+ Based on the setting, the learner will be continuously be fed a batch of words to learn. The learner can pause and continue review until they are comfortable to continue learning. Other blocks like $\color{#da6274}{\text{sentence learning}}$ allow the learner to learn words that are not in the queue to be learned.


[![alt text](/assets/04.png)](https://vimeo.com/manage/videos/1237883194)

<div style="background: #b3af3d; border-radius: 6px; padding: 10px;">
    Practice
</div>

+ Allows the learning to practice every word that currently in review, but the learner can go to any other blocks and practice words from those block except the $\color{#568d62}{\text{learn and review}}$.


<div style="background: #da6274; border-radius: 6px; padding: 10px;">
    Sentence Learning
</div>

+ Normally the learner in other language learning apps is fed words to learn as they progress, but in this case they use can continue learning the words as they go or they can type sentences or just words they would like to learn.  For


[![alt text](/assets/06.png)](https://vimeo.com/manage/videos/1237879948)




<img src="/assets/vimeo.png" alt="Description" width="4%" />

[Github](https://github.com/devpontsho/letmelearn)