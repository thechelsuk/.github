# Accessibility

This is the accessibility file for every thechelsuk repository: the apps, websites, tools and templates I make. It says how to report a barrier, what I already know is broken, what I aim for and what's checked. A repository with its own `ACCESSIBILITY.md` replaces this one.

## Report a barrier

If something I've built doesn't work for you, tell me. You don't need to quote a guideline or know the technical cause. Say what you were trying to do, which page, app or repository it was, and what went wrong. If you use assistive technology, you can say which, but you don't have to.

- Open an issue in the repository, using the **Bug report** form.
- If you'd rather not use GitHub, choose **Prefer to ask directly?** when you open an issue, or use [the contact form on thechels.uk](https://thechels.uk/c/ama). It doesn't need a GitHub account.
- If a page on thechels.uk is hard to read, add `.md` to its address to get the plain Markdown.

What happens next: I'll reply within 10 days. Fixes come as soon as my health allows, and I'll say if something can't be fixed.

I'm one person, so mistakes happen. Telling me is always welcome.

## What I already know is broken

Open accessibility problems are tracked as issues with the `accessibility` label: [see the open accessibility issues](https://github.com/search?q=user%3Athechelsuk+label%3Aaccessibility+is%3Aissue+is%3Aopen&type=issues).

Known from the Cheltenham Open Data statement:

- The interactive maps are harder to use with a keyboard or screen reader. Everything on a map is also listed in the table below it.
- Some long tables scroll sideways on small screens.
- Some linked documents, such as PDFs from other organisations, are outside my control and may not be accessible.

Nothing I make has been audited by anyone outside the project.

## What I aim for

I aim to meet the [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/) 2.2 at level AA. That's a target, not a claim that everything meets it.

Apps follow Apple's Human Interface Guidelines. VoiceOver and Dynamic Type aren't yet tested on every app. Each app's App Store page lists the accessibility features it supports, such as dark mode, larger text and reduced motion.

## What's checked

These run on each change and report failures. None of them blocks a change automatically, because I work on the main branch.

- Linters check page structure, text and style sheets on Cheltenham Open Data.
- Lighthouse runs on pull requests for thechels.uk.
- Code tests and a link checker run on a schedule for both sites.

Done by hand on the websites:

- Pages are run through [TPGI's ARC Toolkit](https://www.tpgi.com/arc-platform/arc-toolkit/) and [Google's Lighthouse](https://developer.chrome.com/docs/lighthouse/).
- Pages are tried in different browsers, at different zoom levels and font sizes, on physical devices and at different screen sizes.
- Every page has a "skip to main content" link and light and dark themes, and is built to work with a keyboard.
- Colour is never the only way information is shown. Charts use a palette chosen to stay readable with colour blindness, and statuses are also given in words.
- Data shown on a map or chart is also given in a table you can sort and read with a screen reader.

## If you contribute

- Use real headings, links and buttons, not styled text.
- Give every image a text description, or an empty one if it's decoration.
- Keep text readable in light and dark themes, and never use colour alone to carry meaning.
- Make sure everything works with a keyboard.
- Say in your pull request what you checked.

## Statements for each site

- [thechels.uk](https://thechels.uk/accessibility)
- [Cheltenham Open Data](https://cheltenham-od.uk/accessibility)
- Apps: the accessibility section of each app's App Store page.

Last reviewed: 22 November 2026.
