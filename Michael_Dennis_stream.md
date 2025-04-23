## What’s your motivation for applying to this stream and project? (max 100 words)

I am very interested in reinforcement learning and in learning in general conceptually. I am also very interested in applications of rl and ml to real world problems: I think robotics and other physical agents are things of the huge impact and potential applications. I would be interested in improving the learning protocols/algorithms to get better in solving relevant problems of real world agents, especially in the topic of reward design (for example, in the style of formulation of a problem as in the 'BAMDP Shaping' or 'CIRL' articles), where better reward structures can reduce misalignment or unintended behavior in real-world agents. 

## What do you want to work on? Please give a 3-5 paragraph pitch for your research idea that fits this stream.

**Research Proposal**
I’ve read (parts of) “BAMDP Shaping: A Unified Framework for Intrinsic Motivation and Reward Shaping”, and I find the core idea of identifying general conditions under which rewards can’t be hacked to be a fascinating and important direction. However, the paper’s use of potential functions over “history” (as opposed to trajectories) seems underspecified and practically challenging. If “history” refers to the full sequence of past states and actions, computing such potentials becomes intractable in real-world environments due to challenges in computations over such high dimensional space in practice. That said, I strongly agree with the meta-level motivation: we could and should use agent's collected experience in much more structured and efficient ways.

I’d be interested in exploring this issue further: starting with toy settings to investigate compressed or approximate representations of history that could serve as viable shaping functions, while still preventing reward hacking. The goal would be to make theoretically grounded ideas from BAMDP Shaping more usable in practice.

More broadly, I’m also very interested in meta-RL directions, such as learning how to learn, inverse reward learning (as in CIRL), or environment design (like Emergent Complexity and Zero-shot Transfer via Unsupervised Environment Design), especially when grounded in practical agent behavior.

## Explain your strongest disagreement with other alignment thinkers. Consider only your own inside-view understanding, and don't defer to others' expertise.

I don’t have strong exposure to all alignment research directions, but from EAG discussions, I’ve noticed a heavy emphasis on mechanistic interpretability. While I appreciate its theoretical appeal, I don’t think it scales well to more large and powerful models, and in many cases, I think it’s unlikely to be the bottleneck in practical safety. I’m much more drawn to applied directions like red-teaming, robustness, and agent control protocols that can be tested and deployed.

I also think the field spends too much time worrying about hypothetical future risks while underestimating alignment challenges in current or near-future systems, especially in physical domains like robotics, biotech (e.g., AlphaFold-style applications and beyond), or scientific ML. These systems can cause harm long before full AGI appears, and I’d like to see more alignment work grounded in those realities.  


## What are your chances of being interested in continuing to work together beyond the 2-month MATS program? E.g. Extending for another 2 months until the project runs to completion. Include a %, with some explanation of your number as needed.

80% - Would be very interested to continue working on the project assuming the project goes well and there is a potential for good output/results. 



