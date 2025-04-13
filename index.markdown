---
layout: default
---

## Abstract

Timelines have traditionally been limited to pre-curated content, restricting users to predefined scopes (e.g., themes or time periods) rather than empowering them to creatively explore evolving areas of curiosity. Leveraging recent advances in AI that can cater to dynamic information needs, we envision more adaptable timelines that provide untethered experiences to enable curiosity-driven exploration. We propose the concept of a generative timeline—a timeline that expands or contracts to adapt to users’ evolving exploration and knowledge-building processes. To instantiate and evaluate this concept, we developed KnowledgeTrail, an interactive system that empowers users to flexibly explore historical events and the process of knowledge formation. A preliminary evaluation with eight participants revealed that KnowledgeTrail supports creative exploration, fosters serendipitous discoveries, and subsequently results in a self-reinforcing cycle of curiosity. This paper contributes the concept of a generative timeline, insights into its design and user experience, and implications for future timeline-based systems that embrace dynamic, user-driven exploration.

---


<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/RjxtAh414WU?si=mO_QHjW_32NUxNBb&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


<!-- 
---
<h2 id="node">Generative Timeline</h2>

Our work introduces the concept of the generative timeline. The illustration below highlights its key features. Prior work on timelines involved timelines either constructed from pre-existing documents or curated by experts, limiting users' ability to explore beyond the available dataset or the predefined timeline. In contrast, with the use of AI models, the generative timeline can dynamically expand or contract for (A) breadth-based or (B) depth-based exploration, enabling flexible, untethered exploration.

<div style="text-align:-webkit-center">
  <div class="img-container" style="text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/generative_timeline.png"/>
  </div>
</div>


An example of event generation in KnowledgeTrail: Users can generate events relating to a topic by (A) hovering over an event and (B) selecting the Events button in the Expand Bar or (C) Search Bar. This renders them in the canvas with arrows (D) tracing out the path of generation. A description on how these generated events are related is then (E) displayed in the Side Panel under the Relationships tab.
<div style="text-align:-webkit-center">
  <div class="img-container" style="width:100%; text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/Teaser New.png"/>
  </div>
</div>

Contextual Event Generation: Users can steer the type of event generation within a single prompt (e.g. United States). One context (World War II) can generate events focusing around that topic (A), while another context (Revolution) can help constrain the generation to a completely separate group of events (B) when the Events button is clicked.
<div style="text-align:-webkit-center">
  <div class="img-container" style="text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/EventGenerationContext.png"/>
  </div>
</div>

<div style="text-align:-webkit-center">
  <div class="img-container" style="width: 100%; text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/ExplainQuestionsFlow.png"/>
  </div>
</div>
Generating Descriptions Flow: Users can (1) learn more details about a topic in the Search Box or event in the timeline by (2) using the Explain button. A detailed explanation is then (3) generated in the Side Panel for the given topic/event. To facilitate further exploration on the topic, the Questions button (4) can be clicked to generate a list of questions relating to the topic and context. Users can (5) select one of these questions to learn more about and a response will be (6) generated again on the Side Panel.


<div style="text-align:-webkit-center; display: flex; flex-direction: row">
  <div class="img-container" style="width: 50%; text-align: -webkit-center; padding: 5px;">
    <img src="/assets/img/knowledgetrail/Legend1.png"/>
    No Event Types selected
  </div>
  <div class="img-container" style="width: 50%; text-align: -webkit-center; padding: 5px;">
    <img src="/assets/img/knowledgetrail/Legend2.png"/>
    Selected the Event Type
  </div>
</div>
Legend Panel: All Event Types and their assigned color coding are listed here. Users can filter and efficiently navigate (b) to a select group of nodes corresponding to the label they select. Matching nodes of that type are highlighted and the view zooms in to focus on these events.

<div style="text-align:-webkit-center; display: flex; flex-direction: row">
  <div class="img-container" style="width: 50%; text-align: -webkit-center; padding: 5px;">
    <img src="/assets/img/knowledgetrail/SemanticZoom1.png"/>
    Semantic Zoom (Scale > 0.4)
  </div>
  <div class="img-container" style="width: 50%; text-align: -webkit-center; padding: 5px;">
    <img src="/assets/img/knowledgetrail/SemanticZoom2.png"/>
    Semantic Zoom (Scale <= 0.4)
  </div>
</div>
Semantic Zoom: As users zoom out on the Timeline View (<= 0.4 zoom scale) to see relationships and patterns between the generated events (e.g., clusters of nearby events, groupings of similar event types, etc.), the nodes will collapse into dots to make them more salient and readable. As a user (b) hovers over an event, the title for that event is displayed along with a small summary of the event as long as the Explain button has been clicked for this event before. 

<div style="text-align:-webkit-center">
  <div class="img-container" style="width: 100%; text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/SelectTitleOrEvent-horizontal.png"/>
    Navigation from the Side Panel: Users can easily return to previously generated content on the timeline by using the Side Panel. By (2) clicking on the title of a result in the Relationships tab, the Timeline View will change to encompass all of the events referenced in that result. When (3) selecting an individual event in the timeline or the Side Panel, the view will zoom in on that particular event on the timeline. Hovering over an event within a Side Panel result will highlight that event on the timeline to make it easy to spot amongst other generated nodes.
  </div>
</div>


<div style="text-align:-webkit-center">
  <div class="img-container" style="width:70%; text-align: -webkit-center;">
    <img src="/assets/img/knowledgetrail/GenerateRelationships.png"/>
    Generating Relationships: Users can determine the relation between 2 or more separate events generated on the timeline by selecting the events and clicking the Generate Relationship button. A paragraph describing the potential relationship between the events is then generated and displayed in the Side Panel under the Relationships tab.
  </div>
</div> 

-->


{% if site.bibtex %}
------

## Bibtex

<pre>
@inproceedings{suh2023sensecape,
  author = {Suh, Sangho and Min, Bryan and Palani, Srishti and Xia, Haijun},
  title = {Sensecape: Enabling Multilevel Exploration and Sensemaking with Large Language Models},
  year = {2023},
  isbn = {9798400701320},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://dl.acm.org/doi/10.1145/3586183.3606756},
  doi = {10.1145/3586183.3606756},
  booktitle = {The 36th Annual ACM Symposium on User Interface Software and Technology},
  keywords = {Large Language Model, Multilevel Abstraction, Visualization},
  location = {San Francisco, CA, USA},
  series = {UIST '23}
}
</pre>

{% endif %}