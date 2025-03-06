# BPCA Website

The BPCA SRC website is accessible at [https://bpcsrc.org/](https://bpcsrc.org/).

## Development Notes

This repository is a "vanilla" website; in other words, it consists of purely HTML, CSS, and JS. There is no framework (e.g. React, Svelte, etc.) used for this site. 

As such, all pages are available as standard `.html` files and generally should resemble a regular "vanilla" web page. Note that this repository was cloned from a previously purchased template (of which, the template files are still here), but has been heavily modified. 

The template is purely for UI; there is little if any functionality (in terms of frontend or backend scripts) from the template that was modified nor required for use on this website. All files use [Tailwind CSS](https://tailwindcss.com/).

This website does not read from any database such as Firebase. You may instead be looking for the curriculum viewer repo, accessible at [https://github.com/bpcsrc-curriculum/bpcsrc-curriculum](https://github.com/bpcsrc-curriculum/bpcsrc-curriculum).

Since the website is entirely static and does not use a parser or builder such as Jekyll, **the footer and header for all pages are not "linked", and all pages must be edited if you change the footer and header for 1 page**.

## Running the Website

As the website is not reliant on a framework or web engine, simply clone the repository to your local machine and open `index.html`.

**However**, since the website is entirely static, changes do not render properly on the browser, viewed locally or in production, unless the cache is cleared. To do so locally for developing, use the hotkey "Ctrl + R". Methods to automatically update the cache when viewed in production (such as cache-busting) have yet to be implemented.

## Deployment

A GitHub action is linked to this repository that automatically deploys the website.

## Pages

Although pages are generally simple enough to understand through brief viewings, for clarity we describe the pages as the following:

### about-src.html

The About page describes the mission statement of the BPCA SRC foundation. 

### assessment.html

This page is blank.

### calendar.html

The Calendar page contains a quarterly schedule of BPCA SRC foundation plans.

### faculty-learning-community.html

The Faculty Learning Community page contains links to materials used in BPCA SRC workshops.

### index.html

The home page.

### news.html

Articles relating to news surrounding the BPCA SRC association. These are currently all placeholders. 

### partners.html

The Partners page contains a rotating array of colleges involved in the BPCA SRC foundation. Each item in the array contains a hyperlink to the college's home page.

### personell.html

The Personell page is a gallery of all professors and staff working for the BPCA SRC foundation.