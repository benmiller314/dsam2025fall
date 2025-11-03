
# Week 11: Machines + Learning
<span class="date">November 3, 2025</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul class="spaced">
            <li>"Computer Scientist Explains Machine Learning in 5 Levels of Difficulty." _WIRED_, YouTube, 18 Aug 2021. <a href="https://www.youtube.com/watch?v=5q87K1WaoFI">https://www.youtube.com/watch?v=5q87K1WaoFI</a>.</li>
            <li>Newhauser, Mary. “What Is Generative AI? A Comprehensive Guide for Everyone.” GPTech, 26 June 2023, <a href="https://www.gptechblog.com/what-is-generative-ai-comprehensive-guide-beginners">https://www.gptechblog.com/</a>.</li>
            <li>Bycroft, Brendan. LLM Visualization. <a href="https://bbycroft.net/llm">https://bbycroft.net/llm</a>. Accessed 29 July 2025.</li>
            <li>Roberts, Sarah T. “Your AI Is a Human.” <em>Your Computer Is On Fire</em>, edited by Thomas S. Mullaney, Benjamin Peters, Mar Hicks, and Kavita Philip, MIT Press, 2021, pp. 61–83. ProQuest Ebook Central, <a href="http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6479710">http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6479710</a>.</li>
            <li>Pengfei Li, Jianyi Yang, Mohammad A Islam, and Shaolei Ren. “Making AI Less ‘Thirsty’.” <em>Communications of the ACM</em>, vol. 68, no. 7, June 2025, pp. 54–61, <a href="https://doi.org/10.1145/3724499">https://doi.org/10.1145/3724499</a>.</li>
            <li>Onuoha, Mimi and Mother Cyborg (Diana Nucera). “A People’s Guide To Tech: Artificial Intelligence.” Allied Media Projects, Aug 2018, <a href="https://alliedmedia.org/resources/peoples-guide-to-ai">https://alliedmedia.org/resources/peoples-guide-to-ai</a>.</li>
            <li>Shane, Janelle. “An Exercise in Frustration.” AI Weirdness, 21 May 2024, <a href="https://www.aiweirdness.com/an-exercise-in-frustration/">https://www.aiweirdness.com/an-exercise-in-frustration/</a>.</li>
            <li>Shane, Janelle. “When Algorithms Surprise Us.” AI Weirdness, 13 Apr 2018, <a href="https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/">https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/</a>.</li>
        </ul>
        <details><summary>EXT for eager learners:</summary>
            <ul>
                <li>Crawford, Kate, and Trevor Paglen. “Excavating AI: The Politics of Training Sets for Machine Learning.” 19 Sep 2019, <a href="https://excavating.ai">https://excavating.ai</a>.</li>
                <li>Thompson, Tiffany, Stuart A. Hsu, and Steven Lee Myers. “OpenAI’s Sora Makes Disinformation Extremely Easy and Extremely Real.” <em>The New York Times</em>, 3 Oct. 2025. NYTimes.com, <a href="https://www.nytimes.com/2025/10/03/technology/sora-openai-video-disinformation.html">https://www.nytimes.com/2025/10/03/technology/sora-openai-video-disinformation.html</a>.</li>
                <li>Isaac, Mike, and Eli Tan. “OpenAI’s New Video App Is Jaw-Dropping (for Better and Worse).” <em>The New York Times</em>, 2 Oct. 2025. NYTimes.com, <a href="https://www.nytimes.com/2025/10/02/technology/openai-sora-video-app.html">https://www.nytimes.com/2025/10/02/technology/openai-sora-video-app.html</a>.</li>
                <li>Vara, Vauhini. “Ghosts.” <em>Believer Magazine</em>, 9 Aug. 2021, <a href="https://www.thebeliever.net/ghosts/">https://www.thebeliever.net/ghosts/</a>.</li>
            </ul>
        </details>
    </details>
    <details><summary><strong>Writing to have done</strong></summary>
        <ul>
            <li>Posts to the <a href="{{site.repo_url}}/discussions">discussion forum</a> in response to the readings, led by John, Rose, Tunga, Scylla, and Yuqing.</li>
        </ul>
    </details>
