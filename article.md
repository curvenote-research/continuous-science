---
title: Continuous Science
description: ''
---

+++ {"part": "abstract"}

There is an opportunity to accelerate scientific discoveries by modernizing how scientists share and work.
We draw comparisons between the open-access scientific movement and the movements of open source and draw comparisons around continuous practices that are increasingly common place in software, which can lead to massive speedups in communication (e.g. 46x) as well as increases in rigour (7x).

+++

::::{important} Video Walkthroughs of Ideas
:class: dropdown

:::{iframe} https://www.loom.com/embed/28898917ad054d38b7e868ca6b73336c
This video goes through some of the motivations of working on this problem and sets up a framework for thinking about how we change processes. Primarily this is framed around MyST. Linked talks are [refactoring geoscience education](https://www.youtube.com/watch?v=IW2LDsevvDk) and [deploying a reproducible course](https://www.youtube.com/watch?v=XY3Tq9Wd1_A).
:::

:::{iframe} https://www.youtube-nocookie.com/embed/uSbjpiUsdT0?si=Hun1k4jwqhxmpTvx
Goes through these same ideas in a presentation format, presentation through the SimPEG Seminar (https://seminars.simpeg.xyz/seminars/2022-04-cockett), built in MyST!
:::
::::

## Accelerating the speed of scientific breakthroughs

Difficult problems that are globally relevant and urgent - like climate change, pandemics, and water security - require us to radically rethink how we share knowledge and work on scientific breakthroughs. The demands of science [from society](https://www.sciencecoalition.org/wp-content/uploads/2020/03/Why-Fund-Science.pdf) are ever increasing to provide solutions and insights to these global challenges: new medicines, cure disease, new energy technologies, better ways to protect the environment, new technologies for economic growth and national defense, as well as better understanding the world we live in [@fig:why-fund-science].

```{figure} images/why-fund-science.png
:name: fig:why-fund-science
:width: 30%

[Why fund science](https://www.sciencecoalition.org/wp-content/uploads/2020/03/Why-Fund-Science.pdf)? This is what the US thinks about.
```

> How do we improve the speed at which science can produce these scientific breakthroughs?!

A common objection to accelerating science is by pointing at all of the potentially drastic consequences of increasing speed — scientists will burn out, we will decrease rigour, we are already overloaded by mountains of information, and who will review all the work?!

These challenges and consequences are very real. Scientists already work 53.96 hours a week on average, and only about 36% of their time is actually spent on research (8% on grants, 32% on teaching, and 24% on service) [@Link2008time]. Graduate students are six times more likely to experience depression than the general population [@Evans2018Evidence]. There are [2.6 million](https://www.universityworldnews.com/post.php?story=20180905095203579) scientific papers published every year and it is growing. The time it takes for the peer-review process is over three months, in high profile journals like Nature that time has almost doubled over the past decade [@Powell2016Does]. Rejections are anywhere from 50-90% [@Grossmann2021Current] with valuable reviews and expertise coming months or even years after the work is completed.

Simply saying “more of this, but faster” will exacerbate all of these problems. Instead, the way that science is conducted, evaluated and communicated requires radical change. Luckily, many of these changes are happening. There are institutional, national and cultural shifts towards open-access [@Else2018Radical] and there is beginning to be the normalization of preprints in many more fields [@Else2020How]. These are massive, and ongoing accomplishments that are changing the nature of scientific communication. The next decade of science-communication will be transformative (schematically shown in @fig:paradise as paradise!).

```{figure} images/force11-2019.png
:name:fig:paradise
:width: 60%

Günter Waibel talking at Force11 in 2019 about where we are on our journey towards open access science. And sketching a final push over the hump and a journey towards paradise 🏝. [Video here](https://www.youtube.com/watch?v=pB7R-juNaCg&list=PLtYOue8U25N1hFfRmMlOsYFGTDHnKjlLA).
```

One of the questions that I think about is what comes _after_ all of science switches to open-access? Are we done? Is that actually the paradise described? What other industries can science look to who have gone through a similar shift?

One analogy to look at is comparing the production and sharing of software to the production and sharing of knowledge. These analogies are illuminating, but not prescriptive. The journey scientific communication and technical knowledge production will take is distinct from software engineering and the pressures are requirements of business are very different than academia.

With that disclaimer, we will look at two aspects of software development:

1. open-source development and sharing; and
2. organizing and incentivizing teams through continuous practices.

## Comparing open-access & open-source

The timing of the open-access shift in scientific publishing has many analogues to where open-source was in the early 2000’s, with new distributed collaboration tools invented (e.g. Git in 2005) and new companies for collaboration, sharing and discovery built on these new ways of working (e.g. Atlassian & GitHub founded in 2002 & 2008, respectively). In software-development today, it is possible for two people who have never met to reuse each others ideas (in this case, software packages), and actually improve, fix and generalize these ideas. It happens without them meeting, planning, or really thinking about the coordination at all — which, frankly, is amazing. The coordination that brings together working and sharing is built into various levels of the infrastructure. The necessary first step in this scenario is clear and open licensing of content, which in science is the open-access movement, supported through legal tools like the Creative Commons Licenses (e.g. CC-BY). The other steps are to provide the

- Open-source
  - Legal
  - Technical
  - Social
- Organizationally
  - Smaller
  - Automated
  - Continuous

The services and standards changed the software industry fundamentally by enabling completely new modes of collaboration and organizational models to motivate, empower and connect people.

The practices of software development are well studied, with large-scale surveys of organizational performance, design, robustness, and speed ([DORA Reports](https://www.devops-research.com/research.html)). The main questions asked in the DORA Reports are how do companies improve the speed with which they can deliver software (tied to improved efficiency, profit and customer satisfaction), while not sacrificing rigour/quality or burning out employees.

> How do we accelerate the rate of scientific breakthroughs while also improving rigour, collaboration, mental-health, accessibility, and reproducibility in science?

The [2018 DORA Report](https://services.google.com/fh/files/misc/state-of-devops-2018.pdf) compared elite teams with low-performing teams for software delivery, and found that the elite teams were 46x faster, had 7x fewer errors, spent 20% more time on new work, had 5-20% less manual work, and were 1.8x more likely to recommend their team as a great place to work. _Let that sink in!_

> 46x faster. 7x fewer errors. 20% more time for new work. 5-20% less manual work. 1.8x more likely to love where they work.

As an unfair comparison: during COVID19, society managed to produce and manufacture a vaccine safely in [5-10x less time](https://coronavirus.jhu.edu/vaccines/timeline), but that has come at a cost in burnout, stress, loss of trust in scientists, and misinformation [@Gewin2021Pandemic; @Algan2021Trust]. The demands on science are mounting to deliver more scientific breakthroughs faster as humanity faces massive global challenges around climate, health and energy.

The analogies between open-access and open-source movements give us an opportunity to peek ahead 15 years to an analogous future and draw on the learnings of how the open-source development, and learnings on how to organize and focus infrastructure to get the best out of our community.

We will focus on three

- Changing the unit of scholarship towards smaller, reusable contributions (Force11)
- Distribute sharing and peer-review throughout the process of science
- Integrate data, computation and testing into how science is communicated

This is a powerful reminder that designing systems and infrastructure that empower individuals to work together, rapidly share updates, and have direct as well as automated feedback can fundamentally change ...

Currently many of these steps in conducting science are designed to happen in a consecutive sequence: define a problem or research area to secure grant funding, collect data, analyze and interpret the results, craft those results into a narrative — the scientific paper — submit it to be reviewed by peers, and finally share the finished work to inspire and be cited by future publications.

There are a lot of challenges in this workflow, for

- Peer review is expensive and less-effective at the _end_ of the process.
  - The authors of a work are often more interested in finishing, than incorporating feedback
    - incremental review, at the time of creation is more **effective, corrective and instructive**.
    - Authors may defend their work when feedback comes at the end, rather than framing as a collaborative improvement of the work
  - Peer review is treated _hurdle_ to get through, rather than an opportunity to learn, refine and improve.
    - See Review 3

Artifacts that are produced along the way.

Starting to modularize this process and improve and professionalize practices as the research work is being conducted.
(e.g. not doing typesetting where we add proper references at the end of a study, but as you are writing your notes).

```{figure} images/continuous-science.png
:name: fig:continuous-science
:align: center
:width: 70%
```

Continuous Science

There is a role for a new position whose job is the cultural and behavioral influencers, who align the system who improve the speed by changing the process of science.

Too much peer review.

- Getting the review at the right time.

Prestige model

- That is the biggest problem.

Earlier then you get the feedback.

Just the productivity side?

- The need for standardization
- Standard metrics for accomplishments

It is a continuum.

Early adoption:

- want 1% of users.
- Convince a hard core group of people to jump with you.
- intersection between open-source / open-science

Pay for prestige.
