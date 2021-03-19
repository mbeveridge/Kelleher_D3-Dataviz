# Get it Right in Black & White

"New Livestream Series: Get it Right in Black and White" -- [VizHub blogpost](https://vizhub.com/blog/2021/02/20/new-livestream-series-get-it-right-in-black-and-white/) (2021-02-20)

[[VizHub Forum topics for course](https://vizhub.com/forum/c/get-it-right/10)] - [[My VizHub profile](https://vizhub.com/mbeveridge)]

_"I'm very excited to begin again from the beginning. I have learned a lot from teaching this course in [2018](https://github.com/curran/dataviz-course-2018) and [2020](https://datavis.tech/datavis-2020/)"_ -- Curran Kelleher, in Episode 1 (2021-03-06)

## Tentative Calendar
It will go every Saturday for a year or more

* ~~March 6: Introduction to HTML, SVG and CSS~~
* ~~March 13: Pseudo Visualizations~~
* March 20: Manipulating SVG graphics with JavaScript
* March 27: Manipulating SVG graphics with D3
* April 4: TBD
* April 11:


## Episodes

#### 001 : "SVG Fundamentals" (2021-03-06)
###### [_[forum](https://vizhub.com/forum/t/episode-1-svg-fundamentals/111)_] - [_[slides](https://docs.google.com/presentation/d/1RcUnOuJuDzNuZYX_2wqyWD2_1SHixtOT89Rr2a-6lp4/)_] - [_[myWorkings](https://vizhub.com/mbeveridge/3dc97f59afca440da2661c1d9d76bf82)_] - [_myExercise_]

###### video [[1:07:18 edited](https://www.youtube.com/watch?v=UQ_kqGDM8A4)]; [[1:26:20 raw (incl chat window)](https://www.youtube.com/watch?v=qaiS88ocS2M)]

* What is [HTML](https://youtu.be/UQ_kqGDM8A4?t=477), [CSS](https://youtu.be/UQ_kqGDM8A4?t=641) and [SVG](https://youtu.be/UQ_kqGDM8A4?t=703)
* ~~"[Question: Why does SVG exist?](https://youtu.be/UQ_kqGDM8A4?t=851)"~~
* ~~"[Question: How does SVG relate to XML?](https://youtu.be/UQ_kqGDM8A4?t=985)"~~
* "[Intro to VizHub](https://youtu.be/UQ_kqGDM8A4?t=1275)" ...[[https://vizhub.com/](https://vizhub.com/)]
* ~~"[Bare Bones HTML Page](https://youtu.be/UQ_kqGDM8A4?t=1463)"~~
* ~~"[Working with HTML Locally](https://youtu.be/UQ_kqGDM8A4?t=1668)"~~
* ~~"[Title & Description in VizHub](https://youtu.be/UQ_kqGDM8A4?t=1781)"~~
* "[Creating an SVG Element](https://youtu.be/UQ_kqGDM8A4?t=1844)" ...`<svg> ... </svg>`
* "[SVG Circles](https://youtu.be/UQ_kqGDM8A4?t=1924)" ...`<circle cx="50" cy="50" r="50"></circle>`
* "[Question: Tags vs. Elements?](https://youtu.be/UQ_kqGDM8A4?t=1999)"
* "[Inspecting Elements with Chrome DevTools](https://youtu.be/UQ_kqGDM8A4?t=2115)"
* "[Manual DOM Manipulation with DevTools](https://youtu.be/UQ_kqGDM8A4?t=2212)" ...cf. JavaScript (D3, React, Vue, Svelte, JQuery) DOM manipulation
* "[Adding Collaborators in VizHub](https://youtu.be/UQ_kqGDM8A4?t=2344)"
* "[The 'fill' attribute](https://youtu.be/UQ_kqGDM8A4?t=2407)" ...`fill="red"`
* "[Using Prettier to auto-format code](https://youtu.be/UQ_kqGDM8A4?t=2431)"
* "[The coordinate space of SVG](https://youtu.be/UQ_kqGDM8A4?t=2483)" ...(0,0) is top-left
* "[SVG Width and Height](https://youtu.be/UQ_kqGDM8A4?t=2546)" ...`<svg width="960" height="500">`
* "[SVG Rectangles](https://youtu.be/UQ_kqGDM8A4?t=2599)" ...`<rect ... />`
* "[Setting "fill" to "none"](https://youtu.be/UQ_kqGDM8A4?t=2626)"
* "[The "stroke" attribute](https://youtu.be/UQ_kqGDM8A4?t=2636)"
* "[The "stroke-width" attribute](https://youtu.be/UQ_kqGDM8A4?t=2655)"
* "[Z Ordering (layering) in SVG](https://youtu.be/UQ_kqGDM8A4?t=2670)" ...depends on their order in the SVG document
* "[SVG Lines](https://youtu.be/UQ_kqGDM8A4?t=2756)" ...`<line x1="0" y1="0" x2="100" y2="100" stroke="navy"></line>`
* "[Question: Shapes beyond width and height (clipping)?](https://youtu.be/UQ_kqGDM8A4?t=2817)"
* "[SVG clip path concept](https://youtu.be/UQ_kqGDM8A4?t=2925)"
* "[Debugging invalid HTML (no self-closing tags allows)](https://youtu.be/UQ_kqGDM8A4?t=2951)"
* ~~"[Question: Differences between SVG lines and SVG paths](https://youtu.be/UQ_kqGDM8A4?t=3093)"~~
* "[SVG Paths and the "d" attribute](https://youtu.be/UQ_kqGDM8A4?t=3180)" ...`<path fill="none" d="M200,200L300,300L300,400" stroke="black" stroke-width=10"></path>` [M is move-to; L is line-to] [Path is used for line charts, area charts, geometries in maps (like countries), etc]
* "[HTML Comments](https://youtu.be/UQ_kqGDM8A4?t=3395)" ...`<!--... -->`
* "[Question: Can you make layers in SVG?](https://youtu.be/UQ_kqGDM8A4?t=3424)"
* "[Question: Upper case vs. lower case in the "d" path attribute](https://youtu.be/UQ_kqGDM8A4?t=3476)"
* "[Review of SVG path commands documentation](https://youtu.be/UQ_kqGDM8A4?t=3557)" ...[[MDN](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/d#path_commands)] ...but usually copy-paste from a tool
* "[Absolute vs. relative coordinates in SVG paths](https://youtu.be/UQ_kqGDM8A4?t=3651)"
* "[Question: How to communicate around this async? D3 Slack? VizHub Forum?](https://youtu.be/UQ_kqGDM8A4?t=3721)" ...[[VizHub Forum topics for this course](https://vizhub.com/forum/c/get-it-right/10)]
* "[Exercise: Make something creative with SVG Shapes!](https://youtu.be/UQ_kqGDM8A4?t=3831)"


#### 002 : "Pseudo Visualizations" (2021-03-13)
###### [_[forum](https://vizhub.com/forum/t/episode-1-svg-fundamentals/111)_] - [_slides_] - [_myWorkings_] - [_myExercise_]

###### video [[1:11:18 edited](https://www.youtube.com/watch?v=UunbNeXhhaU)]; [[1:37:20 raw](https://www.youtube.com/watch?v=f5mYd-ufank)]