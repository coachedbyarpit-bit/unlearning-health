unlearning.health — website files
==================================

WHAT IS IN THIS FOLDER
----------------------
index.html        → the homepage
terms.html        → Terms and Conditions
privacy.html      → Privacy Policy
refund.html       → Refund and Cancellation Policy
contact.html      → Contact and medical disclaimer
assets/           → founder photo and client result photos
                    (this folder MUST stay next to the html files)

Keep every file together exactly as it is. If you move the html files
out of this folder and leave the assets folder behind, the photos and
logo will not load.


HOW TO HOST IT (Netlify, free, ~10 minutes)
--------------------------------------------
1. Unzip this folder onto your computer.

2. Go to app.netlify.com and sign up (use your unlearning.health
   Google Workspace email).

3. On the dashboard, find "drag and drop your site folder here."
   Drag this whole folder (the one containing index.html and assets)
   onto it. It goes live in about 30 seconds on a temporary address
   like random-name-123.netlify.app.

4. Test it. Click through every page. Click the "Book a call" buttons
   and confirm they open your Calendly.

5. Connect your domain: in Netlify go to Domain settings → Add a domain
   → enter unlearning.health. Netlify shows you DNS records to add.

6. In Namecheap (where you bought the domain), open the DNS settings
   for unlearning.health and add the records Netlify gives you. Save.
   Wait a few minutes to a few hours for it to go live.

7. HTTPS turns on automatically once the domain connects.

IMPORTANT ABOUT EMAIL: You already have Google Workspace email on this
domain. When editing DNS, do NOT delete the existing MX records — those
keep team@unlearning.health working. You are only ADDING website records.
The simplest path is to keep Namecheap's nameservers and just add the
A / CNAME records Netlify specifies. If Netlify asks you to switch
nameservers entirely, you must re-add your Google MX records inside
Netlify's DNS panel afterwards.

Updating later = just drag the folder onto Netlify again.


BEFORE YOU POINT THE REAL DOMAIN — QUICK CHECKLIST
--------------------------------------------------
[ ] Confirm team@unlearning.health actually receives email.
[ ] Confirm you have written consent for every client face shown in
    the results gallery. Remove any image you do not have consent for
    (delete the matching <img> line in index.html and the file in
    assets/results/).
[ ] Have a lawyer glance at refund.html and the disorders section of
    index.html. The policies are sound templates, not legal advice.
[ ] When you set up your payment gateway, it may require your legal
    entity name (Parentix Fitness Private Limited) visible on the site.
    If so, add it back to terms.html or contact.html — a 30 second fix.

The Calendly link wired throughout is:
https://calendly.com/teamcoachedbyarpit/ypt90-metabolic-audit
