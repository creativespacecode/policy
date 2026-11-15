# Privacy Policy for Creative Space Code Apps

**Effective Date:** August 6, 2026

Creative Space Code ("we", "our", or "us") builds Shopify Admin apps, including **Simple Labels** (create custom label templates and print product information) and **Simple eBay Sync** (connect an eBay seller account and keep Shopify products in sync as eBay listings). This Privacy Policy explains how we handle data across our apps. Where a section applies to all of our apps, we refer to "Creative Space Code" or "the app"; where a practice is specific to one app, we name that app.

We value your privacy and are committed to handling your data responsibly. We do not collect or store any personal information about your store's customers.

## 1. Information We Collect

**All Creative Space Code apps** collect:

- **Store Identity** — your Shopify store name and domain, used to identify your store within our system, provide the app's features, and support you.

**Simple eBay Sync** additionally collects and stores the following in order to sync your Shopify catalog to eBay:

- **Product and inventory data** — SKUs, titles, descriptions, prices, quantities, images, and product tags for the products you choose to list on eBay.
- **Listing and sync data** — eBay listing/item IDs, sync status, and sync activity logs used to keep Shopify and eBay in sync and to help you troubleshoot.
- **eBay account credentials** — the OAuth access and refresh tokens for the eBay seller account(s) you connect, so the app can create and update listings on your behalf. These tokens are encrypted at rest (see [Section 4](#4-data-storage-and-security)).
- **App configuration and billing** — your plan/subscription and app settings.

**Error monitoring**

We use Sentry, an error-monitoring service provided by Functional Software, Inc. ("Sentry"), to find and fix problems in Simple Labels. When something in the app fails, an error report is sent to Sentry. A report may include:

- the error message and the part of our code where the error happened
- the app page where it occurred (the address only, without any login or session information)
- your browser and operating system type
- the time of the error
- your store's myshopify.com domain, if it appears in the error
Before a report is sent, we remove cookies, login tokens, request headers and form contents. Error reports do not include your customers' personal information, product data or label content, and Simple Labels does not store customer data.

Error reports are stored on Sentry's servers in the United States and kept for [30 days]. We use them only to diagnose and fix problems with the app. You can read Sentry's privacy policy at https://sentry.io/privacy/.

We do **not** collect or store personal information about your store's customers. Our apps operate on store-level and product-level data only.

## 2. How We Use Your Information

We use the information we collect solely to:

- Provide and operate the app's features.
- For **Simple eBay Sync**, create and maintain your eBay listings and keep price and inventory in sync between Shopify and eBay.
- Support your use of the app and respond to inquiries.
- Communicate important updates.

We do not use or sell your data for advertising, profiling, or third-party marketing.

## 3. Third-Party Services and Data Sharing

- **Shopify** — all Creative Space Code apps access your store data through the official Shopify Admin API, under the permissions (scopes) you grant when you install the app.
- **eBay** (Simple eBay Sync only) — to publish and sync listings, Simple eBay Sync sends the product data you select (title, description, price, quantity, images, and SKU) to eBay through eBay's official APIs, using the eBay account you connect. This sharing is essential to the app's core function. eBay's handling of that data is governed by eBay's own privacy policy.

We do not otherwise share, rent, or sell your data to third parties.

## 4. Data Storage and Security

- **Simple Labels** does not store customer or product data externally. Label templates and product information are accessed securely through the Shopify API and used only for rendering and printing within the app.
- **Simple eBay Sync** stores the store, product, listing, and configuration data described above in a secured database in order to perform ongoing background syncing. Connected eBay OAuth tokens are encrypted at rest using AES-256-GCM encryption and are cleared when you disconnect the account.

- Images and logos (optional)
-- If you choose to add a logo or other image to a label design, Simple Labels asks for permission to save files to your Shopify store. This permission is optional. It is requested only when you first add a logo, and you can decline it or revoke it at any time.
-- When you upload an image, it passes through our server only to be checked (we accept PNG, JPG, GIF, and WebP images up to 5 MB) and forwarded to Shopify. It is stored in your store's Files (Content › Files), where you can view or delete it like any other file. We do not keep a copy. Our database keeps only the image's Shopify ID and web address, as part of the label design that uses it, and deletes them with your other app data when you uninstall the app and Shopify sends its data deletion request.
-- With this permission, Simple Labels also reads the images already in your store's Files so you can choose one for a label. It never changes or deletes files you didn't upload through the app.

- Product images
-- Label designs can show your products' images. These are read with the product access the app already has and are loaded directly from Shopify's servers when a label is shown or printed. We do not store them.

- Fonts
-- The fonts used in label designs are served from our own servers. No font service or other third party receives information about you or your customers when labels are designed or printed.

Across all of our apps, we use standard, industry-accepted security practices to protect the data we handle, and access to store data is limited to what each app needs to function.

## 5. Data Retention and Deletion

- When you **uninstall** a Creative Space Code app, we immediately lose access to your Shopify store's information.
- **Simple eBay Sync** deletes the data associated with your store when the app is uninstalled and stops all background syncing. Consistent with Shopify's requirements, we also honor the `shop/redact` request that Shopify sends after uninstall, as a safeguard to ensure your store's data is removed.
- You may request deletion of any data we hold at any time by contacting us directly.

## 6. GDPR and CCPA Compliance

We support the mandatory Shopify privacy webhooks (`customers/data_request`, `customers/redact`, and `shop/redact`). Because our apps do not store customer personal data, the customer-level requests have no customer data to return or delete; the `shop/redact` request removes your store's data.

If you are located in the European Union (EU) or California (USA), you have specific rights under the General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA), including:

- The right to know what data we collect about you.
- The right to request that we correct or delete your data.
- The right to withdraw consent or object to certain types of data use.
- The right to access your data in a portable format.

To exercise any of these rights, please contact us at [privacy@creativespacecode.com](mailto:privacy@creativespacecode.com). We will respond within the timeframe required by applicable laws.

## 7. Uninstalling the App

If you uninstall a Creative Space Code app from your Shopify store, we immediately lose access to your store's information. For **Simple eBay Sync**, uninstalling also stops all background syncing and triggers deletion of your stored data. You may also request that we delete any data we've collected by contacting us directly.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with the updated effective date. Continued use of the app after changes means you agree to the updated policy.

## 9. Contact Us

If you have any questions or concerns about this Privacy Policy, or wish to make a data request, please contact us at:

- **Email:** [privacy@creativespacecode.com](mailto:privacy@creativespacecode.com)
- **Apps:** Simple Labels, Simple eBay Sync
- **Company:** Creative Space Code
