
# Week 07: Materiality + Modeling
<span class="date">October 6, 2025</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul>
            <li>Jannidis, Fotis, and Julia Flanders. “2 A Gentle Introduction to Data Modeling.” <em>The Shape of Data in Digital Humanities: Modeling Texts and Text-Based Resources</em>, by Julia Flanders and Fotis Jannidis, Taylor & Francis Group, 2018, pp. 55–65. ProQuest Ebook Central, <a href="http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=5582790">http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=5582790</a>.<ul>
                <li>Section 1: What Is Data Modeling?</li>
                <li>Section 2: Some Basic Concepts</li>
                <li>rest of chapter is EXT</li>
                </ul>
            </li>
            <li>Cairo, Alberto. “3: The Truth Continuum.” The Truthful Art: Data, Charts, and Maps for Communication, New Riders, 2016, <a href="https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html">https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html</a></li>
            <li>Ensmenger, Nathan L. “The Cloud Is a Factory.” <em>Your Computer Is On Fire</em>, edited by Thomas S. Mullaney, Benjamin Peters, Mar Hicks, and Kavita Philip, MIT Press, 2021, pp. 37–60. ProQuest Ebook Central, <a href="http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6479710">http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6479710</a>.</li>
            <li>Neely-Cohen, Maxwell. "Century-Scale Storage." <a href="https://lil.law.harvard.edu/century-scale-storage">https://lil.law.harvard.edu/century-scale-storage</a>. Accessed 29 July 2025.</li>
            <li>Ford, Paul. <em>What Is Code? If You Don’t Know, You Need to Read This</em>, Bloomberg.com, <a href="http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/">http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/</a>. Section 2: "Let's Begin."</li>
        </ul>
    </details>
    <details><summary><strong>Writing to turn in</strong></summary>
        <ul><li>Reading responses from John, Rose, Tunga, Scylla, Yuqing, posted to the <a href="{{site.repo_url}}/discussions/">discussion forum</a></li></ul>
    </details>
</section>

## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Warm-up writing
    - Reading responses & follow-ups
    - Writing to remember (inkshedding)
