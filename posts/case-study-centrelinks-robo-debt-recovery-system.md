.. title: Case Study: Centrelink’s robo debt recovery system
.. slug: case-study-centrelinks-robo-debt-recovery-system
.. date: 2018-02-18 18:07:49 UTC+11:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text


This is part of the assignments for Data Science Ethics.
 
# Case Study: Centrelink's robo debt recovery system

## Introduction:

Cenrelink is an Australian government agency in charge of "deliver social security payments and services to Australians." Since 2016, the agency implemented a debt recovery system without human intervention to recovery so-called "over payment" using black-box algorithms. It was believed that before the system was in place, the agency issued about 20,000 interventions (debt recovery letters) a year but now the same interventions just a week. The government agency said one in five incidents were resolved without a debt being issued and critics said that this was evidence of 20 per cent error rate.

Listening to this audio report [1][1] and reading stories on this website [2][2], the system sounds very flawed and unfair. People have identified miscalculation of the algorithms. From the stories available online, it appears the government puts the responsibilities of proofing accuracy and resolution of debt onto the vulnerable people and has an intention to maximise financial gains.

Thanks to the Guardian news website, you can view news about this saga chronologically [3][3]. ABC (Australian Broadcasting Corporation) also provides a big picture here of the incident [4][4].

## Data Science

### Social Impact

From the NotMyDebt website, there are about 650 stories and 4.3 million dollars of debt reported. It was also reported that tens of thousands of debts were wiped or reduced [5][5]. This incident definitely has a big social impact and the question over validity and ethics is on solid ground.

### Privacy and Validity

We tend to believe the government will do the right thing so we often surrender our privacy and entrust all our personal data to it. We also expect the government will make sure its decisions are reasonable and right before carrying it out. Unfortunately it seems not the case here.

### Code of Ethics

Hidden behind the heavy door of the government bureau, a person or a group of them have implemented some kinds of Data Science techniques. Can we examine if the proposed two rules of Jagadish's Code of Ethics here apply to both the agency and the data scientist?

### Do not surprise

First, do we expect the government to use our data to catch wrong -doings?  Some people may argue that if you do nothing wrong, you won't be in trouble. But this doesn't set the boundary of what the government can or can't do with our data. Second, is using data science techniques without humans in the loop also a surprise? 

### Own the outcomes

If you follow the stories [3][3], it doesn't give an impression that the minister or the government is owning the outcomes at all. The minister believed the system works well but he can't be sure about many details and later remedies were made to prove that the system was not perfect. The biggest issue here is lack of transparency so we do really know that to what extent the government is right or the journalist is correct.

For individual data scientists, it is very easy to weigh the human costs in their algorithms in hindsight but the mistake was made. Can you really uphold these two "simple" principles in your job when you are working at a big organisation like the government? Are there factors contributing to the difficulties of foreseeing the problems? 

I also think that without a professional board or committee, it would be a lot harder to point out the problem or "say no" to things against the principle.

## References:

[1]: http://www.abc.net.au/radionational/programs/backgroundbriefing/2017-03-05/8319442 "Audio: How Centrelink's 'robodebt' ran off the rails"
[2]: https://notmydebt.com.au/stories/notmydebt-stories "NotMyDebt Stories"
[3]: https://www.theguardian.com/australia-news/centrelink-debt-recovery "Centrelink Debt Recovery"
[4]: http://www.abc.net.au/news/2017-03-03/centrelink-debt-controversy-what-is-robodebt/8317764 "We're all talking about the Centrelink debt controversy, but what is 'robodebt' anyway?"
[5]: https://www.theguardian.com/australia-news/2017/sep/13/centrelink-scandal-tens-of-thousands-of-welfare-debts-wiped-or-reduced "Centrelink scandal: tens of thousands of welfare debts wiped or reduced"

    [1]: http://www.abc.net.au/radionational/programs/backgroundbriefing/2017-03-05/8319442 "Audio: How Centrelink's 'robodebt' ran off the rails"
    [2]: https://notmydebt.com.au/stories/notmydebt-stories "NotMyDebt Stories"
    [3]: https://www.theguardian.com/australia-news/centrelink-debt-recovery "Centrelink Debt Recovery"
    [4]: http://www.abc.net.au/news/2017-03-03/centrelink-debt-controversy-what-is-robodebt/8317764 "We're all talking about the Centrelink debt controversy, but what is 'robodebt' anyway?"
    [5]: https://www.theguardian.com/australia-news/2017/sep/13/centrelink-scandal-tens-of-thousands-of-welfare-debts-wiped-or-reduced "Centrelink scandal: tens of thousands of welfare debts wiped or reduced"
