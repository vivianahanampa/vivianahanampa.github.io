# vivianahanampa.github.io

Personal site covering research and industry machine learning work. Short
intro with a round photo, then Research and Industry sections listing
projects with a thumbnail each; the most important ones are highlighted, and
every project has a "Read more" panel with the longer story. Forest-green
palette on a soft sage-grey background, with a matching dark mode.

Plain HTML and CSS, no build step. `index.html` is the whole site; images live
in `assets/` (see `assets/README.md`).

Served at https://vivianahanampa.github.io

## Editing

Sections, in order: intro (with research interests), Research (projects,
Also in progress), Industry (projects, Other projects),
Experience, Skills, Education and honors (with certifications, leadership).
To lead with industry work instead, swap the `research` and `industry`
sections.

To add a project, copy an `<article class="item">` block. Add `hl` to its
class (`class="item hl"`) to give it the highlighted background. The longer
write-up goes inside its `<details class="more">` panel as `<h4>` headings
and paragraphs; the page opens every panel when printed.

Facts come from the latest base CV (`~/Get a job/CVs-base/Viviana-Hanampa.pdf`,
Oct 26 2026). Numbers marked as disputed in `Viviana_Hanampa_Projects.txt`
are left off.

One thing is waiting on you, marked with an HTML comment: the **CV link** in
the intro. Add a resume *without GPA* as `assets/Viviana_Hanampa_Resume.pdf`,
then uncomment the link.