</section>


## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Warm-up writing (~5 min)
    - Guest lecture: Alison Langmead on synthetic image generators (~30 min)
    - Takeaways, tensions, questions, connections
    - Writing to remember (around 10:20)
* Break (10 min)
* [Second half](#second-half): Let's practice!
    - genAI exercise: evaluating "right output"
    - EXTs / Studio time
* [Homework for next time](#hw)
    - Exploration + Inspiration
    - Looking ahead


## First half: Discussion {#first-half}

### Warm-up writing

1. Call to mind this week's readings, videos, and interactives, which were kind of tilted toward explanation. Make a quick list of **core ideas or takeaways** that have stuck with you. Your list does not have to be complete! Just make sure you have at least a 2-4 ideas to work with. Take about 1-2 minutes here.

2. Once you have at least a few items, _choose one_ and consider: if you had to **represent that idea as an image or diagram**, what would it look like? You can make a quick sketch or two, if you like, or just write notes about what such an image would need to include. Again, take only a minute or two: quick ideas to remind you. We'll come back to this later.


### Guest lecture: Alison on synthetic image generators

We are lucky to have someone who's thought a lot about generative AI, where it's been, where it's going, where it could be of interest to the humanities and the arts. I'm excited to yield the floor and listen for a bit!



### Let's talk!

If we get to grok-writing by around 10:15, that should give us about equal time to dig into ideas now and then to dig into process in the second half.

As usual, it would be great if we could take some collaborative notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes).

Some possible passages for consideration / moments to revisit, if needed
<ul class="spaced">
    <!-- <li><details><summary>The visibility paradox from another angle</summary>
        <blockquote>On one hand, removing these problematic datasets from the internet may seem like a victory. The most obvious privacy and ethical violations are addressed by making them no longer accessible. However, taking them offline doesn’t stop their work in the world: these training sets have been downloaded countless times, and have made their way into many production AI systems and academic papers. By erasing them completely, not only is a significant part of the history of AI lost, but researchers are unable to see how the assumptions, labels, and classificatory approaches have been replicated in new systems, or trace the provenance of skews and biases exhibited in working systems. (Crawford and Paglen)</blockquote>
        <p></p>
        </details>
    </li> -->
    <li><details><summary>Holding space for hope in the face of large but vague or distant problems</summary>
        <p>Scylla points us to the estimates of AI's water usage in Li et al's article on the subject, noting that "the combined scope-1 [direct use] and scope-2 [energy provision] water withdrawal of global AI is projected to reach 4.2-6.6 billion cubic meters in 2027, more than the total annual water withdrawal of four to six Denmarks or half the U.K." (While most of that is incurred during training, processing queries also consumes significant amounts of water.) Scylla continues:</p>
        <blockquote>I appreciate this article's breaking down of the "how" one can arrive at figures like this, because they're so difficult to fathom, and I appreciate that the authors provided recommendations on addressing the "water footprint" of AI. A general question this piece and topic area brings for me, though, is what do folks cling onto to not give into the existential dread of massive, abstract problems like this?</blockquote>
    </details></li>
    <li><details><summary>How to research systems that have been intentionally concealed</summary>
        <p>Tunga draws on a passage in Roberts' chapter on the human labor involved in maintaining AI systems: <blockquote>[Social Media] are a dynamic assemblage of functionality, relationship creation and maintenance, policies, and governance that are always in flux and seldom visible in their totality to the user. They aggregate data, track behavior, determine, and even influence tastes and habits, capture attention, and package all of these things as commodities for advertisers. (69-70)</blockquote></p>
        <p>In Tunga's reading, <blockquote><p>when Roberts writes that social media “aggregate data, track behavior, determine, and even influence tastes and habits,” she reveals how users themselves are enfolded into this system of labor and commodification. The “dynamic assemblage” she describes isn’t only technological; it is social and economic, continually reorganized to maximize extraction of data, of attention, of emotion.</p>
        <p>What I find myself wondering is: if these platforms are always “in flux and seldom visible in their totality,” how can researchers begin to grasp the scope of their operations? What does it mean to study or critique something designed to remain opaque? Roberts’s argument leaves us with a difficult ethical question: when every act of participation fuels an economy of human and algorithmic labor, where do responsibility and complicity converge?</p></blockquote></p>

        <p>Tunga, you said you wanted to talk about art pieces from another course in connection to these questions...?</p>
    </details></li>
    <li><details><summary>Shortcuts and ill-defined problems (or not)</summary>
        <p>Another key idea and passage from Tunga, this time from Janelle Shane:</p> <blockquote>
            <blockquote>So as programmers we have to be very very careful that our algorithms are solving the problems that we meant for them to solve, not exploiting shortcuts. If there’s another, easier route toward solving a given problem, machine learning will likely find it.</blockquote>
            <p>Janelle Shane’s blog posts are deceptively lighthearted meditations on the mischief of machine learning. Through anecdotes of robots that learn to “walk” by collapsing dramatically, or image models that misinterpret simple prompts into absurd and grotesque results, she exposes the strange literalism of artificial intelligence. The humor of these stories (the falling robots, the invisible dinosaurs, the pies that replace deer!) makes them memorable, but beneath that humor lies a serious warning about design and interpretation. Shane’s world of failed experiments and unexpected outputs reminds us that algorithms do not think metaphorically or contextually; they optimize, blindly and brilliantly, toward whatever metric we hand them.</p>
            <p>I think these posts connect immediately to my reading of Roberts. What does it mean, then, to call these systems “intelligent.”? If they are capable only of optimizing our ambiguities, are they learning or simply reflecting the narrowness of our definitions? And if an algorithm always finds “an easier route,” what does that say about the human desire to mechanize creativity, efficiency, or even art? I find Shane’s playful tone disguises a deep ethical unease. Intelligence, stripped of interpretation, can still achieve its goal and yet utterly miss the point.</p>
        </blockquote>
        <p>I love that last line! And I saw it too late to write it up fully, but Rose, I think you had a relevant note here as well on interpretability...?</p>        
    </details>
    <li><details><summary>Data <em>about</em> vs. data that <em>serves</em></summary>
        <blockquote>
            <p>Undocumented people, immigrants, and people of color in lower-income spaces also tend to be over-surveilled. In other words, they’re more likely to have data and information collected about them without their consent, or they’re forced to give it up to get access to basic needs. For example, if you qualify for food stamps in the US, you know that you had to share a lot of information about yourself with the local government, whereas your wealthier neighbor likely hasn’t been forced to in the same way.</p>
            <p>This overcollection of data <em>about</em> some people and undercollection of data that <em>serves</em> those people results in a cycle of data violence that is passed on to these algorithms. (Onuoha and Mother Cyborg, 63–4)</p>
        </blockquote>
        </details>
    </li>   
    <!-- <li><details><summary>When the frustration is part of the point</summary>
        <blockquote>
            <p>If you were able to come up with a social algorithm that can determine who is interesting and fun in an equitable way... amazing! <strong>We suspect that you may have stopped at some point and questioned the activity.</strong> Maybe you thought that there was no good way of telling how fun or interesting someone is. Or maybe you considered that ideas of “fun” and “interesting” are contextual, and might be different for different people. Maybe you just designed an algorithm that would make it so you could attend the party!</p>
            <p>This activity is meant to show just how complex humans are and how attributes like “interesting” and “fun” are relative to whoever is designing the algorithm. (Onuoha and Mother Cyborg 41, emphasis added)</p>
        </blockquote>
        <p>What did you think of the writing exercises / thought experiments in the "People's Guide to Tech"? Did anyone try them out?</p>
        </details>
    </li> -->
    <!-- <li><details><summary>The revision question</summary>
        <p>In "An Exercise in Frustration," Janelle Shane documents the difficulty she had in getting the image generator DALL-E3 (via ChatGPT4) to revise according to her instructions. Given what you've read/seen about how these models are trained, do you think a model with a text-based output would have the same difficulty with revising? Why or why not? Would it be frustrating in the same way? Why or why not?</p>
        </details>
    </li> -->
</ol>


### Writing to remember

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, I'll ask everyone to share one thing, to which we'll all say, simply, "thank you."


## Break (10 minutes)
Assuming we left off at 10:30, let's aim to start up again at 10:40 or so. That should beat the elevator rush for 11am classes.


<a id="second-half"></a>
## Second half: Let's practice

### How to judge an AI's output?

Remember that warm-up writing from the beginning of class? Take it out again now.

<ol start="3" class="spaced">
    <li>If you haven't yet done so, <strong>write a prompt that you hope would get an AI to generate your image.</strong> (If you really want to switch images, you could generate something else instead. Just make sure it's something you can easily imagine.)</li>

    <li>With your prompt set, write out what you are imagining more fully. Picture it in your mind's eye, coming to as full of an understanding as you can. <strong>Write <em>ekphrastically</em></strong>, moving your "mind's eye" across the image to describe and write out what you're imagining.

        <details><summary>Examples of ekphrasis</summary>
            <p>NB: You're under no obligation to write poetry, but it's where my mind goes.</p>
            <ol>
                <li><a href="https://www.poetryfoundation.org/poetrymagazine/poems/42378/edward-hopper-study-hotel-room">"Edward Hopper Study: Hotel Room" by Victoria Chang</a></li>
                <li><a href="https://www.poetryfoundation.org/poems/1679348/archaic-torso-of-apollo">"Archaic Torso of Apollo" by Rainer Maria Rilke</a></li>
            </ol>
        </details>
    </li>

    <li>Use your Pitt credentials to log into <a href="https://gemini.google.com/u/0/">Google Gemini</a>, one of the <a href="https://www.digital.pitt.edu/ai">genAI clients Pitt has an agreement with</a>. (If you want to compare, then yes, you can use any other image-generating AI tool you have at your disposal.)</li>

    <li>Enter the prompt into Gemini, and see what it gives you.</li>
