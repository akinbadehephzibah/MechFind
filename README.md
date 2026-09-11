# MECH FIND

> **WE FIND. YOU DRIVE.**

MECH FIND is a digital mechanic-discovery platform created to make it
easier for car owners in and around Ojodu-Berger, Lagos to find the
right automotive specialist for their vehicle problem.

The project was developed by **Viewport Pod** as a seven-day
collaborative build. The idea grew from a simple but important
observation: mechanics may be easy to find, but identifying the **right
mechanic** for a specific problem, in the right location, with enough
information to make a confident decision, can be difficult.

## The Problem

When a vehicle develops a fault, the immediate challenge is not always
finding *someone* who can help. The harder challenge is finding someone
who is relevant to the actual problem and trustworthy enough to contact.

For car owners around Ojodu-Berger, the team identified concerns
including:

-   Difficulty knowing which type of mechanic is appropriate for a
    particular fault.
-   The possibility of misdiagnosing a vehicle problem.
-   Time lost while searching for suitable help.
-   Unclear or changing repair charges.
-   The stress of being stranded without a trusted mechanic.
-   Difficulty determining whether a mechanic is reliable before making
    contact.

MECH FIND was shaped around these realities, with a focus on
**discovery, relevance and trust**.

## The Solution

MECH FIND presents a straightforward way for users to discover mechanics
through relevant information such as:

-   Area of operation
-   Specialism
-   Verification status
-   Call-out fee
-   Availability and experience information
-   Customer feedback and trust-related information

The website also provides a mechanic directory and direct contact
options, alongside a booking form for users who need assistance in
Ojodu.

The core user journey identified during the project is:

**Search → View Profile → Contact → Completed Job**

## Website Experience

The current website brings together several sections designed around the
mechanic-discovery experience:

### Mechanic Directory

The directory presents verified local mechanics with information about
their specialisms, exact areas, call-out fees and relevant trust
information.

### Problem Section

The website explains the real-world problem from the perspective of car
owners, including the financial, time and trust-related costs associated
with finding the wrong mechanic.

### MECH FIND Trust

The trust section focuses on giving users more information before they
contact a mechanic, including relevant skills, verification information,
availability and customer feedback.

### Booking Form

Users can provide their name, phone number, location in Ojodu and a
description of their vehicle problem through the booking interface.

### Guide & FAQ

The FAQ section addresses practical questions around mechanic arrival
times, verification, payment and what happens when a customer is not
satisfied with the work performed.

## Project Development

MECH FIND was built through a structured seven-day process.

### Days 1--3: From Problem to Identity

The team began by discussing everyday problems and identifying mechanic
discovery as a problem worth investigating. Research then examined the
experiences of car owners and mechanics, existing discovery channels and
competing automotive platforms. The findings reinforced the central
insight:

> The problem is not simply finding a mechanic. It is finding the
> **right mechanic**.

On Day 3, the team gave the idea its identity and selected the name
**MECH FIND**. The project's visual direction followed, with the chosen
logo representing vehicles, mechanics and the act of finding the right
help.

### Day 4: Individual Pages

Development moved from planning into implementation. Team members worked
on assigned pages using HTML and CSS, with an emphasis on structure,
readability, consistency and the wider user experience.

### Day 5: Completion and Refinement

Individual pages were reviewed and refined. Team members corrected
issues, adjusted layouts and improved presentation before committing
their completed work to their individual GitHub accounts.

### Day 6: Integration

The separate contributions were brought together through GitHub. The
integration stage focused on combining independently developed pages
into a unified MECH FIND website without disrupting the overall
experience.

### Day 7: Launch and Submission

The completed website was prepared for submission and hosted on Vercel.
The project materials and README were finalized, marking the transition
from an initial concept to a completed digital product.

## Team

MECH FIND was developed by **Viewport Pod**, a ten-person team:

-   Great Marvney
-   AK
-   The Hijabi
-   Ajewole Israel
-   Victor
-   Wumight
-   Kinglify
-   Testimony
-   Aysha
-   Magnificent

The project demonstrates how different responsibilities and perspectives
can be combined around one shared objective.

## Team Responsibilities --- Development Stage

During the final development stage, responsibilities included:

  Team Member                  Responsibility
  ---------------------------- ------------------------
  Oluwaferanmi Oladapo         Landing Page
  Haibah Yusuff                The Problem Page
  Akinku Hephzibah             How It Works
  Oladimeji Olatomiwa          The Main Working Page
  Ojo Oluwasemilogo Emmanuel   The Detail Page
  Testimony Onilede            Trust and Verification
  Ajewole Israel               Request or Get Started
  Ede Comfort Salome           Guide and FAQ
  Aishat Bolanle Akinade       The Pod Page
  Iwegbu Victor                Contact and Site Shell

