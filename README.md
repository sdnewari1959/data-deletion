# Data Deletion Policy Pages

This repository contains data deletion policy pages required for mobile app compliance with Google Play Console and other app stores.

## Available Pages

- **data-deletion.html** - Generic data deletion policy page
- **napjokh-data-deletion.html** - Specific data deletion page for the Napjokh app

## Using with Google Play Console

To use these pages with Google Play Console:

1. **Enable GitHub Pages** for this repository:
   - Go to repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

2. **Get the public URL**:
   - After enabling GitHub Pages, your data deletion policy will be available at:
   - `https://sdnewari1959.github.io/data-deletion/data-deletion.html`
   - Or for the Napjokh app: `https://sdnewari1959.github.io/data-deletion/napjokh-data-deletion.html`

3. **Submit to Play Console**:
   - In Google Play Console, go to your app → Policy → Data safety
   - In the "Data deletion" section, provide the GitHub Pages URL
   - Example: `https://sdnewari1959.github.io/data-deletion/data-deletion.html`

## Testing the Pages

You can test that your pages work correctly by:
1. Opening the GitHub Pages URL in a browser
2. Verifying that the email links work
3. Ensuring the page displays correctly on mobile devices

## Customization

To customize the pages for your specific app:
1. Edit the HTML files to update:
   - Email addresses
   - App name references
   - Company information
   - Any specific instructions for your app

The pages are already mobile-responsive and styled appropriately for compliance requirements.