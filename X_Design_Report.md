## Design Reports

A report documents the process or incidient that was undertaken or communicate the plan or situation or progress for conducting the project. 
Particularly, the various versions of design reports such as _Conceptual Design Report, Preliminary Design Report, Critical Design Report, etc._ are compiled to communicate the progress or maturity of the project with time. While each of these reports has a dedicated purpose and guidelines, its in our interest to review a well compiled report before embarking on one. 

The centrak guideline for any report revolves around **Requirements**. 
Based on the project timeline and progress, this would generally include a subset of the following

-indentifying the use case,requirement generation

-conceptual operation of the system

-detailing the envisioned or updated functinal or cyberphysical architecture

-detials of the sub-systems

-synopsis of the trade studies that were conducted to determine the operating units for accomplishing the detialed functions

-documenting the performance of the system

-relevants standards or benchmarking processes that were employed to validate the adherence to the funcitonal requirements

-further details such as the work packages that lead to the identified functions

-risks entialed in the process

-risk mitigation strategies

-operating budget or other in-kind financial resources

-finally, conclusion $ future work discussion (learnings) 

This is not an exhaustive description but a model for communicating the operationor conduct of the project. Complying with the guidelines is **critical** and, the team's ingeneous art revolves around mutating this reporting model. 

Training in [systems engineering](http://roboticsknowledgebase.com/wiki/system-design-development/system-engineering/) aids in directig the details of these reports and using these reports as tools to clarify and communicate the goals and progress of the project.

In the following wiki, we survey one of such early stage reports by CMU's Tartan Racing team in their adventure to develop a fully autonomous ground vehicle capable of operating in an **urban environemnt**.

Snapshots of the team's [report](https://www.ri.cmu.edu/publications/tartan-racing-a-multi-modal-approach-to-the-darpa-urban-challenge/) would be used to highlight observations and the flow of the report.

DISCLAIMER: The views expressed or implied or contained in here do not represent the official policies or operation of the team or any of the associated organizations. Alos, it is not in the interest of this document to validate the information contained in the cited Tartan Racing report. 

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.

This template acts as a tutorial on writing articles for the Robotics Knowledgebase. In it we will cover article structure, basic syntax, and other useful hints. Every tutorial and article should start with a proper introduction.

This goes above the first subheading. The first 100 words are used as an excerpt on the Wiki's Index. No images, HTML, or special formating should be used in this section as it won't be displayed properly.

If you're writing a tutorial, use this section to specify what the reader will be able to accomplish and the tools you will be using. If you're writing an article, this section should be used to encapsulate the topic covered. Use Wikipedia for inspiration on how to write a proper introduction to a topic.

In both cases, tell them what you're going to say, use the sections below to say it, then summarize at the end (with suggestions for further study).

## First subheading
Use this section to cover important terms and information useful to completing the tutorial or understanding the topic addressed. Don't be afraid to include to other wiki entries that would be useful for what you intend to cover. Notice that there are two \#'s used for subheadings; that's the minimum. Each additional sublevel will have an added \#. It's strongly recommended that you create and work from an outline.

This section covers the basic syntax and some rules of thumb for writing.

### Basic syntax
A line in between create a separate paragraph. *This is italicized.* **This is bold.** Here is [a link](/). If you want to display the URL, you can do it like this <http://ri.cmu.edu/>.

> This is a note. Use it to reinforce important points, especially potential show stoppers for your readers. It is also appropriate to use for long quotes from other texts.


#### Bullet points and numbered lists
Here are some hints on writing (in no particular order):
- Focus on application knowledge.
  - Write tutorials to achieve a specific outcome.
  - Relay theory in an intuitive way (especially if you initially struggled).
    - It is likely that others are confused in the same way you were. They will benefit from your perspective.
  - You do not need to be an expert to produce useful content.
  - Document procedures as you learn them. You or others may refine them later.
- Use a professional tone.
  - Be non-partisan.
    - Characterize technology and practices in a way that assists the reader to make intelligent decisions.
    - When in doubt, use the SVOR (Strengths, Vulnerabilities, Opportunities, and Risks) framework.
  - Personal opinions have no place in the Wiki. Do not use "I." Only use "we" when referring to the contributors and editors of the Robotics Knowledgebase. You may "you" when giving instructions in tutorials.
- Use American English (for now).
  - We made add support for other languages in the future.
- The Robotics Knowledgebase is still evolving. We are using Jekyll and GitHub Pages in and a novel way and are always looking for contributors' input.

Entries in the Wiki should follow this format:
1. Excerpt introducing the entry's contents.
  - Be sure to specify if it is a tutorial or an article.
  - Remember that the first 100 words get used else where. A well written excerpt ensures that your entry gets read.
2. The content of your entry.
3. Summary.
4. See Also Links (relevant articles in the Wiki).
5. Further Reading (relevant articles on other sites).
6. References.

#### Code snippets
There's also a lot of support for displaying code. You can do it inline like `this`. You should also use the inline code syntax for `filenames` and `ROS_node_names`.

Larger chunks of code should use this format:
```
def recover_msg(msg):

        // Good coders comment their code for others.

        pw = ProtocolWrapper()

        // Explanation.

        if rec_crc != calc_crc:
            return None
```
This would be a good spot further explain you code snippet. Break it down for the user so they understand what is going on.

#### LaTex Math Support
Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering:
\\[ \frac{1}{n^{2}} \\]

#### Images and Video
Images and embedded video are supported.

![Put a relevant caption here](assets/images/Hk47portrait-298x300.jpg)

{% include video id="8P9geWwi9e0" provider="youtube" %}

{% include video id="148982525" provider="vimeo" %}

The video id can be found at the end of the URL. In this case, the URLs were
`https://www.youtube.com/watch?v=8P9geWwi9e0`
& `https://vimeo.com/148982525`.

## Summary
Use this space to reinforce key points and to suggest next steps for your readers.

## See Also:
- Links to relevant material within the Robotics Knowledgebase go here.

## Further Reading
- Links to articles of interest outside the Wiki (that are not references) go here.

## References
- Links to References go here.
- References should be in alphabetical order.
- References should follow IEEE format.
- If you are referencing experimental results, include it in your published report and link to it here.