* [Second half](#second-half): Let's practice!
    - Reflective writing: the Socio-Technical Sustainability Roadmap (in miniature)
    - Project studio (and mini-conferences)
* [Homework for next time](#hw):
    - Time + (especially) Space


## First half: Let's discuss! {#first-half}

### Warm-up writing

Of the many visualizations or figures you've seen in the last two weeks, what sticks with you? See if you can jot down a title or a description or draw a quick sketch. Can you remember what the argument was, either within the figure or in the authors' discussion of it? (Was there an argument? If not explicitly, perhaps implicitly?) What about the figure helps you remember?


### Reading responses & follow-ups

<details><summary>"by someone for some purpose at a specific point in time"</summary>
    <p>Tunga brings in this passage from Flanders and Jannidis, and poses a question about process and conscientiousness that I think is worth repeating in full for those who haven't seen it yet:</p>

    <blockquote>So one could say that a model is a representation of something by someone for some purpose at a specific point in time. It is a representation that concentrates on some aspects—features and their relations—and disregards others. The selection of these aspects is not random but functional: it serves a specific function for an individual or a group. And a model is usually only useful and only makes sense in the context of these functions and for the time that they are needed. (Flanders and Jannidis 46)</blockquote>

    <p>This paragraph made me pause at how explicitly contingent modeling is: it’s not a neutral capture of “what is,” but a time-bound choice about what matters. That contingency feels less like a flaw and more like the point that models are instruments for reasoning, not mirrors which reframes how we should present and critique them. For someone trained in literary analysis, here is what I see: every critical argument is also a model, imposing boundaries that enable certain insights and foreclose others. I find myself wondering: If a model is always chosen “by someone for some purpose at a specific point in time,” <strong>what concrete steps should modelers take to document those purposes and assumptions so future users can treat the model as an interpretive artifact representing the interpreter's thought process rather than a neutral fact?</strong> (emphasis added)</p>

    <p>Thoughts welcome! I (Ben) would posit three words will be important: <em>documentation</em>; <em>about</em>; and <em>README</em>. (I'd love to call in Yixuan to show the <a href="https://github.com/VidaYixuan/digital-humanities-novel-database">GitHub README for her project</a>, which is a great starting point.)</p>
</details>

<details><summary>how to be more right (on the line from falsehood to truth)</summary>
    <p>Responding to Cairo's remark that "When you devise a mdoel, it's never possible to know exactly where it lies in the continuum," John asks a big question: <strong>"What can we do as researchers to move our model toward the 'Absolutely True' end of the spectrum?"</strong> There have to be many answers, of course, not just one – but one, I think, is suggested by Scylla in response to another passage from the same text:</p>

    <blockquote><p>Something that sticks out to me is towards the middle of the reading, where Cairo discusses emailing back and forth with Anatoly Bondarenko, discussing Ukrainian politics and protests that were being covered in the media, and mapped out in various data visualizations:</p>

    <blockquote><p>I immediately shot an e-mail to Anatoly asking, “Do you remember the map that you showed me when I was in Kiev? It explains everything that is going on right now in your country! It’s so prescient! Ukraine is clearly two completely different countries!”</p>

    <p>A few hours later, Anatoly replied. His suggestion, which I am not reproducing verbatim, became a motto that I share with my students every semester: <strong>“It’s more complicated than that.”</strong> I usually add: “And if it’s really more complicated than that, then that complexity, which is crucial for understanding the story, needs to be shown in the visualization.” <strong>Good visualizations shouldn’t over-simplify information. They need to clarify it. In many cases, clarifying a subject requires increasing the amount of information, not reducing it.</strong></p></blockquote>

    <p>There's an interesting tension between simplification and clarification in the way that data is visualized and represented that this passage flags that gives me pause. The idea of increasing information to clarify screams, "Add context!!! Prevent context collapse!!!" to me, but I was curious what other folks thought of, involving this quote.</p>
    </blockquote>
</details>

<details><summary>when you ask me what "digital studies" might mean</summary>
    <p>Ensmenger's "The Cloud is a Factory" is not computational: it's not underwritten by a relational database or engaged in replicable visualization techniques. But nevertheless, I would argue it's very much a digital humanities project. How do you understand the work he's doing here?</p>
    <p>If it's helpful, here's a sample passage:</p>
    <blockquote>All of this is to establish that it is impossible to understand the emergence of the modern information society without reference to the larger history of industrialization. Why is this significant? Because industrialization is fundamentally as much a social and political project as it is technological or economic. The ostensible driving force behind industrialization is the pursuit of efficiency, but the actual history of how, when, and why certain economic sectors chose to industrialize suggests otherwise. New techniques and technologies do not emerge out of nothing to revolutionize work practices; they are designed explicitly to do so. Machines are designed by humans to accomplish human agendas, and as such it is essential to always ask why industrialization is happening, to what ends, and for what purposes. (43)</blockquote>
</details>

<details><summary>the cloud is here. what follows?</summary>
    <p>Rose draws our attention to some of the takeaways at the end of Ensmenger's "The Cloud is a Factory" and brings them into a particularly local context: Pittsburgh's historical access to the things that attract factories, including digital ones. Starting in the middle of her quoted passage:</p>
    <blockquote>
        <blockquote>When Amazon recently encouraged cities to bid for the privilege of hosting their “second headquarters,” they were clearly pushing for those cities with well-established physical and social infrastructures: housing, highways, schools, restaurants, and recreational facilities. When Microsoft or Facebook looks to locate a new data center, they require easy access to inexpensive electricity, a plentiful water supply, and an appropriately skilled labor force. It is any surprise that these data centers are often located in the same places that housed industrial-era factories just a generation ago?" (Ensmenger 43–44)</blockquote>
        <p>This made me wonder about Pittsburgh as a location for the Cloud Factories, as one of these places that used to house industrial-era factories. I remember Alison mentioning the construction of new data centers in Pennsylvania, which led me to find <a href="https://www.datacentermap.com/usa/pennsylvania/">this interactive map</a> (an interesting data visualization in its own right) that shows their locations across the state.</p>
        <p>I wanted to adjust Ensmenger's question: <strong>with this sense of geographical closeness, how can we more accurately depict the Cloud as a factory in our digital work at the University of Pittsburgh, and not as a disembodied computational device?</strong></p>
    </blockquote>
</details>


Let's discuss! And maybe we can take some collaborative notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes)?

If we get to inkshedding by around 10:15, that should leave us with enough time to share and break and still beat the 11:00 rush.



### Writing to remember

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, **I'll ask everyone to share one thing**, to which we'll all say, simply, "thank you."



## Break (10 minutes)
Assuming we left off at 10:35, let's aim to start up again at 10:45 or so. That should beat most of the rush for 11am classes.



## Second half: Let's practice! {#second-half}

### Reflective writing

One piece I didn't quote from above is Neely-Cohen's "Century-Scale Storage." While that goal is potentially out of any one person's control (as he makes clear), it's not a bad idea to think about the future of your files, the potential paths for your projects, however mid-process (or beginning-process) you may feel.

As part of a local effort to decide the future of a medieval art website, our very own Alison Langmead – with a team of students and funding from the National Endowment for the Humanities – produced a series of reflective exercises known as the [Socio-Technical Sustainability Roadmap](https://sites.haa.pitt.edu/sustainabilityroadmap/getting-started/). It's meant to be a multi-part, interactive workshop for team members on DH projects to address an important, but often unasked, question: "How long do we want this to last?"

The full workshop is meant to take two days and involve a fair amount of conversation among stakeholders. We don't really have that time in class today, as it turns out, but, in keeping with the DSAM 3000 "sampler" ethos, I wanted to give you a little taste.

**Over the next 30 minutes or so, please:**

1. Read the introduction to the STSR, "[Welcome and Getting Started](https://sites.haa.pitt.edu/sustainabilityroadmap/getting-started/)"
2. Glance briefly at the [Overview of the STSR Modules](https://sites.haa.pitt.edu/sustainabilityroadmap/getting-started/), so you have a sense of where we are, and where where we aren't going (together, today; you can always come back as part of your independent time!)
3. Read through the brief intro to [Module A1: What is the scope of your project](https://sites.haa.pitt.edu/sustainabilityroadmap/a1-project-scope/) and decide on one "site of production" to think about for now.
4. Continue working through the modules in section A, thinking – and writing! – about:
    * your hoped-for timeline, recognizing that not all projects need to last 100 years
    * your _designated communities_, the people you most want to benefit from the particular site of production you've chosen for today
    * the must-have properties of your project, without which it won't achieve its goals

<div class="alert alert-success panel panel-success">
    <div class="alert-body panel-body">
    Use the worksheets where they make sense for you, and take notes in your own space, at least for now: this is part of your Mindful Practice.
    </div>
</div>

**At around 11:20, no matter where you're up to, jump to [Module A5: the Project Documentation Checklist](https://sites.haa.pitt.edu/sustainabilityroadmap/a5-documentationchecklist/).** There you'll find some excellent advice about how to keep track of your project as it goes and as it grows – including the kinds of process decisions that Tunga was asking about in regard to the modeling chapter.

#### EXT: Studio
If you finish all of Section A, you can use the remaining time to work on your project however you see fit. Please let me know in the [google doc](https://bit.ly/dsam{{site.course.slugterm}}-notes) what you're working on.

### EXT: Debrief
I want to make sure we can preview the homework, but if we have 5 minutes to spare, I would love to bring us back together to hear your thoughts on what it was like to ask yourself these kinds of questions – however briefly - at the start of a project.


## Homework for next time: {#hw}

As always, please continue working on your project, and remember to keep track of your time in your [Mindful Practice Journal](projects.md).

After reading the texts below, please head to the [discussion forum]({{site.repo_url}}/discussions); the group that did not post last week (so Yanni, Namrata, Amrita, Yixuan, and Li) is now due to **post a passage and a question** that will kick off our in-class conversation when we return. If you want to claim first-rights for one of the texts below, you have the option to do so on the [notes doc](https://bit.ly/dsam{{site.course.slugterm}}-notes).

To prepare for week 08, on Space + Time, please **watch / read**:
<!-- The first three are more theoretical; Roth is a bit of a catalog, but it gets more into practicalities. For full-on advice on making maps, see the EXT reading. -->

* Hoekstra, Rik, and Marijn Koolen. “Data Scopes for Digital History Research.” <em>Historical Methods: A Journal of Quantitative and Interdisciplinary History</em>, vol. 52, no. 2, Apr. 2019, pp. 79–94. Taylor and Francis + NEJM, <a href="https://doi.org/10.1080/01615440.2018.1484676">https://doi.org/10.1080/01615440.2018.1484676</a>.
* Murrieta-Flores, Patricia, and Bruno Martins. “The Geospatial Humanities: Past, Present and Future.” <em>International Journal of Geographical Information Science</em>, vol. 33, no. 12, Dec. 2019, pp. 2424–29. Taylor and Francis+NEJM, <a href="https://doi.org/10.1080/13658816.2019.1645336">https://doi.org/10.1080/13658816.2019.1645336</a>.
* Zhao, Bo. “Humanistic GIS: Toward a Research Agenda.” <em>Annals of the American Association of Geographers</em>, vol. 112, no. 6, Aug. 2022, pp. 1576–92. Taylor and Francis+NEJM, <a href="https://doi.org/10.1080/24694452.2021.2004875">https://doi.org/10.1080/24694452.2021.2004875</a>.
* Roth, Robert E. “Cartographic Design as Visual Storytelling: Synthesis and Review of Map-Based Narratives, Genres, and Tropes.” <em>The Cartographic Journal</em>, vol. 58, no. 1, Jan. 2021, pp. 83–114. Taylor and Francis+NEJM, <a href="https://doi.org/10.1080/00087041.2019.1633103">https://doi.org/10.1080/00087041.2019.1633103</a>.

* EXT for eager readers:
    - Carroll, Allen, and the Esri StoryMaps team. “Nine Steps to Great Storytelling.” ArcGIS StoryMaps, 3 July 2025, <a href="https://storymaps.arcgis.com/stories/429bc4eed5f145109e603c9711a33407">https://storymaps.arcgis.com/stories/429bc4eed5f145109e603c9711a33407</a>.
    - Cairo, Alberto. "8: Revealing Change." _The Truthful Art: Data, Charts, and Maps for Communication._ [https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch08.html](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch08.html)
