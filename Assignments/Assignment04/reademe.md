# Assignment 04 - Bootstrap Components

Author: Jacob Greenberger

This project builds on the CSC 235 Bootstrap sample
(https://github.com/connorj4/CSC235-sample). The base sample already used a
`navbar` with a `dropdown`, so for this assignment I added two additional,
different Bootstrap components to `index.html`: **Card** and **Accordion**.

## Components used

### 1. Card
Added a "Course Topics" section with three `card` components (HTML, CSS, and
Bootstrap), each with an image, a title, a short description, and a button.

I chose the Card component because it is a clean, reusable way to group a
related image, heading, and short block of text into one self-contained
unit. The existing sample only had one large block of body text next to a
single image, so Cards let me break that same kind of content (a topic, a
picture, and a short description) into smaller, scannable pieces that are
easy to scan and that reflow nicely on different screen sizes using
Bootstrap's grid classes (`col-md-4`).

### 2. Accordion
Added a "Frequently Asked Questions" section using the `accordion` component
with three collapsible questions and answers.

I chose the Accordion component because it is an interactive element (unlike
Card, which is mostly static), and the assignment page didn't have any
collapsible/interactive content yet. An accordion is a good fit for FAQ-style
content because it lets a visitor see all the questions at a glance without
being overwhelmed by all the answers at once, and it demonstrates Bootstrap's
JavaScript-driven components (`data-bs-toggle="collapse"`) working alongside
the `bootstrap.bundle.min.js` script that was already linked in the sample.

## Why these two together
Card and Accordion complement each other: Card is a static content container
best for showcasing items side by side, while Accordion is an interactive
component best for progressively revealing content. Using one of each shows
both a layout-focused component and a behavior-focused component from the
Bootstrap library, rather than two components that do essentially the same
job.
