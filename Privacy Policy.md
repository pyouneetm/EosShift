EosShift Privacy Policy

**Effective Date:** October 29, 2025
**Developer:** Puneet Mishra (Pyouneetm)

This Privacy Policy explains the nature, purpose, collection, use, and disclosure of information related to the EosShift browser extension ("the Extension").

1. Core Principle: We Do Not Collect Personal Data

EosShift is built with a fundamental commitment to privacy. **The Extension does not collect, transmit, store on external servers, or share any personally identifiable information (PII), browsing history, search queries, or user activity outside of your local browser.**

All data processing, styling, and saving of your settings occur entirely within your local browser environment.

2. Information Handled Locally

The Extension requires storage space to function. This data is stored securely using the browser's built-in **Chrome Storage API** (chrome.storage.local), which is compatible with Microsoft Edge, and is only accessible by the Extension itself and the user on the device where it is installed.

Data Type

Purpose & Description

Data Location

**Site-Specific Settings**

Stores user preferences for specific websites (e.g., brightness, contrast, mode, font, custom CSS, excluded elements). This data is necessary to maintain a consistent user experience on each site.

Local Browser Storage

**Global Settings**

Stores general application-wide preferences (e.g., default mode, scheduling times).

Local Browser Storage

**Site List**

Stores the list of URLs/domains for Blacklist/Whitelist features. This list is necessary to determine if the Extension should apply effects to a specific website.

Local Browser Storage

**Element Exclusions**

Stores CSS selectors of elements you manually choose to hide. This is strictly used for visual customization.

Local Browser Storage

**Reader Mode Annotations**

Stores highlighted text and notes created within the dedicated Reader View (Eos Reader).

Local Browser Storage (localStorage)

3. Permissions and Use of Browser APIs

The manifest.json requires several permissions to execute its core styling and utility functions. Below is a justification for each permission:

Permission Name

Justification for Use

Data Impact

**activeTab**

Allows the Extension to run code on the currently active tab when you click the EosShift icon. This is necessary to retrieve the current URL and apply settings.

Low (Used for URL identification only)

**scripting**

Required to inject the content scripts (eoscontent.js and eosreader.js) into web pages to apply visual styles, filters, and reader mode features.

High (Required for all styling functionality)

**storage**

Required to read and write all local settings (modes, filters, site lists, custom CSS) to your local browser storage. **Data remains local.**

Zero (Data is never transmitted)

**tabs**

Used to identify the URL of the active tab to load and save site-specific settings.

Low (Used for URL identification only)

**contextMenus**

Used to register the "Exclude this element" right-click menu option.

Zero (Used for UI functionality only)

**browsingData**

Specifically used by the **"Reset Site Storage"** button. When clicked, the Extension requests the browser to delete the local storage, cookies, and cache *only* for the current website's domain, acting as a user-triggered cleaning utility.

High (Deletes selected local data at user command)

**host_permissions: <all_urls>**

Required for the Extension's core function: applying visual modifications (dark mode, filters, custom CSS) to *all* websites the user visits, as intended.

High (Access to all website content is necessary to modify its appearance)

4. Third-Party Access

The EosShift Extension uses **no external servers, tracking libraries, or analytics services.** All communication, processing, and data storage are strictly client-side within your browser.

**Payment Links:** The "Buy me a coffee" link directs you to an external payment platform. Any interaction on that third-party website is governed by their respective privacy policy.

5. Data Deletion and Retention

Since EosShift stores all data locally, all information is deleted immediately and permanently in the following circumstances:

When you **uninstall** the EosShift Extension from your browser.

When you use the **"Reset Site Storage"** button within the popup, data for that specific site is deleted.

When you use your browser's function to **clear local storage/extension data**.

We retain no copies of your data whatsoever.

6. Policy Updates

This Privacy Policy may be updated periodically. We will always update the "Effective Date" at the top of the policy to reflect the most recent revision.

7. Contact Information

If you have questions or concerns about this policy or the Extension's privacy practices, please contact the developer at:

Email Address : pyouneetm@gmail.com