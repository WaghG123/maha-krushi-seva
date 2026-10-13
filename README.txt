MAHA KRUSHI SEVA — AUTOMATIC UPDATES STARTER
=============================================

WHAT THIS PACKAGE DOES
- Responsive agriculture/government-information website.
- Marathi, Hindi and English language switching for the main page.
- Automatic headlines panel.
- GitHub Actions workflow runs daily and can be run manually.
- Fetches Google News RSS search results for Maharashtra schemes, agriculture schemes and recruitment.
- Updates updates.json, which the website reads.

ACCURACY NOTE
This fetches news headlines, not verified government notifications. Headlines may include media reports or third-party sources. Always verify details, dates, eligibility and instructions at official government portals. Do not present headlines as official announcements without verification.

PUBLISH FREE USING GITHUB PAGES
1. Sign in/create an account at https://github.com/
2. Create a PUBLIC repository, e.g. maha-krushi-seva.
3. Upload all files/folders in this package, keeping the folder structure:
   index.html
   updates.json
   scripts/fetch_updates.py
   .github/workflows/refresh-updates.yml
   README.txt
4. Open repository Settings -> Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Select branch "main" and folder "/ (root)", then Save.
7. Wait for GitHub Pages to publish and click "Visit site" in Settings -> Pages.
8. In the repository, open Actions and confirm the workflow is enabled. Open "Refresh government and scheme headlines" and click "Run workflow" once to generate the first updates.json.
9. Scheduled refresh is daily at 02:17 UTC (07:47 India time). Scheduled jobs may be delayed.

IF AUTOMATIC UPDATES DO NOT APPEAR
- Ensure updates.json is in repository root.
- Open Actions and manually run the workflow.
- Check the workflow log for feed or permission errors.

LIMITATIONS
- Static website, no admin dashboard or database.
- Headlines update automatically; full articles are not copied.
- Google News RSS may change availability or results.
- No guarantee of income or AdSense approval.
- This is an independent information website, not an official government website.
