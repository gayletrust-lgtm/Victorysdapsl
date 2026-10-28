# Victory SDA Church Website — First Draft

A responsive, single-page custom website prototype for Victory Seventh-day Adventist Church in Port St. Lucie, Florida.

## Preview locally

1. Download and unzip the project.
2. Open `index.html` in a modern web browser.
3. Internet access is required for the Google Fonts and Unsplash photographs used in this prototype.

## Before publishing

This is a front-end website project and is **not yet deployed**. Prayer, visitor, and contact forms are configured to submit through FormSubmit to `victorysdachurchpsl@gmail.com`. The church inbox must complete FormSubmit’s first-use email activation before messages can be delivered. Test all three forms from the deployed HTTPS website before launch:

1. Configure the domain `victorysdapsl.com` with your domain registrar and hosting provider, including HTTPS. The canonical domain is set to `https://victorysdapsl.com/`.
2. Confirm that `victorysdachurchpsl@gmail.com` is the correct monitored church inbox and complete the FormSubmit activation email sent on the first form submission.
3. Replace sample sermon cards with real sermon titles, dates, speaker names, and video links. The YouTube livestream link is currently set to the supplied channel handle.
4. Confirm which ministry areas are active and who should receive ministry inquiries.
5. Review FormSubmit privacy and data handling, add a privacy policy, and confirm who in the church may access prayer requests. Avoid collecting sensitive personal details.
6. Verify the online giving destination and livestream channel before launch.
7. Replace stock imagery with church-owned photos where possible, after obtaining appropriate permission and photo consent.
8. Complete an accessibility review; verify image licenses and third-party assets.
9. Configure analytics (if desired), backups, and a process for keeping content current.

## Design and features

- Mobile-first responsive layout and collapsible mobile navigation
- Navy, gold, and white visual system
- Home, About, beliefs, ministries, events, messages, prayer, visitor, FAQ, contact, and giving-information sections
- Official Facebook page link supplied by church
- Weekly schedule and meeting address supplied by church
- Online giving link supplied by church
- YouTube livestream link constructed from the supplied channel handle (verify channel URL before launch)
- Accessible form labels, client-side validation, keyboard-usable FAQ controls, and reduced-motion support
- Prayer, visitor, and contact forms configured for FormSubmit email delivery to `victorysdachurchpsl@gmail.com` (first-use activation and live testing required)
- Clear placeholders for unconfirmed phone/email, sermon content, and form destinations

## Known limitations

- Forms use the third-party FormSubmit AJAX endpoint. Delivery depends on first-use recipient activation, third-party availability, and live testing; static HTML cannot guarantee delivery on its own.
- The sermon cards remain sample/placeholder content; weekly schedule details are filled in from church-provided information.
- There is no CMS/admin login, backend, database, livestream embed, or payment integration yet.
- The page uses remote Google Fonts and Unsplash images.
