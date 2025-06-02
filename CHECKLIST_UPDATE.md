# Checklist for App Updates

Use this checklist before submitting an update to an app that’s already live on the App Store.

---

## App Store Connect Tasks

- [ ] Write a clear, accurate **"What’s New"** summary for each localization and fill in the promo text (if used).
- [ ] Provide a detailed **"Notes" for the Review Team** section in App Store Connect—explain exactly what has changed, describe any significant updates, and call attention to new features, removed features, or anything that may affect review. Add screenshots that show newly added features, purchase/restore/delete account buttons, or anything required for compliance that a reviewer should see.
- [ ] If the UI or workflows have changed, **update your screenshots** to match the new version.
- [ ] Review and update your app’s **Description** and **Promo Text** to accurately reflect changes.

---

## Privacy & Compliance

- [ ] If your app’s data collection or sharing practices have changed, update your **Privacy Policy** and ensure all privacy descriptions and links are accurate.
- [ ] Update the **Privacy Policy/Terms** URLs if you’ve changed providers or policies.
- [ ] Review and update your [App Privacy details](https://developer.apple.com/support/app-privacy-on-the-app-store/) in App Store Connect if required.

---

## Project & Testing

- [ ] Remove or hide any debug/testing tools or features from your production build.
- [ ] Fully test all new and updated features on every iOS device and OS version you support.
- [ ] Review and refresh analytics/tracking/monitoring integrations to ensure they reflect the latest app logic.
- [ ] Check that onboarding flows, deep links, notifications, and background tasks work as expected with the new version.
- [ ] Double-check your screenshots, description, and metadata—all should reflect the latest app state.
- [ ] **Update your project in CloudKit Console:**
    - [ ] Migrate any development schema changes to production.
    - [ ] Ensure containers and records are configured for the new version.
    - [ ] Check production container access controls and data model compatibility.

---

## Additional Tips

- [ ] Use the "Phased Release" option if you want to monitor the update roll-out for stability before releasing to all users.
- [ ] Check for any new App Store Review Guideline updates since your last release.
- [ ] Update your marketing materials and support docs to match the new version.