</ol>

**Reflect:** How does your experience of seeing the visualization of this embedding compare to what you were imagining?

Let's discuss!

### EXT: Generative Image Revision

Give the AI instructions on how to improve the image. Are you more successful now than Janelle Shane was in May 2024?


### EXT: Studio

Finished with all the above? **Use the remaining time to move your project forward... or get started on the homework.**

<section id="markov">
<details><summary>EXT Bonus activity for thinking about how models are trained: simple Markov chains (kinda long)</summary>

    <p>When we say that an AI model "learns" to predict future texts from past texts, what do we mean? In this exercise, we'll construct a rough approximation of the process by building generative algorithms from short phrases with recurring bits of language.</p>

    <p>Credit for this exercise goes to <a href="https://wac.colostate.edu/repository/collections/textgened/ai-literacy/understanding-markov-chains/">Gabriel Egan</a> (writing in the pedagogy collection <a href="https://wac.colostate.edu/repository/collections/textgened/"><em>TextGenEd</em></a>), who in turn draws on Douglas Hofstadter's <a href="https://en.wikipedia.org/wiki/G%C3%B6del,_Escher,_Bach"><em>Gödel, Escher, Bach</em></a>.</p>

    <h4>Part 1: an offline algorithm as a flow chart for producing text</h4>

    <p>First we have to know what we're trying to make. Check out this <a href="https://docs.google.com/presentation/d/1vosRqj2kAJIqbExYkqxh80yE6x1p4if13w3wWTwRSPE/edit?usp=sharing">brief slide deck on Recursive Transition Networks</a>.</p>

    <ol class="lalpha">
        <li>Understand the flow</li>
        <li>Assign probabilities (now it's a Markov chain)</li>
        <li>Enact the randomness</li>
        <li>Have some fun with it</li>
        <li>Make it recursive (but note that it "bottoms out")</li>
        <li>More generators! <a href="https://perchance.org/verb">verbs</a>, <a href="https://perchance.org/preposition">prepositions</a>, <a href="https://perchance.org/useful-generators">etc</a></li>
    </ol>

    <h4>Part 2: algorithm for <em>producing</em> a flow chart from text, a.k.a. The simplest model of model training</h4>

    <p>For this exercise, you'll need two pieces of paper – or one slide (as in PowerPoint) and one table (as in Excel). If you're using paper, the first should be held in landscape (horizontal) orientation; the second can be either landscape or portrait (vertical).</p>

    <p>Choosing one of the short phrases below to be "the text," proceed through the numbered steps that follow. (NB: These are modified only slightly from Egan's.)</p>

    <p>Options for texts:<ul>
        <li>"It was the best of times, it was the worst of times" (Dickens)</li>
        <li>"Beauty is truth, truth beauty,—that is all
        Ye know on earth, and all ye need to know" (Keats)</li>
        <li>"Every cat is an animal, but not every animal is a cat" (Onuoha and Mother Cyborg 43)</li>
        <li>"all examples of deep learning are examples of machine learning, even though not all machine learning is deep learning" (Onuoha and Mother Cyborg 50)</li>
        </ul>
    </p>

    <ol class="spaced">
        <li>Draw a ["Start"] box on the left side of your  <ins>first</ins> piece of paper <ins>(or slide)</ins> and to the right of it draw a box containing the first word of the text. Draw an arrow linking "[Start]" to the first word of the text. Think of that first word as the "Current word" and underline it in the text to keep track of where you are.</li>
        <li><ul><li>If the underlined "Current word" is the last word in the text and it already has an arrow to a "[Stop]" box, stop the assignment.</li><li>If the underlined "Current word" is the last word in the text and it does not already have an arrow to a "[Stop]" box, draw a "[Stop]" box to the right of the box for "Current word" and link the "Current word" box to the [Stop] box with an arrow and then stop this assignment.</li></ul></li>
        <li>If the underlined "Current word" is not the last word in the text, count how many times "Current word" appears in the text (including the underlined occurrence) and write that number down underneath a forward-slash division sign, as in "/3" if "Current word" appears in the text three times.</li>
        <li>On <del>a spare</del><ins>your second</ins> piece of paper<ins> (or spreadsheet)</ins>, make a "Comes next" list for "Current word" as follows. <ol class="lalpha"><li>For each occurrence of "Current word" in the text, including the underlined one, write down the single word that immediately follows it.</li><li>Beside each of these words that "Comes next" write how many times it "Comes next" after the "Current word" in the text and follow that count with the divisor from Step (3). Thus, if "Current word" appears in the text three times there must be three words that follow "Current word", but they are not necessarily three different words.</li><li>If "Current word" is followed by the word "the" two times and is followed by the word "on" one time, write down "the 2/3" and "on 1/3" in the "Comes next" list.</li><li>If one of the occurrences of "Current word" in the text is the last word in the text, add the item "[Stop]" to the "Comes next" list and add its fraction (which will be 1 over the number of occurrences of "Current word" in the text).</li></ol></li>
        <li>Returning to your Markov Chain, draw a box to the right of the "Current word" box for each of the words (or the "[Stop]" token) in the "Comes next" list you made in Step (4) that you don't already have a box for, then put the word (or the "[Stop]" token) from the "Comes next" list inside the box and draw an arrow from the "Current word" box to each of these new boxes. <ul><li>If one of the words (or the "[Stop]" token) in the "Comes next" list made in Step (4) already has a box drawn in a previous step, don't draw a new box but instead draw the arrow from the "Current word" box to the existing box.</li> <li>Beside each arrow put the associated "weight" from the "Comes next" list made in Step (4). Thus, if "Current word" is followed by the word "the" two times and is followed by the word "on" one time, write beside the arrow from the "Current word" box to the "the" box the fraction "2/3" and write beside the arrow from the "Current word" box to the "on" box the fraction "1/3".</li></ul></li>
        <li>Cross "Current word" off from the text. The next word in the text is your new "Current word", so underline it. You must already have a box for this new "Current word" since you just drew it in Step (5) or in a previous iteration of that step.</li>
        <li>Go to Step 2.</li>
    </ol>


    <h4>Part 3: Reflection</h4>

    <p>How did it go? Do you have any new insights or questions to pose about how computers might crawl text and assign probabilities to the features they find there?</p>

    <p>In reality, it's quite a bit more convoluted than this: rather than map literal words directly, for example, they build classes, or groups, of recurring word-types and assign weights both to the groups and to the terms within them. And then they build groups of groups, and so on. (And that's not even mentioning the fact that <a href="https://www.youtube.com/watch?v=uSinkCeUg9U">they don't really know what words are</a>.)</p>

    <p>But if you can imagine this process being sped up to the point where electrons, rather than eyes, are moving back and forth over the text, you won't be too far off from getting the idea. If you want further details, check out the relevant EXT sources from this week, especially Cheung.</p>
</details>
</section>


## Homework for next time {#hw}

### For next week

As always, continue working on your project, and take notes in your [Mindful Practice Journal](projects.md) and (if you're using GitHub) in commit messages.

To prepare for week 12:

* Search the internet for a **respected public-facing digital project in your field or discipline.**
    - Do any of your field's organizations or conferences sponsor awards for digital work? If so, you might start there. If you're not sure, now's a good time to find out!

* Of the projects you find, **choose one** that inspires you, and **post a link** to your chosen project to the [discussion forum]({{site.repo_url}}/discussions). Add a few words about what the project is and what's cool about it.

* **Be ready to present and discuss your chosen project**: its sources, methods, and presentation choices, as well as the arguments it makes or questions it helps us investigate. What does the digital medium facilitate?

As I've mentioned before, I'll be out of town, but Alison has graciously agreed to anchor me for remote attendance. <!-- See if Alison can take the Owl -->

### Looking ahead
* I won't have [office hours](../office) on Monday afternoon, but I will this Thursday and next, and you can also email me to set up an alternative time if that doesn't work for you.

* The week after next will already be our third project presentation, brought to you by "and...?"
    - I'll expect for you to have some kind of _argument or takeaway for readers_, however tentative. What does it seem like you're able to say now that you couldn't have said at the start of the semester?
    * This will be our final in-class presentation before the final presentations, and we don't have time for all 10 presentations *and* full rounds of feedback. So we should discuss **our options**:
        - If everyone can **pre-record** a five-minute video and post it by Friday, November 14, we could watch over the weekend and skip straight to feedback. But I realize that's a lot to ask. And we might still run out of time.
        - We could **split** into smaller groups for presentations and feedback. It would be easier in a bigger classroom, but I'm sure we could manage.
        - Or we could **randomly select** five presenters.
    * Regardless, everyone will post, and everyone will write and receive two written peer reviews.
* The week after *that* is Thanksgiving week. No class!
* And the week after Thanksgiving is the "People's Choice." We can practice with HTML and CSS; we can select a topic to read about and discuss; or we can have a full-class working studio to act as an accountability group for each other.
    - If you have ideas for what you'd like to do that aren't yet on the list, please email me this week! I'll add to a survey for when I get back.
