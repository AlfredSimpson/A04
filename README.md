# A04
 Assignment A04 for IS-117 with Dr. Hendela

# Task & Check List

- [x] Create a web page in your editor that contains your username, the course name and section.  
- [x] Save the page with the name: my-first-web-page.html
- [x] Once you are finished editing, create a Github repository called A04.
- [x] Upload your file to the A04 repository in your Github account.
- [x] Activate the page through settings

:)

## Troubleshooting

The instructions required us to save the page as my-first-webpage.html. However, GitHub defaults to index.html. If none exists, it will publish README.md... So a quick *hack* to fix this is to do the following:

- Create index.md (see mine at [index.md](./index.md)
- Add to index.md the following:
```md
---
permalink: /my-first-web-page.html
---

<!-- Redirect to your desired HTML page -->
<meta http-equiv="refresh" content="0;url=my-first-web-page.html">
```
- Save, and return to the pages section in the settings.
- From there, deploy as you would normally.

### If you already deployed, though...

If you already deployed, you'll want to break the deployment and then redeploy to the real directory.
- Where it says branches, you'll want to choose the wrong directory. We use root, but...
 - ![image](https://github.com/AlfredSimpson/A04/assets/73041922/06ac6847-37ef-4fc2-ba74-3d7a3082ad74)
- If you choose docs and hit save it will break the deployment. Great! After hitting save you can immediately correct the directory back to / (root) and hit save again.
- It will take a few minutes, but once resolved, your page will be good as new - displaying the desired html page.
