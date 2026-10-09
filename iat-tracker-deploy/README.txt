IAT Tracker - Vercel Static Deployment

IMPORTANT: index.html must be at the ROOT of the deployed project.

Deploy using GitHub + Vercel:
1. Create a GitHub repository, e.g. iat-tracker.
2. Upload index.html directly into the repository root (not inside another folder).
3. In Vercel, import that repository.
4. Framework Preset: Other.
5. Build Command: leave empty.
6. Output Directory: leave empty / use the project root (do not set a separate output folder).
7. Deploy.

The tracker is a static HTML file with inline CSS and JavaScript, so it does not need npm install or a build command.

Note: Progress stored in browser localStorage is specific to each browser/profile/device. Hosting the page online does not automatically sync progress across devices.
