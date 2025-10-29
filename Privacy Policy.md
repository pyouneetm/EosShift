EosShift Privacy Policy

This Privacy Policy explains how the EosShift browser extension (the "Extension") handles your information.

We believe in privacy first. EosShift is designed to work entirely locally within your browser. The developer, Puneet Mishra, does not collect, store, transmit, or share any personal information, browsing data, or web content from users of this Extension.

1. Data Collection and Transmission

1.1 Information We DO NOT Collect

EosShift operates without a backend server connection. This means:

No Personal Data: We do not collect names, email addresses, IP addresses, geographical locations, or any other personally identifiable information.

No Browsing History: We do not track, log, or transmit the websites you visit.

No Web Content: We do not capture or transmit the content of the pages you view, even when the Extension is active. All filtering, styling, and reader mode processing happens directly on your device.

1.2 Information Stored Locally (Your Settings)

The Extension requires local storage to remember your preferences and ensure a consistent experience across different websites. This data is stored using the browser's built-in chrome.storage.local API and remains solely on your computer.

The locally stored settings include:

Styling Preferences: Dark Mode selection, brightness, contrast, color filters, font size, line height, etc. (Stored in: Your local browser storage - chrome.storage.local).

Per-Site Overrides: Your custom settings for specific hostnames (e.g., youtube.com). (Stored in: Your local browser storage - chrome.storage.local).

Site List & Schedule: The list of domains for black/whitelisting, and the start/end times for scheduled modes. (Stored in: Your local browser storage - chrome.storage.local).

Custom CSS & Exclusions: Any custom CSS you type or elements you exclude using the context menu tool. (Stored in: Your local browser storage - chrome.storage.local).

Reader View Annotations: Highlights or notes made in the local Reader View environment. (Stored in: Your local browser storage - localStorage within the injected Reader View script).

This local data is never synced to external servers or accessible by the developer. You can view, export, and delete this data at any time via the Extension's popup.

2. Permissions Required

EosShift requires the following permissions to function as a powerful page customization tool:

activeTab: Allows the popup to access and control settings only on the tab you currently have open, not all tabs simultaneously.

scripting: Required to inject the styling and processing JavaScript (eoscontent.js and eosreader.js) into websites to apply your custom modes and filters.

storage: Required to permanently save your user-defined settings, site-specific overrides, and global preferences locally.

tabs: Used to identify the current tab and reload it after actions like clearing site data.

contextMenus: Required to add the "EosShift: Exclude this element" option to your browser's right-click menu.

browsingData: Required for the "Reset Site Storage" button. This function uses the chrome.browsingData.remove() API to clear cookies, cache, and local storage only for the current website's domain at your explicit request.

host_permissions (<all_urls>): Required so the Extension can inject its styling and code onto all websites you visit to apply the selected filters and customizations. This does not mean we monitor all your browsing; it means we have the technical ability to inject code when needed, all of which runs locally.

3. Third-Party Services

Support Links

The Extension includes a link to a third-party service ("Buy me a coffee") and a UPI ID (pyouneetm@oksbi) for voluntary donations.

Your use of these support links is entirely voluntary.

No data is transmitted to the developer automatically. Clicking on these links will direct you to external sites with their own privacy policies.

Reader View (Local Content Processing)

When you enable the advanced Reader View:

The content of the current article is processed by the local script (eosreader.js).

This script attempts to generate a local summary and citation information using simple text-processing algorithms.

The script uses your browser's native SpeechSynthesis API for Text-to-Speech functionality.

All content extraction and summarization remain local to your browser. No content is ever sent to an external service for processing.

4. Policy Changes

The developer reserves the right to update this Privacy Policy at any time. If the policy changes, the Extension will require a review and update on the relevant browser extension stores. Continued use of the Extension after a policy update implies acceptance of the new terms.

5. Contact Information

If you have any questions or concerns about this privacy policy, please contact the developer:

Puneet Mishra
Email: pyouneetm@gmail.com
GitHub/Support: https://github.com/pyouneetm/EosShift/issues

Last updated: October 25, 2025