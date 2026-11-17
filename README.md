# .github

thechelsuk's default community health files. GitHub uses them for every repo
of thechelsuk's that doesn't have its own copy.

- `.github/ISSUE_TEMPLATE/`: four issue forms (Bug report, Feature request,
  Question, Feedback), labelled `bug`, `enhancement`, `question` and
  `feedback`. Blank issues are off, and the chooser links to the
  ask-me-anything form (thechels.uk/c/ama) and GitHub Sponsors (a one-off $10
  Feature request bump).
- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md` and the pull request
  template.

New issues are labelled, assigned and thanked by the `new-issue.yml` workflow in
[thechelsuk/workflows](https://github.com/thechelsuk/workflows), which each
repo calls. It reads these forms' headings, so keep the field labels in step
with it.

## Repos with their own forms

A repo's own `.github/ISSUE_TEMPLATE/` replaces these completely. These repos
keep copies of the four forms next to their own, so update them when these
change:

- `uk.thechels`: its content forms (add a book, film, post and so on).
- `uk.nuchronic`: its feed submission and removal forms.
- `uk.cheltenham-od`: its own set, reviewed separately.
