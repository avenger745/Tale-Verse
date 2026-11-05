# Tale Verse policy pages

Files:
- `privacy-policy.html` — Privacy Policy
- `data-deletion.html` — Data Deletion Instructions

## Before publishing
Review the text and confirm it matches the app's actual behavior, especially:
- the exact profile fields requested from Facebook and Google;
- the data stored in your database;
- whether any analytics, advertising, crash-reporting, or other third-party services receive data;
- your actual deletion and backup-retention process.

Do not publish statements that are not true of the app.

## Free hosting with GitHub Pages
1. Sign in to https://github.com/ or create a free account.
2. Create a new **public** repository, for example `tale-verse-legal`.
3. Upload `privacy-policy.html` and `data-deletion.html` to the repository's root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait for GitHub Pages to publish the site. Its URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/tale-verse-legal/`

Your Meta URLs will then be:
- Privacy Policy: `https://YOUR-GITHUB-USERNAME.github.io/tale-verse-legal/privacy-policy.html`
- User Data Deletion: `https://YOUR-GITHUB-USERNAME.github.io/tale-verse-legal/data-deletion.html`

Replace `YOUR-GITHUB-USERNAME` and `tale-verse-legal` with your actual GitHub username and repository name. Test both URLs in a private/incognito browser window before adding them to Meta.

In Meta for Developers, open your app's **Settings → Basic** and enter the URLs in the corresponding Privacy Policy URL and User Data Deletion URL fields. The exact labels may vary as Meta updates its dashboard.
