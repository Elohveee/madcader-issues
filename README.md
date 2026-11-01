<p align="center">
  <a href="https://madcader.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.svg">
      <img src="assets/wordmark-light.svg" alt="MadCADer" width="360">
    </picture>
  </a>
</p>

<p align="center">
  <strong>Design aluminum-extrusion frames in your browser.</strong><br>
  This is where MadCADer's bug reports, feature ideas and roadmap live in public.
</p>

<p align="center">
  <a href="https://github.com/Elohveee/madcader-issues/issues?q=is%3Aissue+is%3Aopen+label%3Abug"><img alt="Open bugs" src="https://img.shields.io/github/issues/Elohveee/madcader-issues/bug?label=open%20bugs&color=d73a4a"></a>
  <a href="https://github.com/Elohveee/madcader-issues/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement"><img alt="Feature requests" src="https://img.shields.io/github/issues/Elohveee/madcader-issues/enhancement?label=feature%20requests&color=a2eeef"></a>
  <a href="https://github.com/Elohveee/madcader-issues/issues?q=is%3Aissue+is%3Aclosed"><img alt="Closed issues" src="https://img.shields.io/github/issues-closed/Elohveee/madcader-issues?label=closed&color=2ea44f"></a>
</p>

<p align="center">
  <a href="https://github.com/Elohveee/madcader-issues/issues/new?template=bug_report.yml"><b>🐞 Report an issue</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Elohveee/madcader-issues/issues/new?template=feature_request.yml"><b>💡 Request a feature</b></a>
  &nbsp;·&nbsp;
  <a href="https://madcader.com"><b>🛠️ Open MadCADer</b></a>
</p>

---

## 👋 Hello, builder

MadCADer is a 3D designer for T-slot aluminum frames, from workbenches and enclosures to printer frames and whatever else you're bolting together. You place beams, snap them together with real connector hardware, and get a cut list and parts count you can order from.

The code is private, but **this repo is fully public**. Anyone with a GitHub account can file, read, upvote and follow issues here.

You can also get here from inside the app:

| Where | How |
| :--- | :--- |
| Account menu (your avatar, top right) | **Report Issue** · **Feature Request** |
| Keyboard shortcuts dialog (press <kbd>?</kbd> in the editor) | the 🐞 and 💡 buttons in its header |

## 🐞 Found a bug?

**[Open a bug report →](https://github.com/Elohveee/madcader-issues/issues/new?template=bug_report.yml)**

The reports that get fixed fastest have:

1. **Steps someone else can follow.** For example: *"New model → add a 40×40 beam → connect a second beam at 90° → the corner bracket floats 2 mm off the face."*
2. **What you expected to happen**, and what happened instead.
3. **A screenshot or screen recording.** You can drag one straight into the form, and 3D problems are much easier to see than to describe.
4. **Your browser and OS.** MadCADer runs on WebGL, so a lot depends on the browser.

> [!TIP]
> If the editor freezes or shows nothing, open the browser console (<kbd>F12</kbd> → **Console**) and paste any red error lines into your report.

## 💡 Have an idea?

**[Suggest a feature →](https://github.com/Elohveee/madcader-issues/issues/new?template=feature_request.yml)**

Start with **what you're trying to build**, not just the button you'd like. *"I keep re-drawing the same 4-beam rectangle for shelves"* tells us more than *"add copy/paste."* There may be a better fix than the first one that comes to mind.

Before you post, **search the existing issues** and add a 👍 to the one that matches. We look at reactions when deciding what comes next.

## 🔁 What happens after you post

```mermaid
flowchart LR
    A([You open an issue]) --> B{Triage}
    B -->|Can reproduce| C[Labelled and prioritized]
    B -->|Need more info| D[We ask a question]
    D --> B
    B -->|Duplicate / won't fix| X([Closed with a note])
    C --> E[Fixed or built]
    E --> F([Shipped to madcader.com])
```

| Label | Meaning |
| :--- | :--- |
| ![bug](https://img.shields.io/badge/-bug-d73a4a) | Something is broken |
| ![enhancement](https://img.shields.io/badge/-enhancement-a2eeef) | A new feature or improvement |
| ![question](https://img.shields.io/badge/-question-d876e3) | We need more information from you |
| ![duplicate](https://img.shields.io/badge/-duplicate-cfd3d7) | Already tracked in another issue (linked) |
| ![wontfix](https://img.shields.io/badge/-wontfix-ffffff) | Out of scope for now. We'll explain why. |

Changes ship straight to [madcader.com](https://madcader.com). When a fix goes live, the issue is closed with a comment, and if you're subscribed you'll get a notification.

## 🔒 A note on privacy

Issues here are **public**. Please don't post passwords or private details, and don't attach a model file you don't want the world to see. If you need to share something sensitive, mention that in the issue and we'll find a private way to get it.

---

<p align="center">
  <sub>Made with too many T-nuts · <a href="https://madcader.com">madcader.com</a> · <a href="https://madcader.com/privacy">Privacy</a></sub>
</p>
