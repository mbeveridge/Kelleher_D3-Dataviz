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


* 00:00​ - Intro to the course
* 07:23​ - Intro to this episode
* [07:57]((https://youtu.be/UQ_kqGDM8A4?t=477))​ - HTML
* [10:41](https://youtu.be/UQ_kqGDM8A4?t=641)​ - CSS
* [11:42​](https://youtu.be/UQ_kqGDM8A4?t=702) - SVG
* ~~[14:11​](https://youtu.be/UQ_kqGDM8A4?t=851) - Question: Why does SVG exist?~~
* ~~[16:25​](https://youtu.be/UQ_kqGDM8A4?t=985) - Question: How does SVG relate to XML?~~
* [21:15​](https://youtu.be/UQ_kqGDM8A4?t=1275) - Intro to VizHub ...[[https://vizhub.com/](https://vizhub.com/)]
* ~~[24:23​](https://youtu.be/UQ_kqGDM8A4?t=1463) - Bare Bones HTML Page~~
* ~~[27:48​](https://youtu.be/UQ_kqGDM8A4?t=1668) - Working with HTML Locally~~
* ~~[29:41​](https://youtu.be/UQ_kqGDM8A4?t=1781) - Title & Description in VizHub~~
* [30:44​](https://youtu.be/UQ_kqGDM8A4?t=1844) - Creating an SVG Element ...`<svg> ... </svg>`
* [32:04](https://youtu.be/UQ_kqGDM8A4?t=1924)​ - SVG Circles ...`<circle cx="50" cy="50" r="50"></circle>`
* [33:19](https://youtu.be/UQ_kqGDM8A4?t=1999)​ - Question: Tags vs. Elements?
* [35:15](https://youtu.be/UQ_kqGDM8A4?t=2115)​ - Inspecting Elements with Chrome DevTools
* [36:52](https://youtu.be/UQ_kqGDM8A4?t=2212)​ - Manual DOM Manipulation with DevTools ...cf. JavaScript (D3, React, Vue, Svelte, JQuery) DOM manipulation
* [39:04​](https://youtu.be/UQ_kqGDM8A4?t=2344)​ - Adding Collaborators in VizHub
* [40:07​](https://youtu.be/UQ_kqGDM8A4?t=2407)​ - The "fill" attribute ...`fill="red"`
* [40:31​](https://youtu.be/UQ_kqGDM8A4?t=2431)​ - Using Prettier to auto-format code
* [41:23​](https://youtu.be/UQ_kqGDM8A4?t=2483)​ - The coordinate space of SVG ...(0,0) is top-left
* [42:26​](https://youtu.be/UQ_kqGDM8A4?t=2546)​ - SVG Width and Height ...`<svg width="960" height="500">`
* [43:19​](https://youtu.be/UQ_kqGDM8A4?t=2599)​ - SVG Rectangles ...`<rect ... />`
* [43:46​](https://youtu.be/UQ_kqGDM8A4?t=2626)​ - Setting "fill" to "none"
* [43:56​](https://youtu.be/UQ_kqGDM8A4?t=2636)​ - The "stroke" attribute
* [44:15​](https://youtu.be/UQ_kqGDM8A4?t=2655)​ - The "stroke-width" attribute
* [44:30​](https://youtu.be/UQ_kqGDM8A4?t=2670)​ - Z Ordering (layering) in SVG ...depends on their order in the SVG document
* [45:56​](https://youtu.be/UQ_kqGDM8A4?t=2756)​ - SVG Lines ...`<line x1="0" y1="0" x2="100" y2="100" stroke="navy"></line>`
* [46:57​](https://youtu.be/UQ_kqGDM8A4?t=2817)​ - Question: Shapes beyond width and height (clipping)?
* [48:45​](https://youtu.be/UQ_kqGDM8A4?t=2925)​ - SVG clip path concept
* [49:11​](https://youtu.be/UQ_kqGDM8A4?t=2951)​ - Debugging invalid HTML (no self-closing tags allows)
* ~~[51:33​](https://youtu.be/UQ_kqGDM8A4?t=3093)​ - Question: Differences between SVG lines and SVG paths?~~
* [53:00​](https://youtu.be/UQ_kqGDM8A4?t=3180)​ - SVG Paths and the "d" attribute ...`<path fill="none" d="M200,200L300,300L300,400" stroke="black" stroke-width=10"></path>` [M is move-to; L is line-to] [Path is used for line charts, area charts, geometries in maps (like countries), etc]
* [56:35​](https://youtu.be/UQ_kqGDM8A4?t=3395)​ - HTML Comments ...`<!--... -->`
* [57:04​](https://youtu.be/UQ_kqGDM8A4?t=3424)​ - Question: Can you make layers in SVG?
* [57:56​](https://youtu.be/UQ_kqGDM8A4?t=3476)​ - Question: Upper case vs. lower case in the "d" path attribute
* [59:16​](https://youtu.be/UQ_kqGDM8A4?t=3556)​ - Review of SVG path commands documentation ...[[MDN](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/d#path_commands)] ...but usually copy-paste from a tool
* [60:51](https://youtu.be/UQ_kqGDM8A4?t=3651) - Absolute vs. relative coordinates in SVG paths
* [62:01](https://youtu.be/UQ_kqGDM8A4?t=3721) - Question: How to communicate around this async? D3 Slack? VizHub Forum?] ...[[VizHub Forum topics for this course](https://vizhub.com/forum/c/get-it-right/10)]
* [63:51](https://youtu.be/UQ_kqGDM8A4?t=3831) - Exercise: Make something creative with SVG Shapes!]

---

#### 002 : "Pseudo Visualizations" (2021-03-13)
###### [_[forum](https://vizhub.com/forum/t/episode-2-pseudo-visualizations/138)_] - [_[slides (blocked)](https://docs.google.com/presentation/d/1QXHKfzkY6Qh-sy2iqxFS2_V-5KrmvwYumPTRG_YBgrs/)_] - [_myWorkings_] - [_myExercise_]

###### video [[1:11:18 edited](https://www.youtube.com/watch?v=UunbNeXhhaU)]; [[1:37:20 raw](https://www.youtube.com/watch?v=f5mYd-ufank)]



* [00:00](https://youtu.be/UunbNeXhhaU?t=0) -​ Intro to episode
* ~~[01:28​](https://youtu.be/UunbNeXhhaU?t=88) - Expanded mental model of SVG~~
* ~~[02:05​](https://youtu.be/UunbNeXhhaU?t=125) - Review of exercise submissions~~
* [02:55​](https://youtu.be/UunbNeXhhaU?t=175) - Animated hover transitions with SVG and CSS
* [06:23​](https://youtu.be/UunbNeXhhaU?t=383) - Removing default margins and scrollbar with CSS ...`<style>body {margin: 0; overflow: hidden;}</style>`
* ~~[08:02​](https://youtu.be/UunbNeXhhaU?t=482) - Review of more submissions~~
* [08:19​](https://youtu.be/UunbNeXhhaU?t=499) - Setting the height in VizHub
* [10:25​](https://youtu.be/UunbNeXhhaU?t=625) - Using classes with CSS
* [11:11​]() - Question: Difference between id and class with CSS
* [13:08​]() - Question: SVG as text?
* [14:38​]() - Tags vs. Elements in Documents vs. Dom
* [18:59​]() - Sunrise & sunset by Adil
* [20:13​]() - Radial gradients
* [25:26​]() - Bezier curves
* [27:56​]() - The animate tag in SVG
* [29:35​]() - Using Figma
* [31:31​]() - Bezier curve control points in Figma
* [32:38​]() - Workflows with sketching and mockups
* [34:37​]() - Creating a pseudo scatter plot
* [36:20​]() - Exporting SVG from Figma to HTML
* [37:43​]() - Question: is the xmlns attribute important?
* [39:55​]() - Creating a pseudo bar chart
* [40:23​]() - Real time collaboration in Figma
* [43:17​]() - Tricky Y values for bar charts
* [44:39​]() - Pseudo horizontal bar chart
* [45:26​]() - Adding text and selecting font in Figma
* [47:47]()​ - SVG Text and styling with CSS
* [51:13​]() - Using Google Fonts
* [54:38​]() - Question: Is CSS accessing the DOM or the document?
* [57:03​]() - Question: Does CSS or DOM have the final say (precedence)?
* [59:46​]() - Question: Is the fill attribute only for SVG elements?
* [62:17​]() - Pseudo line chart
* [62:52​]() - Line join options
* [63:07​]() - Line cap options
* [63:54​]() - Question what is the precedence of inline CSS?
* [68:58​]() - Exercise: Create pseudo visualization from a visualization taxonomy.

