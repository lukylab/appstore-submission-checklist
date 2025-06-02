# Checklist for App Updates

Use this checklist before submitting an update to an app that’s already live on the App Store.

---

## App Store Connect Tasks

- [ ] Write a clear, accurate **"What’s New"** summary for each localization.
- [ ] Provide a detailed **"Notes"** in App Review Information section in App Store Connect—explain exactly what has changed, describe any significant updates, and call attention to new features, removed features, or anything that may affect review. Add screenshots that show newly added features, purchase/restore/delete account buttons, or anything required for compliance that a reviewer should see.
- [ ] If the UI or workflows have changed, **update your screenshots** to match the new version.
- [ ] Review and update your app’s **Description** and **Promo Text** to accurately reflect changes.

---

## Privacy & Compliance

- [ ] If your app’s data collection or sharing practices have changed, update your **Privacy Policy** and ensure all privacy descriptions and links are accurate.
- [ ] Update the **Privacy Policy/Terms** URLs if you’ve changed providers or policies.

---

## Project & Testing

- [ ] Remove or hide any debug/testing tools or features from your production build.
- [ ] Fully test all new and updated features on every iOS device and OS version you support.
- [ ] Review and refresh analytics/tracking/monitoring integrations to ensure they reflect the latest app logic.
- [ ] Check that onboarding flows, deep links, notifications, and background tasks work as expected with the new version.
- [ ] **Update your project in CloudKit Console:**
    - [ ] Migrate any development schema changes to production.
    - [ ] Ensure containers and records are configured for the new version.

---

## Additional Tips

- [ ] Use the "Phased Release" option if you want to monitor the update roll-out for stability before releasing to all users.
- [ ] Update your marketing materials and support docs to match the new version.
