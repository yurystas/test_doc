---
title: Wiki.js
description: Official Documentation for 2.x
published: true
date: 2025-09-26T11:23:32.775Z
tags: 
editor: markdown
dateCreated: 2025-09-26T09:23:33.812Z
---

> This documentation site is running on Wiki.js!
{.is-success}
```diagram
PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudDsgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IGNvbG9yLXNjaGVtZTogbGlnaHQgZGFyazsiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIxMjFweCIgaGVpZ2h0PSI2MXB4IiB2aWV3Qm94PSItMC41IC0wLjUgMTIxIDYxIiBjb250ZW50PSImbHQ7bXhmaWxlIGhvc3Q9JnF1b3Q7ZW1iZWQuZGlhZ3JhbXMubmV0JnF1b3Q7IGFnZW50PSZxdW90O01vemlsbGEvNS4wIChYMTE7IExpbnV4IHg4Nl82NCkgQXBwbGVXZWJLaXQvNTM3LjM2IChLSFRNTCwgbGlrZSBHZWNrbykgQ2hyb21lLzE0MC4wLjAuMCBTYWZhcmkvNTM3LjM2JnF1b3Q7IHZlcnNpb249JnF1b3Q7MjguMi41JnF1b3Q7Jmd0OyZsdDtkaWFncmFtIGlkPSZxdW90OzRJTnVrbGpvd3BCSjBEQ19NVlpmJnF1b3Q7IG5hbWU9JnF1b3Q7UGFnZS0xJnF1b3Q7Jmd0O2paSk5iOE1nRElaL0RmY2txRzEyWGRhdGgwNDc1TEF6Q2w1QUluRkV5WkxzMTQ4TWt3OVZsWFlDSHI4Rys4V01GODM0WmtXbjNsR0NZVmtpUjhaZldKYWwvSEQweTB5bVFFNVBlUUMxMVpKRUt5ajFEeEJNaVBaYXdtMG5kSWpHNlc0UEsyeGJxTnlPQ1d0eDJNdSswT3hmN1VRTmQ2Q3NoTG1ubjFvNkZXaCtTRlorQVYycitIS2FVS1FSVVV6Z3BvVEVZWVA0bWZIQ0lycXdhOFlDekd4ZTlDWGt2VDZJTG9WWmFOMS9FcktROEMxTVQ3MWR6dGZyQnhYbnB0aXh4YjZWTUNlbGpEOFBTanNvTzFITjBjSC9zV2ZLTlliQ2RDZFlCK1BEdXRLbFd6OG1nQTA0TzNrSkpmQVRHVVFUd25NNkQ2dmZhVFJSYmJ3K0VoUDB4ZlZ5OWVxQzM1QVI4YmdhL2hmYmpDMC8vd0k9Jmx0Oy9kaWFncmFtJmd0OyZsdDsvbXhmaWxlJmd0OyI+PGRlZnMvPjxnPjxnIGRhdGEtY2VsbC1pZD0iMCI+PGcgZGF0YS1jZWxsLWlkPSIxIj48ZyBkYXRhLWNlbGwtaWQ9IjIiPjxnPjxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSIxMjAiIGhlaWdodD0iNjAiIHJ4PSI5IiByeT0iOSIgZmlsbD0iI2ZmZmZmZiIgc3Ryb2tlPSIjMDAwMDAwIiBwb2ludGVyLWV2ZW50cz0iYWxsIiBzdHlsZT0iZmlsbDogbGlnaHQtZGFyaygjZmZmZmZmLCB2YXIoLS1nZS1kYXJrLWNvbG9yLCAjMTIxMjEyKSk7IHN0cm9rZTogbGlnaHQtZGFyayhyZ2IoMCwgMCwgMCksIHJnYigyNTUsIDI1NSwgMjU1KSk7Ii8+PC9nPjxnPjxnPjxzd2l0Y2g+PGZvcmVpZ25PYmplY3Qgc3R5bGU9Im92ZXJmbG93OiB2aXNpYmxlOyB0ZXh0LWFsaWduOiBsZWZ0OyIgcG9pbnRlci1ldmVudHM9Im5vbmUiIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIHJlcXVpcmVkRmVhdHVyZXM9Imh0dHA6Ly93d3cudzMub3JnL1RSL1NWRzExL2ZlYXR1cmUjRXh0ZW5zaWJpbGl0eSI+PGRpdiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94aHRtbCIgc3R5bGU9ImRpc3BsYXk6IGZsZXg7IGFsaWduLWl0ZW1zOiB1bnNhZmUgY2VudGVyOyBqdXN0aWZ5LWNvbnRlbnQ6IHVuc2FmZSBjZW50ZXI7IHdpZHRoOiAxMThweDsgaGVpZ2h0OiAxcHg7IHBhZGRpbmctdG9wOiAzMHB4OyBtYXJnaW4tbGVmdDogMXB4OyI+PGRpdiBzdHlsZT0iYm94LXNpemluZzogYm9yZGVyLWJveDsgZm9udC1zaXplOiAwOyB0ZXh0LWFsaWduOiBjZW50ZXI7IGNvbG9yOiAjMDAwMDAwOyAiPjxkaXYgc3R5bGU9ImRpc3BsYXk6IGlubGluZS1ibG9jazsgZm9udC1zaXplOiAxMnB4OyBmb250LWZhbWlseTogSGVsdmV0aWNhOyBjb2xvcjogbGlnaHQtZGFyaygjMDAwMDAwLCAjZmZmZmZmKTsgbGluZS1oZWlnaHQ6IDEuMjsgcG9pbnRlci1ldmVudHM6IGFsbDsgd2hpdGUtc3BhY2U6IG5vcm1hbDsgd29yZC13cmFwOiBub3JtYWw7ICI+SEVMTE88L2Rpdj48L2Rpdj48L2Rpdj48L2ZvcmVpZ25PYmplY3Q+PHRleHQgeD0iNjAiIHk9IjM0IiBmaWxsPSJsaWdodC1kYXJrKCMwMDAwMDAsICNmZmZmZmYpIiBmb250LWZhbWlseT0iSGVsdmV0aWNhIiBmb250LXNpemU9IjEycHgiIHRleHQtYW5jaG9yPSJtaWRkbGUiPkhFTExPPC90ZXh0Pjwvc3dpdGNoPjwvZz48L2c+PC9nPjwvZz48L2c+PC9nPjxzd2l0Y2g+PGcgcmVxdWlyZWRGZWF0dXJlcz0iaHR0cDovL3d3dy53My5vcmcvVFIvU1ZHMTEvZmVhdHVyZSNFeHRlbnNpYmlsaXR5Ii8+PGEgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCwtNSkiIHhsaW5rOmhyZWY9Imh0dHBzOi8vd3d3LmRyYXdpby5jb20vZG9jL2ZhcS9zdmctZXhwb3J0LXRleHQtcHJvYmxlbXMiIHRhcmdldD0iX2JsYW5rIj48dGV4dCB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LXNpemU9IjEwcHgiIHg9IjUwJSIgeT0iMTAwJSI+VGV4dCBpcyBub3QgU1ZHIC0gY2Fubm90IGRpc3BsYXk8L3RleHQ+PC9hPjwvc3dpdGNoPjwvc3ZnPg==
```

