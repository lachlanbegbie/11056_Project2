# 11056_Project2
 
# ChatGPT

## Original Prompt

Working with ChatGPT to write the HTML code was finnicky. It took several alterations to the prompt to get something to work from. As well as altering the prompt, it also took follow up prompts to finish the code, as it would usually stop halfway through. The final promt placed into ChatGPT is included below.

*"Write a semantic HTML code document which includes styling with bootstrap and CSS. The content should include three paragraphs about the history of Australian poetry, and include information on three famous Australian poetic works, with information on their authors. These works should be The Man From Snowy River by Banjo Patterson, My Country by Dorothea MacKellar and We Are Going by Oodgeroo Noonuccal."*

# Production Reflection

## Production Approach

The aim of this assessment was experimentation, so my approach to this assessment was "experimentation with a purpose". I was ultimately setting out to understand front-end frameworks though Bootstrap, so when considering how I would approach applying this tool, I thought about how I would probably utilise the developed resources to improve my own websites. Largely what came to mind was the features which I had attempted before or knew of which I do not currently have the skills to develop from scratch. So my approach became about including those elements (notably modals and carousels) and seeing how they could be incorporated among the code, and also using Bootstrap to style the page where I could, to better understand the system.

## Production Process

The first step of the process was generating the website with ChatGPT. This step was about an hour and a half of trying different additions to a basic prompt to get a result which I was happy with. It started out with a prompt like *"Generate a semantic HTML website which uses Bootstrap"* and by adding instructions about basic styling and what content to include (to recieve consistent results), I arrived at the prompt included above. I did later use ChatGPT again to get further content, and also to generate styles which did specific things, such as altering the horizontal border width to get the timeline marker on the carousel.

Following that, I worked to understand the code that ChatGPT had generated. This was the point where I worked around backgrounds, fonts and item size and placement, so I could work with most elements on the page and figure out what controls what. This was the most painful process, as I didn't write the HTML file or the Bootstrap CSS file, so I had no idea what anything did or how to work with it, as I didn't know which properties were used inside of which selectors to alter a frame I was seeing on screen. There was a lot of time spent in the inspector, and learning I could download the Bootstrap CSS file to search it was a huge help. What do they say, "short cuts make long delays"? I definitely think that applies to this.

Once I had a basic idea of what I was working with, I started including the features U was looking to include. To display the poem, I started with a collapse element, so when you clicked the button, a box would swipe open underneath the description. I later changed this to a modal when considering the amount of white space the collapse element created with such vertical content. I also implemented a carousel to the bottom of the page to act as an interactive timeline. I ran into some problems with the carousel surrounding the transition frames. What would happen is it would appear to slide past a whole white space between the slides, because of how the function was actually set up. To fix this, I moved the border line to the bottom of the title (outside the carousel), so although nothing changed with how the function works, it looks like it is fixed.

## Reflection

Following this project, I am not a massive fan of using front-end frameworks. At least for the whole project. Whenever I was trying to work with an element to get it looking the way I wanter, I felt like I had not control, like the code is was creating was really innefficient, always contradicting itself. Possibly if I were to begin the project again, I would not ask ChatGPT to write any Bootstrap styling in to begin with, and I would only include it where I saw necessary, such as in creating a modal or carousel. I think this would help to regain some of that control I felt I had lost over my own project.
