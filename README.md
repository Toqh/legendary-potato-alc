# African Leishmaniases Consortium

Static ALC website, configured for Vercel hosting.

## Editing

The site entry point is `index.html`. Keep the `assets` directory alongside it.
`ALC_Landing_Page.html` is the original working copy; when editing it, copy the
updated file to `index.html` before publishing.

## Publishing

Vercel serves `index.html` and the `assets` directory directly. No build tools
are required. Link this folder to the `alc-africa` Vercel project, then run
`npx vercel --prod` to publish. When the GitHub repository is connected in
Vercel, pushes to `main` publish automatically.
