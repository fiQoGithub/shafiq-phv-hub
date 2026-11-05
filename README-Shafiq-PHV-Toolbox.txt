SHAfiq PHV — DRIVER KNOWLEDGE & TECHNOLOGY HUB v0.4

FILES IN THIS RELEASE
- index.html: Main homepage.
- phv-tracker-v1.html: PHV Tracker. Existing browser storage keys and record format are preserved in this revision.
- ev-calculator.html: EV & Vehicle Cost Calculator.
- knowledge-centre.html: Starter knowledge page.
- feedback.html: Feedback landing page. WhatsApp works now; Google Form is not yet connected.

BRANDING
Official name: Shafiq PHV — Driver Knowledge & Technology Hub.
Short brand: Shafiq PHV.
Tagline: Practical tools, knowledge and community for Singapore PHV drivers.
Community credit: Built by Shafiq (@shafiq.phv), from the PHV AI community — Joel Ng (@joelng.ai).

FEEDBACK
- WhatsApp opens a prepared message; the user must tap Send.
- Google Forms/Sheets has not been created or connected yet. Create a Google Form, link its Responses tab to a Google Sheet, test a submission, then replace the temporary text on feedback.html and homepage with the real form URL. Do not publish an editable response sheet.
- Do not collect NRIC, passwords, bank details or private financial documents.

TRACKER DATA / BACKUP
- Tracker records remain in local browser storage on the user's device. They are not uploaded to a server.
- Download my backup file exports records and platform fee settings to a .json file.
- Restore replaces the records currently saved in that browser after confirmation. Users should download a fresh backup before restoring.
- Preserve the existing tracker storage keys if modifying its code; this version retains the current code and storage model.

EV CALCULATOR
- Example values are assumptions, not verified current Singapore rates or recommendations.
- Have an experienced EV driver/rental operator validate vehicle efficiency, tariffs, charging time, rental and charging arrangements before presenting outputs as reliable.
- One input per row is used for easier mobile entry.

GITHUB PAGES DEPLOYMENT — BEGINNER STEPS
1. Open https://github.com/fiQoGithub/phvtracker and make sure you are signed in.
2. Before changing anything, open each current HTML file and use Download raw file / save a local copy. Keep the original files in a folder named phvtracker-backup.
3. Download and extract shafiq-phv-hub-v0.4.zip on your computer.
4. In the GitHub repository, click Add file > Upload files.
5. Upload these five files together into the repository root (not inside a new folder): index.html, phv-tracker-v1.html, ev-calculator.html, knowledge-centre.html, feedback.html.
6. If GitHub reports a file with the same name, it will be replaced in the new commit. Check that your local backup exists first.
7. Scroll down to Commit changes. Use message: Publish Shafiq PHV Hub v0.4. Choose commit directly to main, then click Commit changes.
8. Open Settings > Pages. Confirm Deploy from a branch, branch main, folder /(root). Do not change the repository visibility or other settings.
9. Wait for the Pages deployment. Open the published website on desktop and phone. Check all links and test a sample tracker backup before inviting drivers.
10. If something is wrong, the previous commit can be restored from the repository's commit history. Do not delete the repository.

LINK PREVIEW
- Page title, description and Open Graph title/description are set. Some messaging apps cache old previews; test after deployment and allow time for cache refresh.

RELEASE LIMITATIONS
- No cloud account, sync or central database.
- Google Form integration is pending user setup.
- This release has not been tested on every physical device/browser.
