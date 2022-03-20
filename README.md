<h1 id="topBanner"align="center">
  <img src=".github/images/GitHubREADMEBanner.png" alt="GitHub README banner"/>
</h1>
<h2 align="center">
  <img src=".github/images/GitHubREADMETagline.png" alt="GitHub README tagline">
</h2>
<div align="center">

[![](https://img.shields.io/github/v/tag/maxheyn/readme-reference?color=41aee7&label=latest%20release&logo=Github)](https://github.com/maxheyn/readme-reference/releases/latest) [![](https://img.shields.io/github/last-commit/maxheyn/readme-reference?color=41aee7&label=latest%20commit&logo=Github)](https://github.com/maxheyn/readme-reference/commits/main) [![](https://img.shields.io/github/issues/maxheyn/readme-reference?color=41aee7&logo=Github)](https://github.com/maxheyn/readme-reference/issues)

[Releases][release]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Features](#features)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Commands](#commands)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Screenshots](#screenshots)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Planned](#planned)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Issues][issues]

This section is what I call **The Pitch**. It is centered and directly below the banner and tagline. It is intended to be used to provide a quick overview of the project and its goals, similar to an abstract or summary. This should be kept short and concise, one paragraph at the most. You should describe what your project is, name (do not describe) some key features, and provide navigation links to important sections of the README and the project.
</div>

<h2 id="features" align="center">  
  <img src=".github/images/Features.png" alt="features header">
</h2>

This is the **Features** section. It is intended to allow the reader to quickly understand the key features of your project. You should not include any code or other technical information here, mainly a very high-level overview of the feature. Do not center this section. Try to avoid complete sentences; short blurbs that you may see as section headers are best, but it may depend on your goal. Include navigation links to the sections mentioned here, even if the navigation link already exists in **The Pitch** section of the README. If you are using this as a template, feel free to delete this paragraph and edit the rest of this section.

This README template/guide has many features/sections, some of the key ones to highlight are...

- Generic (and biased) advice on how you can use your README to highlight your project
    - Why is this important?
    - How to define sections
    - Images as headers
    - Images as a visual aid
    - Videos
- Formatting "hacks" you can use to make your README look better
    - GitHub Flavored Markdown
    - Navigation bar
    - Code blocks
- README editing made simpler
- Sample READMEs which you can use as a starting point or reference

You can add a small blurb here if you would like. Typically I include a hyperlink to an external download here or to my latest GitHub release. You can also just leave this blurb blank and continue on to the next section.

<h2 id="advice" align="center">  
  <img src=".github/images/Advice.png" alt="advice header">
</h2>

This is our first features subsection. This is where you will go into detail for all of the features you are highlighting in the first bullet point of the **Features** section. I tend to make a banner for each subsection, and then use typical html headers to describe the features in further detail. Using too many banners to separate sections can cause visual clutter.

<h2 id="why">
    Why is this important?
</h2>

Why is this important? Why should I put in all of this effort? What does this achieve? These are all important questions to be asking yourself, and hopefully I can provide some answers here.

There are multiple reasons why you may want to create a thorough GitHub README. The following reasons are numbered for your convenience, but the numbering does not indicate levels of importance.

1. You want to make sure that your project is well-documented, easy to use, and easy to understand.
2. You want to make sure that your project is easy to contribute to, if having contributors is important to you.
3. You want to grab the attention of anyone who is browsing your GitHub and leave them wanting to know more about your project.

The first and third reasons are fairly connected but not necesarilly the same thing. You can create a well documented README that is not necesarilly attention grabbing. Our goal here is to make sure that readers can easily find important technical information about your project, yet also provide a pleasant reading experience for someone who is just browsing to learn more about your projects (*like a future Employer, wink wink*). You want your README to **STAND OUT** from the rest of the crowd to set yourself apart and make a good impression. When I see a README that is well made, I also assume (whether it is correct or not), that the code itself is also well made (or at least has a good chance of being so). That is the impression that you want to to give off after someone views your README.

If your project is intended to be contributed to by others, you will also want to have a pleasant README as a way of advertising that your project is worth being contributed to. After all, would you rather contribute to the project that looks professional and is well-documented, or contribute to the project has little to no information about it? Your preferences may vary, but I would admit that the better a README looks to me, the more willing I am to consider contributing to your project.


<h2 id="sectioning">
    Defining Sections
</h2>

Your README needs sections, so how do you decide what sections to include, and what do you include in each section? Luckily, it's pretty simple if you already set up your **Features** section from above. Take each top level bullet point and use it as a section header, and then use the child bullet points as the section content.

There are a few sections that I always try to include, regardless of the type of project. These are:
- **The Header**
- **The Pitch**
- **Features**
- **Feedback**

I will not describe them here, as they are already described in their respective sections, aside from **The Header**. **The Header** is the main banner of your project and should be at the very top of your README. It replaces the default #project-title that is included in the default README that GitHub generates for your project, if you decide to generate one.

I tend to create section header images for top level bullet points from **Features**, and then use HTML H2 headings for the child bullet points.

Each section header should be wrapped in a `<h2>` tag with an id attribute, so that we can link to it from other sections. For example, the section header for this section looks like this:

```html
<h2 id="sectioning">
    Defining Sections
</h2>
```
This allows you to link to this section by using the id attribute, like this:
`[Defining Sections](#sectioning)` → [Defining Sections](#sectioning)

<h2 id="visuals">
    All About Visuals
</h2>

Visuals are an AMAZING way to make your README stand out. I tend to use images as section headers, and try to use images as a visual aid to the section content whenever possible. However, it is also possible to overdo this and use too many images, which ends up as visual clutter. Feedback is crucial and you should always ask someone to read over your README and get their thoughts on it, especially when it comes to visual clutter.

<h4 id="banners">
    Banners
</h1>

Banners are more of a creative expression than anything, but I try to follow a few guidelines when making my banners.

- A Banner should be at least 300px wide
    - This is a good rule of thumb, but it is not a hard rule.
- A Banner should be either 8:3, 4:1, or 3:1 aspect ratio
    - Personally, I believe 8:3 is fantastic for your header banner, and 4:1 or 3:1 are great for section banners, depending on the font and font size you use.
- Text on a banner should be easy to read
- Colors should not be harsh
- Ensure that the banner looks fine in both dark and light themes

I usually create my banners in Photoshop, but any image editor should work. Here are some tools you can use:
- Adobe Photoshop
- Adobe Illustrator
- GIMP
- MS Paint (*for the brave*)



<h2 id="hacks" align="center">  
  <img src=".github/images/FormattingHacks.png" alt="hacks header">
</h2>

<h2 id="sectioning">
    GitHub Flavored Markdown
</h2>

sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text 

<h2 id="sectioning">
    Navigation Links
</h2>

sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text 

<h2 id="sectioning">
    Code Blocks
</h2>

sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text 

<h2 id="tips" align="center">  
  <img src=".github/images/Advice.png" alt="tips header">
</h2>

sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text 

<h2 id="samples" align="center">  
  <img src=".github/images/Samples.png" alt="samples header">
</h2>

sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text sample text 

<h2 id="feedback" align="center">
  <a href="https://github.com/maxheyn/readme-reference/issues">
  <img src=".github/images/SubmitFeedback.png" alt="feedback header">
  </a>
</h2>

<div align="center">

Have a suggestion for some options, or want to report a bug? Open an [issue][issues]!

[Back to Top](#topBanner)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Authors](https://github.com/maxheyn/readme-reference/graphs/contributors)

</div>

[release]:https://github.com/maxheyn/readme-reference/releases/latest "Latest Release (external link)"
[issues]:https://github.com/maxheyn/readme-reference/issues "Issues (external link)"

*This repository exists to provide a loose guide or reference for creating an aesthetically pleasing and noteworthy GitHub README for your project. This is **NOT** a guide for GitHub PROFILE READMEs. Do not consider this guide as one to learn best practices, but rather as one that will get you started on the path to improving your documentation skills and making your project stand out from the crowd. Please also note that this is how I personally like to style my GitHub READMEs, and you may have other preferences - feel free to use this template and customize it to your own liking.*