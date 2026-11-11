# NFC + QR Review Website

Business: Universal Kebabs & Biryani

## What it does
- Open `index.html` on tap/scan.
- Customer selects any star from 1–5.
- Browser immediately navigates to `feedback.html?rating=N`.
- Every rating gets the same options: **Review on Google** or **Send private feedback**.
- Google button opens the Maps listing supplied by the user. Google may not immediately open the write-a-review dialog; replace with a direct review URL if one is available.
- Private feedback is **not transmitted or stored**. If clipboard copying fails, a selectable text box appears. It can be copied to the clipboard and shared manually. Add an owner-approved receiving mechanism (such as a contact form backend) before advertising it as direct delivery.

## Free publishing
Upload all three website files (`index.html`, `feedback.html`, `style.css`) to the root of a GitHub Pages repository or Cloudflare Pages site. Write the published **index.html** website URL to the NFC card using NFC Tools. Make the QR code use that exact same URL.

## Customization
Change the business name in both HTML files and replace the Google Maps href in `feedback.html` when reusing the template for other businesses. Do not use the template to block low-rating customers from reviewing publicly.