## Technology

The project uses a lightweight, dependency-free front-end stack:

-   **HTML** for page structure and content
-   **CSS** for layout, styling and all interactive behaviour
-   **GitHub** for version control and integration
-   **Vercel** for hosting the completed website

There is **no JavaScript anywhere in the site**. The mechanic directory
filter, the mobile navigation menu, the FAQ accordions and the two-way
form switcher on the Get Started page are all built with CSS alone,
using radio inputs, `:target`, `:checked` and CSS counters. The only
external request the site makes is to Google Fonts.

## Design

The visual design is taken directly from the MECH FIND logo. Nothing in
the palette is invented; every value is sampled from the mark itself.

| Role | Colour | Where it comes from |
| --- | --- | --- |
| Ink | `#17191C` | the dark outlines in the mark |
| Brand | `#A01020` | the red in the gear and the wrench |
| Brand dark | `#7A0C18` | hover and active states |
| Neutrals | `#6B7280` → `#E4E6E9` | the silver family of the car body |
| Surface | `#FFFFFF` / `#F6F7F8` | white ground |
| Success | `#107445` | semantic only — availability and confirmation |

Type is set in **Rajdhani** for headings, the wordmark and UI labels,
which echoes the squared italic letterforms of the logo, and **Inter**
for body copy.

The page background is white throughout, with no gradients, no glass
effects and no decorative shadows. Separation is carried by hairline
borders, generous spacing and a single alternating surface tone.

### Working with a light-on-dark logo

The MECH FIND mark is drawn in silver and white with red accents. It was
designed to sit on a dark background — which is why it is usually shown
on dark navy. Placed straight onto a white page, 29% of its pixels are
near-white and the car silhouette almost disappears.

The fix is the one used by any brand with a light logo: the page stays
white, and the logo is given a small **dark plate** to sit on. You can
see it in the header, the footer and the hero panel. This is a deliberate
brand container, not a dark theme and not a gradient.

Two logo files are in use:

-   `logo.png` — the full lockup, used large on the dark hero panel where
    its own wordmark is legible.
-   `logo-mark.png` — the emblem cropped out of the same file, used small
    in the header and footer beside a wordmark set in Rajdhani. At 26px
    tall the logo's built-in text would be unreadable, so it is set in
    type instead.

Neither file has been recoloured. `logo-mark.png` is a pixel-for-pixel
crop of `logo.png`.

## Project Structure

``` text
MechFind/
├── index.html                Home
├── problem.html              The Problem
├── how-it-works.html         How It Works
├── find.html                 Mechanic directory, with CSS-only filtering
├── trust.html                Trust & Verification
├── guide.html                Guide & FAQ
├── request.html              Get Started (car owner + mechanic forms)
├── pod.html                  The Pod
├── contact.html              Contact
├── thank-you.html            Form confirmation
├── 404.html                  Not found
│
├── mechanics/                Individual mechanic profiles
│   ├── mechanic-1.html
│   ├── …
│   └── mechanic-8.html
│
├── assets/
│   ├── css/
│   │   └── style.css         One shared stylesheet for every page
│   └── img/
│       ├── logo.png          Full logo lockup (the live mark)
│       ├── logo-mark.png     Emblem, cropped from logo.png
│       ├── logo-cyan.png     Alternate cyan lockup, kept for reference
│       └── logo-cyan-mark.png
│
├── _archive/                 Earlier single-file prototype
└── README.md
```

The site pages sit at the root so their URLs stay clean once hosted
(`/find`, `/contact`), while the eight mechanic profiles are grouped
under `mechanics/` and everything non-HTML lives under `assets/`.

All paths are relative, so the site works both when opened directly
from the file system and when served from a web host.

## How the CSS-only features work

**Directory filter (`find.html`).** Three groups of hidden radio inputs
sit before the results. A checked radio hides every card that does not
carry the matching class, so the service, location and tier filters
combine. The result count is a CSS counter: hidden cards generate no
box, so they are not counted.

**Result count.** `counter-reset` on the results grid, `counter-increment`
on each visible card, and `content: counter(shown)` on a following
sibling that flex `order` moves back above the list.

**Mobile menu.** A checkbox and its label, with the nav revealed by
`:checked`.

**FAQ accordions.** Native `<details>` and `<summary>` elements.

