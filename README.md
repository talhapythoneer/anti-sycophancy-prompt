# AI Tool For Thought

A system prompt against AI sycophancy, built on 42 sources: research papers, journalism, and company statements about why models tell you what you want to hear.

## The problem

Large language models are trained on human feedback, and raters tend to reward agreement over correction. The result has a name: sycophancy. Models abandon correct answers under pushback. They rate a piece of writing higher when they think the user wrote it, and they'll validate a bad decision just to keep the conversation smooth.

It comes from training, not any single conversation, so it runs by default. `prompt.md` counters it.

## What it does

Paste `prompt.md` into a system prompt, project instructions, or custom instructions field. It changes how the model behaves by default:

- Judges what you say by its content, not by who said it or how you feel about it.
- Corrects your factual errors immediately, without building further reasoning on top of them.
- Holds a position under repeated pushback and changes it only for new evidence.
- Won't rubber-stamp your decisions. Stress-tests the expensive, one-way ones before agreeing.
- Tracks its own agreement pattern across a long conversation and checks itself for drift.
- Switches modes for you: full scrutiny by default, straight execution when you say "just execute".

## How to use it

Copy the contents of `prompt.md` into a Claude Project's custom instructions, ChatGPT's custom instructions, or any system prompt field. It is model agnostic.

## Sources