# Getting Started

Wiki.js is quick and easy to install. You should be up and running in no time.

- [Requirements *Server and database prerequisites.*](/install/requirements)
- [Installation Guide *Detailed installation instructions for all platforms.*](/install)
{.links-list}

# User Guide

- [The Basics *New to Wiki.js? Learn how to use it and create your first page.*](/guide/intro)
- [Folder Structure & Tags *Learn how to categorize your pages for an easier browsing experience.*](/guide/structure)
- [Manage Pages *How to create, edit and manage your pages.*](/guide/pages)
- [Using Editors *Learn how to use the various editors.*](/editors)
- [Using Assets *How to upload and manage assets such as images and documents.*](/guide/assets)
{.links-list}

# Administration

- [:globe_with_meridians: Locales *Display the wiki in a different language or enable multilingual capabilities.*](/locales)
- [:busts_in_silhouette: User Groups *Permissions and access rights.*](/groups)
- [:satellite: Telemetry *Help Wiki.js developers understand crashes by enabling anonymous telemetry.*](/telemetry)
- [:wrench: Troubleshooting *Solutions to common issues.*](/troubleshooting)
{.links-list}

## Modules
Modules greatly expand the capabilities of your wiki.
- [:lock: Authentication *Configure how users can login and register to your wiki.*](/auth)
- [:speech_balloon: Comments *Add discussion capabilities to your wiki.*](/comments)
- [:pencil: Editors *Manage the various editors used to create content.*](/editors)
- [:hourglass: Rendering *Configure how content is parsed and rendered into its readable form.*](/rendering)
- [:mag: Search Engines *Manage the search capabilities of your wiki.*](/search)
- [:floppy_disk: Storage *Backup or sync the content of your wiki with external storage services.*](/storage)
{.links-list}

# Developers

Wiki.js is fully extensible for maximum customization.

- [:book: Getting Started *How to setup a dev environment for Wiki.js.*](/dev)
- [:closed_book: Modules *Learn how to create a module.*](/dev/modules)
- [:art: Themes *Learn how to create your own theme.*](/dev/themes)
{.links-list}

# Localization
- [:globe_with_meridians: Translations *Contribute a new language or test new keys*](/dev/translations)
{.links-list}

# Contribute
- [:question: Ask a Question *We're here to help.*](https://github.com/Requarks/wiki/discussions)
- [:fire: Report a Bug *Help us squash those pesky bugs.*](https://github.com/Requarks/wiki/discussions)
- [:bulb: Suggest a New Feature *We need your ideas!*](https://requests.requarks.io/wiki)
- [:moneybag: Donate *Make a small donation or become a sponsor of this wonderful project!*](https://js.wiki/donate)
{.links-list}

![Wiki.js](https://static.requarks.io/logo/wikijs-butterfly.svg){.align-abstopright}