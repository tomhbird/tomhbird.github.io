A personal article built in Quarto and hosted via GitHub Pages, combining two things I care about: writing honestly about life with Type 1 diabetes, and building things cleanly in code.

What it is:

I've Just Travelled the World as a Type 1 Diabetic. Here Are 10 Things You Should Know. It's a long-form travel piece covering eight months across the US, Australia, New Zealand, Thailand, Vietnam, Japan, and South Korea. Written from personal experience and aimed at anyone with Type 1 diabetes who wants to travel but isn't sure where to start.

The article is also a portfolio piece. I wanted to demonstrate what I can do with Quarto beyond a standard rendered document, so the design, layout, and interactivity were all built deliberately rather than left to defaults.

What it's built with:

Quarto for document structure, rendering, and the three-column layout. Custom CSS for typography, the editorial margin column, callout styling, pull quotes, fact boxes, mobile responsiveness, and the collapsible resource section. JavaScript for the interactive route map and mobile photo carousel. GitHub Pages for hosting. ImageMagick for batch image compression via the terminal. R and RStudio as the development environment.

What it includes:

The main article with 10 sections, an intro box, a closing section, callout tips, pull quotes, and fact boxes throughout. A right margin column running the full length of the article, populated with 40 plus photos, all with lightbox captions and accessibility alt text. A mobile-responsive layout with a swipeable photo carousel that replaces the margin column on smaller screens. An interactive route map at tomhbird.github.io/map built with Leaflet.js, showing the full eight month route colour coded by transport mode, with hover tooltips and a country by country diabetes travel guide for all seven countries visited. A downloadable pre-flight diabetes checklist in PDF format. A collapsible country by country resource section at the bottom built with native HTML details and summary elements styled in CSS with no JavaScript.

Some things worth noting:

The right margin column is managed through Quarto's column-margin system. Getting consistent spacing and flow out of that system across a long-form article took considerable experimentation, and all margin content is consolidated into a single block at the top of the QMD to avoid the overflow and misalignment issues that arise when individual blocks are placed inline. On mobile, the column is hidden entirely and replaced with a purpose-built swipeable carousel. The interactive map is a separate Quarto page using Leaflet.js with real GPS coordinates for every stop on the route, accurate transport mode colour coding, and popup country guides built from first-hand research. The PDF checklist was generated programmatically using ReportLab in Python. OG meta tags are included in the YAML front matter for proper LinkedIn and WhatsApp link previews.
Live site: tomhbird.github.io