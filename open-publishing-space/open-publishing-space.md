[← Open Textbooks and Guides](open-publishing-space/README.md)

# Open Publishing Space 2

<small>Part 2 of 5</small>

A free, open-source website starter for sharing **web-first open textbooks and guides** alongside a blog and other pages, built on the Grav 2 CMS. And being web-first, the website is each guide's main edition – easy to read on any device, with print and Markdown versions from the same pages.

- Guides with section cards, reading progress, Learning Objectives, OER attribution, search and **Keep My Place** (come back to this guide's home page to continue where you left off, even partway down a page)
- One site can hold several guides, each with a card on a Guides page and its own pages in the menu (like this guide's Topics and Resources) – plus site pages like [About](about.md)
- Diagrams and math written as plain text, with the free [Mermaid](https://hibbittsdesign.org/cost-free-grav-projects.html#mermaid-plugin) and [LaTeX Math](https://hibbittsdesign.org/cost-free-grav-projects.html#latex-math-plugin) plugins – like $E = mc^2$, or this diagram:

```mermaid
flowchart LR
  A[Read] --> B[Move] --> C[Reuse]
```

Pages **embed in Canvas, Moodle or Brightspace** – just add `?embedded=true` to a page's address.

Editing works **in the browser** with Grav's Admin 2 panel, or as Markdown files with any editor or **via Git** – with no database needed, on most PHP web hosts.

![An Open Publishing Space guide home page, with its cover, Start Reading button, search box and a card for each section](open-publishing-space-guide.jpg)

*A guide home page, from the Open Publishing Space demo*

![A page of this guide on a phone, twice: at the top of the page with the site header, and scrolled down with the header out of the way, both with a Previous and Next bar at the bottom of the screen](open-publishing-space-phone.webp)

*A page of this guide on a phone: the header slides away as you read, and Previous/Next stay at the bottom*

See the demo: [one guide](https://demo.hibbittsdesign.org/grav-open-publishing-quark2/) · [several guides](https://demo.hibbittsdesign.org/grav-open-publishing-quark2-guides/) · [This page, embedded](https://read-move-reuse.hibbittsdesign.org/open-publishing-space/open-publishing-space?embedded=true)

Try the Admin 2 panel: [read-only demo](https://try.hibbittsdesign.org/grav-skeleton-open-publishing-space/admin) (the sign-in details are on its sign-in screen). Once signed in, the project's ReadMe is in the Admin sidebar, thanks to the [Admin2 Site ReadMe plugin](https://hibbittsdesign.org/cost-free-grav-projects.html#admin2-site-readme-plugin).

> [!NOTE]
> Want to jump right in? Download [Open Publishing Space](https://getgrav.org/downloads/skeletons#open-publishing-space-site) or try the [demo](https://demo.hibbittsdesign.org/grav-open-publishing-quark2/).
