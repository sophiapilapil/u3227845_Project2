### 11056 - Front End Web Design

# A2 - PROJECT WEBSITE REFLECTION

### u3227845 - Sophia Pilapil

The project objective was to __explore the use of ChatGPT to initially code a one-page, responsive website__, and discover the impacts of doing so. With this, it was presumed that ChatGPT would generate basic, Bootstrap-like coding which I suspected would limit the creativity in the visual design. With this, I wanted to challenge myself to __create a website that avoided looking generic__. Additionally, although the Project Brief states that it is a *minimum* one-page website, I wanted the challenge of limiting the page number to just one to explore various ways of presenting different content. 


My approach to this task was to create a website for a fictional brand called *The Soul* which is based on the Stats For Spotify website. The website presents different data and information about your personal Spotify activity. I chose this topic because there is a lot of information and I wanted to investigate whether I can present it on a one-page website in a way that does not clutter the page. This means that __hierarchy, grids, and structure__ are crucial for the flow of the website, which I established early in the development process. The website structure is dependent on the hierarchy from the top of the page to the bottom.


In the process, I initially began with ChatGPT as I never used it before this project. I quickly realised that it was difficult to avoid generic responses without knowing what I wanted from the AI. With this, I created a __lo-fi prototype__ that helped me understand the direction that I wanted from this website. I was able to decide the order of the content based on the narrative I wanted to portray. Although, during the coding process, I did realise that the *Song of the Day* section should be higher on the page to engage the audience more and bring them into the narrative earlier rather than later. Further, I found that the prototype helped me curate my prompts for ChatGPT with more direction and specifications, rather than just going open-ended. This allowed me to overcome the goal of avoiding a generic-looking website. However, it would be interesting to approach this task differently with no prototype in the future. This would change the order of the development process. Rather than having unique design factors before using ChatGPT, I would like to challenge myself to do the designing after the coding that ChatGPT provides me to see what obstacles I will encounter. 


![Lo-Fi Prototype](/assets/images/fewd%20A3%20mockups.png)


During the process of AI coding generation, I acknowledged __my advantage of pre-existing knowledge of coding syntax as it guided me to curate my prompts__. For example, I asked AI to code me an HTML starting code, and it provided me with:

![Initial ChatGPT HTML Template](/assets/images/htmlcode.png)

However, because of my coding knowledge, I understood that I need a boilerplate template to satisfy my intentions for the website. With this, I changed my language to ask for a basic HMTL5 boilerplate template, to which ChatGPT replied with:

![Improved ChatGPT HTML5 Boilerplate template](/assets/images/htmlcode2.png)

I used this knowledge to target more specific elements of the website for AI and it helped me create a more descriptive and accurate response from ChatGPT. In the future, I would like to approach this task differently and limit my use of coding syntax in ChatGPT. This will determine whether someone without the same coding knowledge can develop a similar website or if ChatGPT is only effective with pre-existing knowledge. 


Although using multiple prompts per section was beneficial in dividing the development process, I faced a few challenges by doing so. For example, because each prompt was separate, I found that ChatGPT used the same class name that it used for another section. This means that the most recent CSS for the class will override the style for the class before. Due to this, whenever I added a new CSS style, I would have to ensure that it did not override other styles. If it did, I would have to change the name. For example, I asked ChatGPT to create the header and the footer separately and both included a logo that is styled differently. Due to this, I changed the class name from “logo” to “logo2”. This example was a quick fix, however, it did get confusing with all the cards that I used for each section at first, particularly as I just copied and pasted it rather than writing it all myself. However, as I familiarised myself with the HTML and CSS files, it was easier to navigate around. 


Another problem I faced was creating the responsive hamburger menu through ChatGPT. The first obstacle was that AI always generated coding that included JavaScript, which is beyond the scope of my skills. This was an easy fix as I ask AI to code it without Java. The real obstacle was that no matter how I worded it, ChatGPT’s generated code never worked to what I desired:

![ChatGPT Hamburger HTML](/assets/images/hamb-html.png)

![ChatGPT Hamburger CSS 1](/assets/images/hamb-css1.png.png)

![ChatGPT Hamburger CSS 2](/assets/images/hamb-css2.png)

I eventually just utilised the hamburger menu from the previous assignment as a template because ChatGPT could not provide me with a working code. 


One challenge also worth noting was that even when ChatGPT’s coding did work, I often found myself going back and personalising/fixing the codin, which got harder as the files got bigger. This contradicted my tactic of being specific because if I was too specific, AI would create an undesired code. To overcome this, I began to __use AI as a foundation for coding and personalised the content myself (i.e. colours, heights, widths etc.), increasing the effectiveness experience with AI coding__. 


Amongst these challenges, I believe that the use of AI is still beneficial for coding depending on the approach. AI can be efficient using prototypes, having HTML and CSS syntax and breaking up the prompts into more specific elements all helped in developing the website. AI is highly beneficial as a foundation for coding, particularly if you aim to create a unique design with efficiency. Using ChatGPT specifically as an AI was helpful because it described what they were doing. This allowed me to understand what they are generating and why. This description expanded my knowledge of HTML and CSS such as learning about z-index, using infinite animations/transitions, and creating a horizontal/vertical scroll. I believe beyond the negative connotations that AI has, if used correctly it can help expand your abilities as it saves time.