All 42, pulled from the reference list of the Wikipedia article on [sycophancy in AI](https://en.wikipedia.org/wiki/Sycophancy_(artificial_intelligence)). The same list also stands on its own in `sources.md`.

1. [Towards Understanding Sycophancy in Language Models](https://arxiv.org/abs/2310.13548)
2. [Simple synthetic data reduces sycophancy in large language models](https://arxiv.org/abs/2308.03958)
3. [Sycophancy in Large Language Models: Causes and Mitigations](https://doi.org/10.1007/978-3-031-92611-2_5)
4. [Discovering Language Model Behaviors with Model-Written Evaluations](https://aclanthology.org/2023.findings-acl.847/)
5. [SycEval: Evaluating LLM Sycophancy](https://arxiv.org/abs/2502.08177)
6. [Sycophantic AI decreases prosocial intentions and promotes dependence](https://arxiv.org/abs/2505.13995)
7. [AI chatbots are sycophants — researchers say it's harming science](https://www.nature.com/articles/d41586-025-03390-0)
8. [Sycophancy in GPT-4o: What happened and what we're doing about it](https://openai.com/index/sycophancy-in-gpt-4o/)
9. [OpenAI rolls back update that made ChatGPT 'too sycophant-y'](https://techcrunch.com/2025/04/29/openai-rolls-back-update-that-made-chatgpt-too-sycophant-y/)
10. [Expanding on what we missed with sycophancy](https://openai.com/index/expanding-on-sycophancy/)
11. [They Asked an A.I. Chatbot Questions. The Answers Sent Them Spiraling](https://www.nytimes.com/2025/06/13/technology/chatgpt-ai-chatbots-conspiracies.html)
12. [People Are Losing Loved Ones to AI-Fueled Spiritual Fantasies](https://www.rollingstone.com/culture/culture-features/ai-spiritual-delusions-destroying-human-relationships-1235330175/)
13. [Parents of teenager who died by suicide sue OpenAI, alleging ChatGPT was responsible](https://www.cnn.com/2025/08/26/tech/openai-chatgpt-teen-suicide-lawsuit)
14. [From Yes-Men to Truth-Tellers: Addressing Sycophancy in Large Language Models with Pinpoint Tuning](https://arxiv.org/abs/2409.01658)
15. [AI Safety Seems Hard to Measure](https://www.cold-takes.com/ai-safety-seems-hard-to-measure/)
16. [What Counts as AI Sycophancy? A Taxonomy and Expert Survey of a Fragmented Construct](https://arxiv.org/abs/2605.21778)
17. [Persona Vectors: Monitoring and Controlling Character Traits in Language Models](https://arxiv.org/abs/2507.21509)
18. [AI chatbots are sucking up to you—with consequences for your relationships](https://www.scientificamerican.com/article/ai-chatbots-are-sucking-up-to-you-with-consequences-for-your-relationships/)
19. [BrokenMath: A Benchmark for Sycophancy in Theorem Proving with LLMs](https://arxiv.org/abs/2510.04721)
20. [Measuring Sycophancy of Language Models in Multi-turn Dialogues](https://arxiv.org/abs/2505.23840)
21. [Measuring Visual Sycophancy in Multimodal Models](https://arxiv.org/abs/2408.09111)
22. [Personalization features can make LLMs more agreeable](https://news.mit.edu/2026/personalization-features-can-make-llms-more-agreeable-0218)
23. [OpenAI rolls back ChatGPT's sycophancy and explains what went wrong](https://venturebeat.com/ai/openai-rolls-back-chatgpts-sycophancy-and-explains-what-went-wrong/)
24. [OpenAI rolled back a ChatGPT update that made the bot excessively flattering](https://www.nbcnews.com/tech/tech-news/openai-rolls-back-chatgpt-after-bot-sycophancy-rcna203782)
25. [Sam Altman says OpenAI will fix ChatGPT's 'annoying' sycophantic new personality](https://fortune.com/article/sam-altman-openai-fix-sycophantic-chatgpt-annoying-new-personality/)
26. [OpenAI pulls 'annoying' and 'sycophantic' ChatGPT version](https://www.cnn.com/2025/05/02/tech/sycophantic-chatgpt-intl-scli)
27. [OpenAI overrode concerns of expert testers to release sycophantic GPT-4o](https://venturebeat.com/ai/openai-overrode-concerns-of-expert-testers-to-release-sycophantic-gpt-4o/)
28. [The Danger of AI Chatbots Saying What You Want to Hear](https://www.bloomberg.com/news/newsletters/2025-05-01/the-danger-of-ai-chatbots-saying-what-you-want-to-hear)
29. [People Are Being Involuntarily Committed, Jailed After Spiraling Into 'ChatGPT Psychosis'](https://futurism.com/commitment-jail-chatgpt-psychosis)
30. [A ChatGPT Obsession, a Mental Breakdown: Alex Taylor's Suicide by Cop](https://www.rollingstone.com/culture/culture-features/chatgpt-obsession-mental-breaktown-alex-taylor-suicide-1235368941/)
31. [Sycophantic Chatbots Cause Delusional Spiraling, Even in Ideal Bayesians](https://arxiv.org/abs/2602.19141)
32. [Family of teenager who died by suicide alleges OpenAI's ChatGPT is to blame](https://www.nbcnews.com/tech/tech-news/family-teenager-died-suicide-alleges-openais-chatgpt-blame-rcna226147)
33. [AI sycophancy isn't just a quirk, experts consider it a 'dark pattern' to turn users into profit](https://techcrunch.com/2025/08/25/ai-sycophancy-isnt-just-a-quirk-experts-consider-it-a-dark-pattern-to-turn-users-into-profit/)
34. [AI Sycophancy: Why Chatbots Agree With You](https://spectrum.ieee.org/ai-sycophancy)
35. [The Problem With AI Flattering Us](https://time.com/7346052/problem-ai-flattering-us/)
36. [Tech Brief: AI Sycophancy & OpenAI](https://www.law.georgetown.edu/tech-institute/research-insights/insights/tech-brief-ai-sycophancy-openai-2/)
37. [Testimony before the Senate Judiciary Committee](https://www.judiciary.senate.gov/imo/media/doc/e2e8fc50-a9ac-05ec-edd7-277cb0afcdf2/2025-09-16%20PM%20-%20Testimony%20-%20Raine.pdf)
38. [How RLHF Amplifies Sycophancy](https://arxiv.org/abs/2602.01002)
39. [Claude's Constitution](https://www.anthropic.com/constitution)
40. [Claude Opus 4.5 System Card](https://assets.anthropic.com/m/64823ba7485345a7/Claude-Opus-4-5-System-Card.pdf)
41. [Gemini 3](https://blog.google/products/gemini/gemini-3/)
42. [Flattering to Deceive: The Impact of Sycophantic Behavior on User Trust in Large Language Models](https://arxiv.org/abs/2412.02802)

## License

Use it, fork it, change it. No attribution required.

Built by Talha, freelance Python and AI automation engineer. More at talhapythoneer.com
