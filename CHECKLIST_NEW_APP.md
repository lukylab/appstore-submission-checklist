# Checklist for New App Submissions

Use this checklist before submitting your iOS app to the App Store for the first time.

---

## Xcode Project Checks

- [ ] Remove all debug, test, or logging code from production builds, or mark them with #if DEBUG/#endif to hide them from prod.
- [ ] Ensure the app runs smoothly on all iOS versions and devices you plan to support.
- [ ] Check that all onboarding flows are complete and free of placeholder or demo content.
- [ ] Remove any test/demo/placeholder data from your app.
- [ ] Provide clear Info.plist entries for all permissions (e.g., camera, location) your app requests (see samples [here](https://github.com/lukylab/ios-permissions-descriptions).
- [ ] All permission prompts are shown only as needed and include a clear, user-facing rationale.
- [ ] Verify the bundle identifier in Xcode matches the identifier in App Store Connect.
- [ ] Test app state restoration, backgrounding/foregrounding, and error handling (including simulating poor network or low storage).
- [ ] Remove references to price or promotional terms (“free,” “discount,” etc.) in your screenshots for the App Store.
- [ ] Add user feedback for error cases and failures—avoid silent failures.
- [ ] Implement proper cleanup of user data if required (e.g., provide a “Delete Account” option).
- [ ] Integrate analytics for key features (if desired).
- [ ] Test various network, device, and multi-user scenarios (if relevant).
- [ ] Deploy iCloud (or any cloud service you use) to production (not in a development or test environment).

---

## App Store Connect Checks

- [ ] Add and configure all required in-app purchases and subscriptions you want to launch with your app’s first version.
- [ ] Set up app pricing and availability for all countries/regions you intend to target (be aware of local restrictions, e.g., AI in China).
- [ ] Write a clear, descriptive App Name (Title) and Subtitle—target your main keywords.
- [ ] Optimize the Keywords field: no spaces after commas; don’t duplicate words used in the Title or Subtitle.
- [ ] Fill in both the Main Category and Subcategory.
- [ ] Fill out Support URL and (if available) Marketing URL.
- [ ] Add Copyright (your personal or company name).
- [ ] Add links to your Privacy Policy, Terms of Use, and License in the App Store description (and provide working URLs in the designated fields).
- [ ] Fill in the Age Rating questionnaire carefully (this affects discoverability and review outcome).
- [ ] Select Content Rights and Main License in the App Information section.
- [ ] Choose manual or automatic release—decide if the app goes live immediately after approval or if you want to release it manually.
- [ ] Upload the required set of screenshots for each device family you support (see below for recommended sizes).
- [ ] For sensitive features (e.g., delete account/logout button), attach a screenshot showing them to your notes for reviewers. (Tip: Reviewers sometimes miss these if not shown clearly.)
- [ ] Complete all localizations as needed for your app at launch.

---

## Recommended Screenshot Sizes

### iPhone
Up to 3 app previews + 10 screenshots per size:
- 6.7"/6.9" displays:  
  - 1290 × 2796 px, 2796 × 1290 px  
  - 1320 × 2868 px, 2868 × 1320 px

### iPad
Up to 3 app previews + 10 screenshots:
- 12.9"/13" displays:  
  - 2048 × 2732 px, 2732 × 2048 px  
  - 2064 × 2752 px, 2752 × 2064 px

### Apple Watch
Up to 10 screenshots:
- Ultra 2: 410 × 502 px  
- Series 10: 416 × 496 px  
- Series 9: 396 × 484 px  
- Series 6: 368 × 448 px  
- Series 3: 312 × 390 px

### iMessage Apps
Up to 10 screenshots for iPhone 6.7"/6.9" displays:
- 1290 × 2796 px, 2796 × 1290 px  
- 1320 × 2868 px, 2868 × 1320 px

### Mac
Up to 3 app previews + 10 screenshots:
- 1280 × 800 px  
- 1440 × 900 px  
- 2560 × 1600 px  
- 2880 × 1800 px

---

## Additional Tips

- [ ] Test with different App Store Connect users/Apple ID accounts if your app uses sign-in or account management.
- [ ] If using features unique to certain countries (e.g., AI, subscriptions, or specific APIs), verify compliance and availability for each.
- [ ] Add an accurate, non-generic Description in your app listing.
