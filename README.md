## Thinking about thinking, learning about learning

I build tools to help learners, and I'm interested in computational and mathematical modelling of human learning. My goal is to develop technologies to help learners reach real mastery in a breadth of subjects more efficiently. I'm especially interested in mathematics education: quantitative methods make science more robust and are the foundation of modelling, which is central to cognition itself and to how the brain understands the world.

### How I build

I use coding agents (mainly Claude Code currently) for much of my recent work, and I treat them as collaborators rather than autopilot: I design the architecture and review, test, and scrutinise what they produce, stepping in to write or debug the code myself where the tools get stuck. LangBiasTester and my earlier projects were written entirely by hand.

### Projects

- **[PaperSkillTree](https://github.com/gabrloureiro/PaperSkillTree)**: turns a scientific paper into a step-by-step learning path laid out by LLM agents with designated roles · *Python, JavaScript* · 2026
- **[Nomas](https://github.com/pedrobarbosaocb/nomas)**: swipe-based apartment hunting built on scraped, structured listings with information extracted from plain language descriptions · *Python, JavaScript, PostgreSQL* · 2026 · with [pedrobarbosaocb](http://github.com/pedrobarbosaocb)
- **[LangBiasTester](https://github.com/gabrloureiro/LangBiasTester)**: experiment software for my honours thesis on auditory language bias in bilinguals · *C#* · 2025-26

<details>

<summary>More detail</summary>

**PaperSkillTree**: Scientific papers can be extremely dense and challenging, especially for people who are not fully immersed in academia. PaperSkillTree aims to diminish this barrier by turning a scientific paper into a guided learning path. A team of LLM agents with different roles, orchestrated together in a LangGraph, plans a progression through the paper's concepts, then builds a dependency graph of topics. Learners move through it one topic at a time and unlock the next step by summarising each explanation in their own words. A tutor agent is available when something doesn't click.

**Nomas**: It can be incredibly overwhelming to try to find an apartment in a large city like Montreal. There are several listings in different platforms, often with mismatched information between their descriptions and the websites' filters, such that even trying to make the search easier does not help much. Nomas aims to solve this by centralising ads and using more reliable filters, derived from the listings' descriptions themselves. It scrapes listings from Kijiji and Facebook Marketplace and uses a small LLM to extract structured details (rooms, what's included, location and distance to metro stations). Users filter and rank what matters most to them, then review matching listings one at a time with a swipe, and contact landlords, roommates, or people passing on their lease from their shortlist.
*Built with [pedrobarbosaocb](http://github.com/pedrobarbosaocb): he set up the initial swipe view, listing cards and the frontend/backend scaffolding; I built the scraping and LLM pipeline, filtering, hierarchical sorting, shortlist and the other aforementioned features on top of it.*

**LangBiasTester**: Experiment software I wrote from scratch for my honours thesis on auditory language biases in bilinguals. It mixes audio clips in varying proportions of two languages, collects participants' confidence ratings on what they heard, and generates counterbalanced trial sequences from individual templates.

### Earlier work

**[COVID data project](https://github.com/gabrloureiro/QCcovidDB)** · *Python (2020)*
My first project, written before university. The government of Quebec did not publish its COVID-19 data in a usable format, nor did they provide any visualisations to better understand trends. Seeing this gap and feeling a need to better understand the severity of the situation, I built this project to extract the case and death data from their website and to plot it in order to follow trends.

</details>

### Get in touch

[Email](loureirogabr@gmail.com) · [LinkedIn](https://www.linkedin.com/in/gab-loureiro-7a6115204?utm_source=share_via&utm_content=profile)
