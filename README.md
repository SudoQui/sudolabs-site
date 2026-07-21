# SudoLabs static website

This folder contains a deployable static website for:

* SudoLabs homepage
* Muslims ACT product page
* MACT privacy policy
* MACT support
* MACT data deletion requests

## Recommended deployment with Vercel

1. Create a new GitHub repository named `sudolabs-site`.
2. Upload all files and folders from this package.
3. In Vercel, choose **Add New → Project**.
4. Import the GitHub repository.
5. Select **Other** as the framework preset if Vercel does not detect a framework.
6. Leave the build command empty.
7. Set the output directory to `.` if Vercel asks.
8. Deploy.
9. In the Vercel project, open **Settings → Domains**.
10. Add `sudolabs.app` and `www.sudolabs.app`.
11. Apply the DNS records Vercel shows at the company where the domain is registered.

## URLs for Google Play Console

Privacy policy:
https://sudolabs.app/mact/privacy/

Data deletion:
https://sudolabs.app/mact/data-deletion/

Support:
https://sudolabs.app/mact/support/

Website:
https://sudolabs.app/

## Before production release

Review the policy against the final production app and its installed SDKs.
Update the email address when a permanent support address is available.
Add a privacy policy link inside the MACT mobile app.