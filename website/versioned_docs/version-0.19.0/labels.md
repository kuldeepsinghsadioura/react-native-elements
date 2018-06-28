---
id: version-0.19.0-labels
title: Label Guide
original_id: labels
---

<style>
.label {
  font-size: 16px;
  font-weight: 600;
  line-height: 2;
  color: #ffffff;
  padding: 8px;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(27, 31, 35, 0.12);
}
.label.bug {
  background-color: #ee0701;
}
.label.bug-fix {
  background-color: #b60205;
}
.label.help {
  background-color: #128A0C;
}
.label.question {
  background-color: #cc317c;
}
.label.reply {
  background-color: #0052cc;
}
.label.docs {
  color: #000;
  background-color: #1d86b7;
}
.label.enhancement {
  background-color: #0052cc;
}
.label.first {
  background-color: #464EBA;
}
.label.v1 {
  background-color: #F3CB46;
  color: #000;
}
.label.fixed {
  background-color: #CEE3CE;
  color: #000;
}
.label.response {
  background-color: #d93f0b;
}
.label.new {
  background-color: #0e8a16;
}
.label.release {
  background-color: #5319e7;
}
.label.thoughts {
  background-color: #fbca04;
  color: #000;
}
.label.types {
  background-color: #e4b4f7;
  color: #000;
}
.label.wip {
  background-color: #1d76db;
}
.label.pr-submitted {
  background-color: #7621a8;
}
.label.tooling {
  background-color: #054c70;
}
</style>

This page explains how we use labels throughout the repo to tag issues and pull
requests. Knowing our label structure will help you to be able to triage issues
easier and know how to contribute to open issues and pull requests.

## Issues

<a class="label first" href="https://github.com/react-native-training/react-native-elements/labels/👶%20Good%20First%20Issue" target="_blank">
  👶 Good First Issue
</a>

A well documented issue explaining the tasks needed to accomplish it, that
should be suitable for a new contributor to the project

<a class="label bug" href="https://github.com/react-native-training/react-native-elements/labels/%3Aboom%3A%20%20Bug" target="_blank">
  💥 Bug
</a>

The problem reported has been tested and the effect replicated by a maintainer

<a class="label help" href="https://github.com/react-native-training/react-native-elements/labels/🔦%20Help%20Wanted" target="_blank">
  🔦 Help Wanted
</a>

My code is broken and I don't know why. I need help!

<a class="label question" href="https://github.com/react-native-training/react-native-elements/labels/❔Question" target="_blank">
  ❔ Question
</a>

Seeking information that doesn't include code. e.g “can I use react navigation
with react-native-elements?”

<a class="label reply" href="https://github.com/react-native-training/react-native-elements/labels/⏳Awaiting%20Reply" target="_blank">
  ⏳ Awaiting Reply
</a>

Maintainer has replied to the user and there's been no response. After 2 weeks
any issues with this label should be closed as inactive.

<a class="label fixed" href="https://github.com/react-native-training/react-native-elements/labels/✅%20Fixed%20-%20Next%20Release" target="_blank">
  ✅ Fixed - Next Release
</a>

Issue or feature has been implemented and will be apart of the next npm release

<a class="label pr-submitted" href="https://github.com/react-native-training/react-native-elements/labels/📥%20PR%20Submitted" target="_blank">
  📥 PR Submitted
</a>

A pull request has been submitted to resolve this issue or implement this
feature

---

## Pull Requests

<a class="label bug-fix" href="https://github.com/react-native-training/react-native-elements/labels/💊%20Bug%20Fix" target="_blank">
  💊 Bug Fix
</a>

Fixes a bug reported in an issue

<a class="label response" href="https://github.com/react-native-training/react-native-elements/labels/📞%20Needs%20Response%20from%20Author" target="_blank">
  📞 Needs Response from Author
</a>

Maintainer has left feedback on the pull request and it needs a response or a
revision made from the author

<a class="label release" href="https://github.com/react-native-training/react-native-elements/labels/📦%20RELEASE" target="_blank">
  📦 RELEASE
</a>

Pull request for the next version to be released

<a class="label wip" href="https://github.com/react-native-training/react-native-elements/labels/👨%E2%80%8D💻WIP" target="_blank">
  👨‍💻 WIP
</a>

Work In Progress. Author is still working on this PR and it shouldn't be merged
or reviewed as yet

---

## Both

<a class="label thoughts" href="https://github.com/react-native-training/react-native-elements/labels/🤔Thoughts%3F" target="_blank">
  🤔 Thoughts?
</a>

Requires discussion for decisions that are unsure

<a class="label tooling" href="https://github.com/react-native-training/react-native-elements/labels/🔧%20Tooling" target="_blank">
  🔧 Tooling
</a>

Issues or pull requests that affect tooling e.g tests, npm, ci

<a class="label docs" href="https://github.com/react-native-training/react-native-elements/labels/%3Abook%3A%20Docs" target="_blank">
  📖 Docs
</a>

Issues or pull requests surrounding documentation

<a class="label enhancement" href="https://github.com/react-native-training/react-native-elements/labels/✨Enhancement" target="_blank">
  ✨ Enhancement
</a>

Suggests and implements improvements or additions to existing components

<a class="label new" href="https://github.com/react-native-training/react-native-elements/labels/💡New%20Component" target="_blank">
  💡 New Component
</a>

Suggests or implements a new component

<a class="label types" href="https://github.com/react-native-training/react-native-elements/labels/🗂%20Types" target="_blank">
  🗂 Types
</a>

Issues and pull requests around typescript definitions

<a class="label v1" href="https://github.com/react-native-training/react-native-elements/labels/🥇v1" target="_blank">
  🥇 v1
</a>

Temporary tag associated with the release of version 1.0.0
