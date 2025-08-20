Spellmates site v2
- Sticky nav with subtle blur
- Newsletter signup (uses Formspree or EmailJS). Replace the FORM_ENDPOINT in index.html with your own endpoint.
  • Formspree: create a form at https://formspree.io/, copy the endpoint, paste into FORM_ENDPOINT.
  • EmailJS: use emailjs SDK if you prefer; or swap to mailto: if you don't want a service yet.
- Client-side www → apex redirect (GitHub/DNS already handle most cases; this is a safety net).
- Replace images in /assets/images with your own art whenever you like.
