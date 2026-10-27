# PhiloMind — Philosophy for a Deeper Life

A responsive, single-page philosophy learning website built with plain HTML, CSS, and JavaScript. It is designed to be easy to publish with GitHub Pages and easy to customize without a build step.

## Features

- Responsive layout for desktop and mobile
- Search across the included philosopher/topic index
- Dark mode (preference stored in this browser)
- Daily philosophical question with interactive follow-up prompts
- Private reflection journal stored in browser `localStorage`
- Interactive Experience Machine thought experiment
- Mini logic quiz on validity and soundness
- Philosophy essay outline builder with `.txt` export
- Philosophy branches, timeline, reading guidance, and featured thinkers

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `philomind`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The published address will appear in the Pages settings.

No npm install or build command is required.

## Customize

- Change the brand name and copy in `index.html`.
- Edit the `searchItems`, `questions`, and `quotes` arrays in the script section to add content.
- Replace the Unsplash image URLs with your own licensed images if desired.
- Add more content pages by creating additional HTML files, or evolve this into a multi-page React project later.

## Privacy note

Reflection entries are stored in the current browser using `localStorage`; they are not uploaded to a server. They may be lost if browser storage is cleared, and they do not automatically sync across devices. Avoid entering sensitive personal information on a shared device.

## Content note

This is a polished functional starting version. Verify historical details and quote attributions before using the site as an academic reference. Some quotations are commonly attributed or paraphrased and should be checked against reliable editions.