**Get Started tabs.** Driven by `:target`, so both the car-owner form and
the mechanic application have their own shareable URL
(`request.html#panel-mech`).

**Forms.** Standard HTML forms using native browser validation
(`required`, `type`, `pattern`). They submit by GET to `thank-you.html`,
which works on any static host with no backend.

## Responsive behaviour

The site is built mobile-first in the sense that it is tested at the
narrow end, not just the wide end. There are four breakpoints:

| Breakpoint | What changes |
| --- | --- |
| `1020px` | Navigation collapses into the dropdown menu; hero, profile and footer go to one column; team grid 5 → 3 |
| `860px` | Three- and four-column card grids → 2; directory results → 1; stat bar 4 → 2 |
| `620px` | All card grids → 1; form fields → 1 column; calendar 7 → 4; table headers wrap; buttons go full width in mechanic cards |
| `400px` | Gutters tighten; the brand tagline is dropped; stat bar → 1; calendar → 3; buttons go full width |

Rules that keep it honest at every size:

-   Grid tracks use `minmax(0, 1fr)`, not `1fr`. A bare `1fr` track refuses
    to shrink below its content, which is the most common cause of a page
    that scrolls sideways on a phone.
-   Images are `max-width: 100%`. Where a more specific rule sets a pixel
    `max-width`, it is paired with `width: 100%` so the smaller of the two
    wins.
-   Wide tables live inside `.table-scroll` (`overflow-x: auto`) so the
    table scrolls, never the page.
-   The header row uses `flex-wrap: nowrap` with a shrinkable brand, so
    the logo and the menu button always share one line.

**How it is verified.** A throwaway copy of every page is rendered at
320, 360, 414, 768, 1024 and 1280px with a measuring script injected, and
any element whose bounding box crosses the viewport edge is reported.
That is 114 renders, and all of them come back clean. The measuring
script exists only in the test copy --- the shipped site has no
JavaScript.

## Build Notes --- What Was Corrected, and Why

This section records what changed when the site was rebuilt, and the
reasoning behind each decision. The point is not the list of fixes but
the principles underneath them, which apply to any project.

### 1. Invalid HTML

The original files did not parse cleanly. Measured on the committed
`index.html` and the earlier single-file prototype:

| Problem | Count | Why it matters |
| --- | --- | --- |
| Missing `</html>` | 1 | The document never formally closes |
| Two `<main>` elements | 2 | `<main>` must appear once; screen readers use it to find the content |
| Four `<h1>` headings on one page | 4 | The heading outline is how assistive tech and search engines understand a page |
| Unquoted attributes: `<img src=logo.jpg alt= A Car Logo>` | 1 | `alt` silently becomes the single word `A` |
| More `</div>` than `<div>` | 39 vs 38 | The browser guesses where elements end, so layout drifts |
| `</header>` with no `<header>` | 10 vs 0 | Tags closed that were never opened |

**Principle.** Write markup that parses. Browsers will paper over broken
HTML, but each recovery is a guess, and guesses differ between browsers.
Every page here is now tag-balanced, which is checked automatically.

### 2. One long file became separate pages

The prototype was a single 1,348-line file with a JavaScript hash router
that hid and showed sections. It has been split into 19 real pages.

**Why.** Real URLs can be bookmarked, shared and indexed. `find.html` is
a page a browser can open on its own; `#find` handled by a script is not.
A visitor landing on a broken script sees a blank page. Separate files are
also far easier for ten people to work on without collisions.

### 3. All JavaScript removed

Three `<script>` blocks were replaced with CSS. The site now has none.

| Feature | Was | Now |
| --- | --- | --- |
| Mobile menu | Click handler toggling a class | Hidden checkbox + `:checked` |
| Directory filter | `filterMechanics()` rebuilding the DOM | Radio inputs + sibling selectors |
| Result count | Counted in JavaScript | CSS counters |
| FAQ accordions | Click handler toggling `.open` | Native `<details>` / `<summary>` |
| Form tabs | Click handler swapping panels | `:target` |
| Form submit | `preventDefault()` then show a div | Real submit to `thank-you.html` |

**Principle.** Reach for the platform before reaching for a script. The
native `<details>` element is keyboard accessible, searchable by the
browser's find-in-page, and works before any script loads. A hand-rolled
accordion usually is none of those things.

The one genuinely interesting trick is the result count. Elements hidden
with `display: none` generate no box, so they do not increment a CSS
counter. That means a counter naturally counts only the *visible* cards:

``` css
.results { counter-reset: shown; }
.mech    { counter-increment: shown; }
.result-count__n::after { content: counter(shown); }
```

