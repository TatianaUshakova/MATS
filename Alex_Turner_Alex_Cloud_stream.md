## Explain your strongest disagreement with other alignment thinkers. Consider only your own inside-view understanding, and don't defer to others' expertise.

I am not as familiar with main stream views of alignment thinkers. From small amount of things I saw, I dont think a lot of current approaches to mechanical interpretability are scalable enough to produce the results when models get bigger. (This is actually the reason while I was really fascinated by the gradient routing paper, this does offer the scalable alternative - it should be much easier to create the needed structure that to interpret the existing -and quite complex - one). 


## Propose a follow-up experiment to section 4.2 of the gradient routing paper ([https://arxiv.org/abs/2410.04332](https://arxiv.org/abs/2410.04332)) and explain the relevance of the experiment to AI safety efforts. (Suggested length: ~250 words for experiment, 1-4 sentences for relevance.)

I think the main challenges given the achievements in the articles are (1) creating stable routing for mostly unlabeled data: it should be impossible to label every unsafe content to delete it; and (2) resolution between close concepts and selective deletion: we want the model to not know how to make a bomb (lets say requiting some chemical element), but we want it to know what is
the bomb and what is the definiton of this chemical element. Several things to try to achieve this

resolution between close concepts and selective deletion
1. More strict separation of the concept: If we mask the california specific layer and detach it from learning on non-california labeled data, would the delition of this layer produce less increase of the loss on non-california data
2. Resolution between close concepts: have the separate layers for routing for notion california and for notion state and see if its possible to separate them in a way that delition of only state-layers do not produce the loss increase in california only related tasks. Alternatively, trying to allocate specific layer corresponding to one and another concept and their overlap: have a dataset for tales involving cakes, texts of kitchen tools and texts of cakes recepies and routing them in layers for cakes, tools and their overlap; see if delition of only overlap makes model to forget the recepies of cakes, but doesnt produce significant increase in loss in other types of data

Robust routing for mostly unlabeled data: 
1. If the layer separation performed by routing by training on some amount of labeled data, for how long after that the separation will be preserved during next training with no routing? (hypothesis: concepts lets say related to california will continue to be localized in selected layers but decreasing with some dissipation rate) If the rate is slow enough or the separation can be restored by periodical intermediate fine tuning with labeled routing between unlabeled general training, it would be possible to generalize the scheme to scale for mostly unlabeled scenarious of large datasets. 

Other things interesting to try:
1. From intuition with golden gate claude, its possible to localize the metaconcepts like depressive style of writing, is it possible to localize the lie/creating vulnerable code, baises towards some groups of people and so on? Experimental protocol the same as in the article but with labels corresponding to metaconcepts instead of 'california'

## Briefly describe your most relevant skills and experience other than AI research (e.g. software engineering, other research, teamwork, writing, or anything else) (max 250 words).

Physics research - astrophysics and quantum field theory/high energy physics: advanced math, dealing with complex problems, research, understanding of statistical methods and so on. 
Python experience: was involved in work with python-based simulations during my astrophysics research, and took machine learning/data science classes. 

## Are you open to working in a small team? We plan to prioritize people that answer “yes” to this question, although it is not a strict requirement.

Yes and actually would prefer that


## If you’re open to working in a team, briefly reflect on how you might make this go well. What would a great collaboration look like to you? In your answer, you might draw on prior experience in teams, but you don’t have to. (max 250 words).

Great collaboration for me is working on the same or similar problems in the close contact and share the progress/ideas/things that worked and didnt, and tackle the challenges together.  To make the collaboration go well I would try to understand what are the things that other parts of the team are stuck in where I can offer the help in some ways.  


## If accepted, would you participate in the program full-time, in person in Berkeley (Jun 16 - Aug 22)? If you’re not sure, please explain. We are happy to accept people who have other commitments, as long as MATS would be their primary focus.

Yes



## If the project is going well, and you receive funding to continue your work afterward, do you expect to choose to participate in the MATS extension (between 6 and 12 months after the main program)? This could be remote. It’s okay if you aren’t sure if you’ll be available for the entire period.

Yes (though I cant predict entirely my future availability, but I am interested in continue working on promising project)


## Is there anything else we should know? (If the rest of your application speaks for itself, feel free to leave this blank.)










