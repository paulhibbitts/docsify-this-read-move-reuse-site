[← Docsify for Open Education and Publishing](docsify/README.md)

# Moving to Grav, and Back

<small>Part 4 of 5</small>

**When a full site helps:** editing in the browser with an admin panel, a search box across all your guides, Keep My Place for returning readers, or a blog alongside – that's when a free [Grav](https://getgrav.org/) website starter fits better. It needs a PHP web host, but still no database.

```mermaid
flowchart LR
  accTitle: Moving between Docsify and Grav
  accDescr: The same Markdown files move from Docsify-This to a Docsify Starter Kit, and between either of them and a Grav site with a free converter, in both directions.
  A[Docsify-This] -- same files --> B[Docsify Starter Kit]
  A <-- converter --> C[Grav site]
  B <-- converter --> C
```

- **[Open Publishing Course Hub Converter](https://open-publishing-course-hub-converter.hibbittsdesign.org/)** – moves guides or a course between Docsify and Grav Open Publishing Space or Open Course Hub, in either direction, with the same Markdown
- **[Docsify Common Cartridge Converter](https://docsify-common-cartridge-converter.hibbittsdesign.org/)** – turns a Canvas, Moodle or Brightspace course export into Markdown pages for Docsify
- **[Pressbooks Converter](https://pressbooks-converter.hibbittsdesign.org/)** – its Standard Markdown option suits a Docsify site too

**A way back:** moving to Grav doesn't lock you in – the converter moves your guides or course back to Docsify whenever you want.

For the Grav side, see [Open Textbooks, Guides and Courses](guide/README.md) or [Grav 2 for Open Education and Publishing](grav-2/README.md).

Example: [a course on Docsify-This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-open-course-hub-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&loadFooter=_footer.md&pagination=true&searchbox=true&name=CPT-363), converted from the Open Course Hub demo
