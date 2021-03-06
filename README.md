KnowTree
========

(Name [undecided](#naming))

# About

Similar to a [technology tree in video games](https://en.wikipedia.org/wiki/Technology_tree) but for learning stuff in real life. Essentially a dependency graph for learning.

The closest thing to this is, in some sense, Wikipedia. But it's meant to be a reference, [not a directory](https://en.wikipedia.org/wiki/Wikipedia:What_Wikipedia_is_not#Wikipedia_is_not_a_directory) and [not a textbook](https://en.wikipedia.org/wiki/Wikipedia:What_Wikipedia_is_not#Wikipedia_is_not_a_manual.2C_guidebook.2C_textbook.2C_or_scientific_journal).

It is essentially a new type of generation [Learning Management System](https://en.wikipedia.org/wiki/Learning_management_system) which is a lot more personal and of personal value.

Perhaps a better analogy would be a fancy digital [learning log](https://en.wikipedia.org/wiki/Learning_log) where everything you've learned it immortalized. This would be used for analysis of what you know (based on what you have learned), what you don't, how you could learn something (links to rated resources) and make a lesson plan to learn anything (by mapping out learning prerequisites). It could also be used for simply keeping track of what you know and what you've learned, a good start. An activity graph would be a powerful tool to motivate the user.

# Background

When I was in high school, a new form of education arose on the internet, namely MOOCs and sites such as Khan Academy.

I spend a considerable amount of time on Udacity, Khan Academy and Coursera during my third year of high school and I think I learned more that year than any other thanks to these services.
I thought the MOOC revolution was going to take off, and it did to some degree, but it's potential is still very much underappreciated.

When I realized how effective online courses were for me to learn, I thought that conventional schooling had its days numbered. 
That does not longer seem to be the case, but I still think it should be to a large degree. KnowTree will hopefully lead to people realizing that they aren't getting the best education offline, they could be getting something even better online.

[Peter Thiel seems to agree](https://www.youtube.com/watch?v=rzdiWDw4teo&t=328s)

I even found an old `.txt` file I had written in January 2012 about the "home of knowledge" which was an idea for a platform where learning resources could be shared and voted on in a reddit-like fashion.

## Examples

**Example 1:** [This article](http://manishearth.github.io/blog/2017/03/04/what-are-sum-product-and-pi-types/) explains sum, product and pi types. It requires knowledge of structs and enums, optionally requires basic set theory. It provides (basic knowledge of)/(intuition to) sum, product and pi types. If a learner wants to learn sum, product and pi types. They would have to have learned structs and enums before. Once they read the article, they could mark sum, product and pi types as learned (or a lighter version such as "basic understanding") in their tree, and even get informed about what "next steps" would be.

**Example 2:** The entirety of Khan Academy could be put in such a learning tree. They already have a [basic one](https://www.khanacademy.org/exercisedashboard) of their own, although quite dated (designwise) and messy.


## Value proposition

 - Enables you to keep track of what you know and don't know.
   - Likely motivating for the learner to have an overview.
   - Makes it easy to find the gaps.
   - Enables a simple way of letting others know what you know. Useful in resumes.
 - The learner would be provided with an overview of what they can do with the things they have learned.
   - A kind of reversal of prerequisites.
   - Example: Someone has just learned the basics of programming, they would be shown what they can do/learn with what knowledge. Such as app/web/game dev, AI, robotics, CS theory.
 - Freedom of learning *what you want* while still learning *what you need*.
   - The learner can themselves choose which path they want to take while still getting some indication of which paths are reasonable/practical and lead to the desired goal.
   - There might still be user-created "tracks"/curricula,
     - Could also be generated from user data.
 - Optimizing the learning process.
   - Learn faster by getting to know what you don't know.
   - Learn faster by getting recommendations for the best learning resource 
     - Which the best resource is could vary from person to person.
 - Planning out what you need to learn in order to reach some goal. 
   - [CLARIFY] If someone wants to learn X, they would be presented with a variety of options to do so. The work of figuring out how and where is just a matter of choosing between the presented options.
   - [CLARIFY] Learn the concepts you want to learn, and get help with what you need to to get there.


## Naming

Alternative names:

 - TreeLearn
 - LearnerTree
 - Graph-equivalents
   - LearnerGraph
   - LearningGraph (two g's in a row is probably bad)
   - LearniGraph (gets rid of the two g's issue)
 - Tree of Knowledge (or some variation thereof)
   - I've bought the domain names knowledgetree.io and knowtree.io


# Is there something similar?

I've made some basic searches, nothing found. But more extensive searching would be in order.

**Update 1:** Turns out [Nikita Voloboev](https://github.com/nikitavoloboev), [who's mindmap repo I've found before](https://github.com/nikitavoloboev/knowledge-map) is "Building a visual search engine and mind maps to organise world's knowledge with a study plan for learning anything" (his GitHub profile description 2017-04-16). Looks like he's taking a different approach, but has likely thought a lot about stuff related to this. I've reached out to him.

**Update 2:** Nikita gave some really good feedback, will integrate later.

Also, [Arbital](https://arbital.com/) is an example of a wiki with some fresh ideas.

**Update 3:** Googled around, [found this (Swedish)](https://magisterfalk.wordpress.com/tag/kunskapstrad/) which was interesting. Another datapoint to the claim that there's no such thing as a new idea. I should gather info from that blogger.

**Update 4:** Got a Twitter ad for Pluralsight, apparently a long-time player in the technology learning market. They seem to have some sort of progress system but I've yet to try it. Should probably sign up for a trial and check it out.

[Someone on HN posted a lecture search engine](https://news.ycombinator.com/item?id=14484549). Interesting stuff for sure, highly relevant (but we might want to go for curated/contributor style adding of learning resources instead of crawling the web to start with, leads to higher quality information, but that could also be solved with ratings).

Also found [Learnodoro](learnodoro.com) ([The creators Twitter](https://twitter.com/learnodoro)). Not entirely sure what the angle is but seems like he is planning some kind of progress system as well.

**Update 5:** Just re-discovered https://openbadges.org/, seems like a good project that left a lot of the interesting parts untouched (no focus on personal tracking of progress, just on verifiable progress).

**Update 6:** I've been meaning to write an update for quite a while now. First of all I discovered Mek Karpeles project [Skillsera](https://github.com/Skillsera) so I reached out to him. He reminded me of the existence of [Metacademy](metacademy.org) which I've completely forgotten about. Mek also invited me to a Slack for the [ArchiveLab](https://experiments.archivelab.org/) at the Internet Archive. Apparently people there have a shared interest in this kind of stuff.

**Update 7:** [@hajak](https://twitter.com/hajak) found [@wynlim](https://www.patreon.com/wynlim) and linked to me. She's working on a ["self-directed learning network"](https://medium.com/the-experimental-year/designing-a-self-directed-learning-network-v0-3-8a8a990d0bfe), really cool stuff.

**Update 8:** When I started writing this article I found out about [Kristin and her Knowmap project](https://github.com/ksteph/KnowMap). I should probably reach out.


So, in summary:

 - Metacademy
 - Pluralsight (commercial)
 - Khan Academy (exclusive content, therefore limited in scope)


# Implementation

It would probably be best implemented as a webapp.

The real question is how to do it in a way that minimizes the complexity of the backend and frontend so that we can iterate quickly.

Perhaps the graph itself could be represented with Neo4j? (Edit: Likely overkill, relational database will probably be enough to start off with)

How to classify learning resources in some automatized way? Doesn't have to be overly advanced, just have to be decent. ([Example](https://news.ycombinator.com/item?id=14337275))

**Update 1:** I've started some basic work on a prototype. Not much yet.

## Datastructure

The database will contain something similar to these types of objects:

 - Field/body of knowledge (category)
   - Mathematics, Physics, Computer Science, etc.
   - Essentially serves as categories for more granular pieces of knowledge.
   - Wikipedia already does categorization like this well and can be retrieved from the [dumps](https://stackoverflow.com/questions/17432254/wikipedia-category-hierarchy-from-dumps).
   - The topics would be linkable to Wikipedia articles as well, making categorization easier.
   - **Unclear why this would be qualitatively different from a larger topic/concept.**
 - Topics/Concepts (goals?)
   - Can belong to one or more fields of knowledge.
   - ~~Essentially what you want to learn.~~ Things you can learn about.
   - [This PDF](https://worldview.unc.edu/files/2013/07/Getting-the-Big-Idea-Handout.pdf) contains some information about the "concept-topic divide".
   - Nodes of this type have relations to each other.
     - Required prerequisites and recommended/optional prerequisites. 
     - **This is what builds the arguably most important part of the graph.**
 - Learning resources (resource)
   - Can supply knowledge about one or more topics/concepts.
   - Examples:
     - Reading/watching materials (no interaction)
       - Articles
       - Books
       - Videos
     - Exercises (interaction)
       - Khan Academy
     - Courses (planned paths)
       - MOOCs
       - Brick-and-mortar University courses
     - Flashcards?
     - Projects?
       - Could also be learning goals.
 - Verification/Accreditation
   - The problem: People would want to prove their ability. 
   - Solution: There are a lot of existing ways to do this (tests, courses) 
     so the easiest thing to do is just to let them handle it (i.e. users can claim verification is available, that they would need to be able to show if asked to do so).


# Visualization

Visualization of the graph would likely be best done with D3. 

The [D3.js gallery](https://github.com/d3/d3/wiki/Gallery) has great examples. We could probably get a lot of good ideas from some of them.

**Update 1:** I've started attempts at prototyping the structure of such a tree using [Gephi](https://gephi.org/).

**Update 2:** Gephi wasn't the right tool for the job, yEd was a lot better (but not open source). I found [this neat collapsible tree demo](http://live.yworks.com/yfiles-for-html/2.0/complete/collapse/index.html) on their website, the balloon style was really nice.

**Update 3:** Is graph-style visualization of the graph really important? It might be good if it can instill a sense of overview/progress but otherwise we should perhaps be sceptical. Facebook initially also planned to visualize a graph for you, but they dropped out. Probably due to business reasons, but might it be due to something else I fail to account for?

# Issues

There might be plenty of things making the idea in need of modification or entirely unfeasible/impractical, those things go here.

 - Looking for feedback currently, expect more here in the future. 
   - **Update:** I've reached out to a handful of friends for feedback, most of it overwhelmingly positive. I've created a [new section for feedback](#feedback).
 - Too simplistic? Can we really reduce knowledge to a tree/graph in a useful way?
 - Knowledge about a topic usually has levels (basic, intermediate, advanced, expert), these would be hard to structure in the graph.
   - We should probably focus on basics/intermediate knowledge first anyway, so might not be that big of an issue initially.
 - Monetization: Is there any good way to monetizing it without sacrificing maximum value provided?
   - Donations work, but have their own problems.
   - Offering a premium service of some sorts?
     - Enterprise?
       - Support for closed ecosystems?
     - Pro users? *(I just went through and s/user/learner'd the whole document, I laughed when I realized this would become Pro learner)*
 - Internationalization
   - Learning resources are usually specific to a certain language, some are translated however. 
   - We'd need to track which languages a resource is available in if we want to scale beyond an English-speaking audience.


# Feedback

The only feedback I've gotten so far has been extremely positive, still looking for more constructive feedback/ways to improve/potential issues.


# Questions

 - Is the tree actually a tree? Might it actually be a graph?
   - It will at least be a directed acyclic graph (I hope, otherwise it'd be messy)
 - Might a tree/graph like this be useful in training/building AI?


# Additions v2 (2018-09-04)

A more approachable version of the project, with the same end goal.


 - A system where knowledge is packaged into flashcard-like pieces of knowledge.
 - It can be a word in another language, an acronym, a mathematical formula, a random factoid you saw in a blog post,
 - These pieces of knowledge which can be tagged, collected in categories, and have references to articles.


### The basic UI

The UI would first present categories or subjects that one could learn, when a subject is clicked, an ability test begins to gather approximate information about the users abilities. This consists of quizzing the user to estimate their proficiency.

When a fact is shown, it can appear either:

 - Explicitly, simply stating the fact.
 - As a quiz that tests the knowledge.

When the user has acknowledged the information, or answered/skipped the question, the user can take a few actions:

 - Answer correctly: the user received a positive reinforcement for correctly answering.
 - Answer incorrectly: the correct answer is shown.
 - Dismiss card/mark uninterest ("I don't care about this")

Once the answer is given:

 - A "review" checkbox appears
   - We might also want to indicate how "easy" this was, to automatically adjust the difficulty of future questions in a field.
 - A dismiss button appears.
 - Default would be to review at some future date (could be set either automatically or manually).

All facts correctly answered should be added as a healthy leaf to ones tree of knowledge, it could yellows if it becomes old (hasn't been reviewed), and just be a sprout if never correctly answered.


