---
name: Bug report
about: Create a report to help us improve
title: "[ BUG ]"
labels: bug
assignees: georgeosheanz

---

### Does your log mention database corruption?

If your Web Application log reports panics because of database corruption it is
most likely a fault with your system's storage or memory. Affected log
entries will contain lines starting with `panic: leveldb`. You will need to
delete the index database to clear this, by running `website
-reset-database`.

---------------------------------------------------
### Include required information

Please be sure to include at least:

 - which version of Web Application and what operating system you are using
 - browser and version, if applicable
 - what happened,
 - what you expected to happen instead, and
 - any steps to reproduce the problem.
 - screenshots to help explain the problem
 - any other context about the problem