### 4. Gradients, glass and the dark theme

The prototype used 26 gradients, a `backdrop-filter` blur, and a near-black
background. All are gone.

**Why.** Gradients and blur draw attention to the decoration rather than
the content, and they date quickly. Text on a gradient has a different
contrast ratio at each end, so it cannot be checked reliably. A flat white
ground with hairline borders is harder to make look impressive in a
screenshot and much easier to read for ten minutes.

**Principle.** Hierarchy should come from spacing, size and weight before
it comes from colour, and from colour before it comes from effects.

### 5. Colour was arbitrary; now it is derived

The prototype declared a crimson-and-charcoal palette while the logo in
use was cyan and green. The two fought each other.

**Principle.** Sample the palette from the brand asset. Every colour in
the table above exists somewhere in the logo file. When the logo changed,
only the token block changed --- roughly 30 lines --- and the whole site
followed, because no colour is hard-coded anywhere else.

### 6. 189 inline styles became design tokens

The prototype carried 189 `style="..."` attributes. Inline styles cannot
be reused, cannot be overridden without `!important`, and have to be
edited one at a time.

Everything is now a CSS custom property in one `:root` block, used by
class. Changing `--brand` recolours every button, link, eyebrow, focus
ring and active state at once.

### 7. Emoji were used as icons

27 card icons were emoji (🔍 💰 🛡️). Emoji render differently on every
operating system, cannot be recoloured, and are announced aloud by screen
readers ("magnifying glass tilted left").

They were replaced with a small inline SVG sprite. The icons inherit
`currentColor`, so they change colour with their surroundings, and they
carry `aria-hidden="true"` because the adjacent text already says what
they mean.

### 8. Accessibility

Added throughout:

-   A skip link, so keyboard users can jump past the navigation.
-   `:focus-visible` outlines on every interactive element.
-   Real `<label for="...">` on every form field, verified by script.
-   `alt` text on every image; decorative marks use `alt=""` so they are
    not announced twice.
-   `aria-current="page"` on the active navigation link.
-   One `<h1>` per page and a correct heading order.
-   `prefers-reduced-motion` honoured.

All text was checked against WCAG AA. Two greens initially measured 4.31:1
and 3.97:1 against their backgrounds; they were darkened to 5.02:1 and
5.19:1. The 4.5:1 threshold is the requirement for normal-size text.

**Principle.** Contrast is measurable. Do not judge it by eye --- compute
the ratio.

### 9. Forms that did nothing

The prototype's forms called `preventDefault()` and revealed a hidden
success message. Nothing was submitted and nothing was validated.

The forms now use native browser validation (`required`, `type="email"`,
`pattern`) and submit by GET to `thank-you.html`. On a static host with no
backend this is a genuinely working flow: the browser blocks an incomplete
form, and a real navigation confirms the submission.

### 10. Dead external assets

Eight images were loaded from a temporary `genspark.ai` URL that will stop
resolving. They were removed. The site's only external request is to
Google Fonts; every image is local.

**Principle.** If your page breaks when somebody else's server goes down,
that dependency belongs in your repository.

### 11. File organisation

Twenty-four files in one folder became a structure: pages at the root so
URLs stay clean, profiles grouped in `mechanics/`, everything non-HTML in
`assets/`. `logo.jpg` turned out to be a PNG with the wrong extension; its
artwork now lives correctly in `logo.png`.

### 12. What gets checked, every time

Each change was verified by script rather than by eye:

-   Every internal link and `src` resolves from its own folder.
-   Every page is tag-balanced.
-   Every `<img>` has `alt`; every `<label for>` points at a real field.
-   No `<script>`, no `on*` handler, no `gradient`, no `backdrop-filter`.
-   Every CSS class used in the HTML has a rule, and every rule is used.
-   Contrast ratios computed against WCAG AA.
-   No horizontal overflow on any page at six viewport widths.

**Principle.** If a rule matters, check it automatically. A rule you only
enforce by remembering is a rule you will eventually break.


## Project Vision

MECH FIND is built around a simple principle:

**Finding a mechanic should not be the end of the search. Finding the
right mechanic should be the goal.**

By bringing mechanic relevance, location, verification and contact
information closer together, the project explores a more transparent
approach to automotive service discovery for car owners and mechanics.

## Acknowledgement

MECH FIND is the result of seven days of research, planning, design,
development, review, version control and integration.

The finished product reflects the combined effort of the Viewport Pod
team and the shared responsibility required to turn an idea into a
working digital product.

------------------------------------------------------------------------

**MECH FIND --- WE FIND. YOU DRIVE.**
