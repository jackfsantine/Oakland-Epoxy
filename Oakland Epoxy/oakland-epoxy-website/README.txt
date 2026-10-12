# Oakland Epoxy Co. — one-page website

## Files
- `index.html` — complete responsive website (HTML, CSS, and JavaScript in one file)
- `oakland-epoxy-logo.png` — cropped placeholder logo from the screenshot you provided

## Preview
Open `index.html` in a browser. An internet connection is needed for the placeholder flooring photos.

## Connect the contact form to Google Forms
The form is styled and laid out, but it will not submit to Google until you connect your form.

1. Create a Google Form with questions matching Name, Email, Phone, Project type, and Project details.
2. In Google Forms, use the three-dot menu to **Get pre-filled link**. Fill each field with sample values and generate the link.
3. In that pre-filled URL, find the form URL and the `entry.########` IDs for each question.
4. In `index.html`, replace `GOOGLE_FORM_ACTION_URL` with your Google Form's response endpoint. It usually looks like:
   `https://docs.google.com/forms/d/e/YOUR_FORM_ID/formResponse`
5. Replace `entry.NAME_ID`, `entry.EMAIL_ID`, `entry.PHONE_ID`, `entry.PROJECT_ID`, and `entry.MESSAGE_ID` with the exact `entry.########` IDs for the matching questions.
6. Test a submission and confirm the response appears in Google Forms.

Google Forms does not provide a conventional website embed endpoint in the same way as a custom form backend, so test the final setup in a browser. For a more seamless success message, embed the Google Form or use a form service/backend.

## Before publishing
- Confirm business details and service area.
- Replace any copy or claims that don't match the services you actually offer.
- Swap the Unsplash placeholder images for photos of your own completed projects.
- Test the page on mobile and desktop.
