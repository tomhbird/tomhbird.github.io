# tomhbird.github.io

A personal article built in Quarto and hosted via GitHub Pages, combining two things I care about: writing honestly about life with Type 1 diabetes, and building things cleanly in code.

What it is:
I've Just Travelled the World as a Type 1 Diabetic. Here Are 10 Things You Should Know. It's a long-form travel piece covering eight months across the US, Australia, New Zealand, Thailand, Vietnam, Japan, and South Korea. It's written from personal experience and aimed at anyone with Type 1 diabetes who wants to travel but isn't sure where to start.
The article is also a portfolio piece. I wanted to demonstrate what I can do with Quarto beyond a standard rendered document, so the design, layout, and interactivity were all built deliberately rather than left to defaults.

What it's built with:
Quarto for document structure, rendering, and the three-column layout.
Custom CSS for typography, the editorial margin column, callout styling, pull quotes, fact boxes, and the collapsible resource section
GitHub Pages for hosting.
ImageMagick for batch image compression via the terminal.
R / RStudio as the development environment.

Some things worth noting:
The right margin runs the full length of the article and is populated with photos, pull quotes, and fact boxes, all managed through Quarto's column-  margin system. Getting consistent spacing and flow out of that system took some work.
The resource section at the bottom uses native HTML <details> and <summary> elements styled entirely in CSS, with no JavaScript. It expands by country and uses a card grid layout that adapts to screen width.
Photos are compressed using ImageMagick and served with Quarto's built-in lightbox feature, which allows full-screen viewing with captions on click.

Live site
tomhbird.github.io
