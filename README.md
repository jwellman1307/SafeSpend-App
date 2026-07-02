# SpendGuard

SpendGuard is a paycheck-focused Android budgeting app designed to help users quickly understand how much money they have available until their next payday.

The app focuses on one simple question:

> How much can I safely spend before my next paycheck?

SpendGuard helps users track available cash, income sources, upcoming bills, and bills due before the next pay period. It is designed to be simple, readable, and useful for people who want a clear picture of their money without complicated budgeting tools, bank connections, or required logins.

---

## Project Status

SpendGuard is currently in Google Play closed testing and preparing for production access.

The app has completed the required closed testing period with 12 testers, and version 1.1.4 has been released to the closed testing track with additional polish, dark mode support, updated Settings, and refreshed store screenshots.

The current next step is to wait briefly after the v1.1.4 closed testing update, confirm no new issues are reported, and then apply for Google Play production access.

---

## Current Release Status

SpendGuard has been uploaded to Google Play Console and released to closed testing.

Current version: **1.1.4**  
Current release code: **4**  
Testing track: **Closed testing - Alpha**  
Production status: **Preparing to apply for production access**

Recent release work includes:

- Completed Google Play closed testing requirement
- Released v1.1.4 to closed testing
- Added dark mode
- Added Settings screen improvements
- Added tutorial access from Settings
- Added privacy policy access from Settings
- Added app version display
- Updated Play Store screenshots with feature captions
- Updated phone, 7-inch tablet, and 10-inch tablet screenshots
- Tested the updated build on a physical phone

---

## Features

- Track current cash available
- Add multiple income sources
- Set one primary income source
- Support weekly, biweekly, monthly, and one-time income entries
- Add recurring or one-time bills
- See bills due before the next paycheck
- Mark bills as paid
- View available money per day
- Edit or delete income sources and bills
- Update available cash quickly
- Dark mode support
- Settings screen
- Tutorial access from Settings
- Privacy policy access from Settings
- App version display
- Local storage with no account required
- Simple dashboard-first design
- Banner ad support through Google AdMob

---

## Screens

SpendGuard includes the following main screens:

- **Dashboard**  
  Shows amount available, per-day amount, days left, next payday, and bills due before the next paycheck.

- **Income**  
  Allows users to add, edit, delete, and set a primary income source.

- **Bills**  
  Allows users to add, edit, delete, and track recurring or one-time bills.

- **Update Cash Available**  
  Lets users quickly update how much money they currently have available.

- **Edit Income**  
  Allows users to update an existing income source.

- **Edit Bill**  
  Allows users to update an existing bill.

- **Settings**  
  Allows users to toggle dark mode, reopen the getting started tutorial, view the privacy policy, and see the current app version.

---

## Built With

- Kotlin
- Jetpack Compose
- Android Studio
- Room / local device storage
- Google AdMob
- Google Play Console

---

## Design Goals

SpendGuard was built with a focus on:

- Simplicity
- Privacy
- Local-first storage
- Easy navigation
- Clear financial information
- Minimal setup
- No required account or login
- Light and dark mode readability
- A clean app-store-ready user interface

The goal was to create a budgeting tool for users who are focused on managing money between paychecks, rather than building a complex long-term finance platform.

---

## Privacy

SpendGuard does not require an account or login.

Budget information such as income, bills, due dates, and cash available is stored locally on the user's device.

SpendGuard does not require a bank connection and does not collect banking usernames, passwords, account numbers, or card numbers.

Privacy Policy:  
https://sites.google.com/view/trs-safespend-privacy-policy

---

## Testing Completed

SpendGuard has been tested for:

- Fresh install behavior
- App uninstall and reinstall
- Local data persistence
- Income add/edit/delete flow
- Bill add/edit/delete flow
- One-time bill behavior
- Recurring bill behavior
- Paid bill behavior
- Dashboard amount calculations
- Date edge cases
- Navigation stress testing
- Rotation behavior
- Larger screen testing
- Light mode styling
- Dark mode styling
- Settings screen behavior
- Tutorial access from Settings
- Privacy policy access from Settings
- Delete confirmation dialogs
- App version display
- Physical phone testing
- AdMob banner integration
- Release build generation
- Closed testing upload process
- Google Play closed testing requirement

---

## Release Preparation Completed

- App icon created
- Splash screen created
- Privacy policy published
- AdMob app created
- Banner ad integrated
- Test ads verified
- Live ad configuration tested
- Signed Android App Bundle created
- Release key created and backed up
- Google Play Console account created
- Closed testing release created
- Tester access configured
- Closed testing requirement completed
- v1.1.4 update released to closed testing
- Store screenshots updated for phone, 7-inch tablet, and 10-inch tablet layouts
- Production access application preparation started

---

## Screenshots

<table>
  <tr>
    <td align="center">
      <strong>Dashboard</strong><br>
      <img src="Screenshots/01-Dashboard-7.png" width="250">
    </td>
    <td align="center">
      <strong>Income</strong><br>
      <img src="Screenshots/02-Income-7.png" width="250">
    </td>
    <td align="center">
      <strong>Bills</strong><br>
      <img src="Screenshots/03-Bills-7.png" width="250">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Update Cash Available</strong><br>
      <img src="Screenshots/04-UpdateCash-7.png" width="250">
    </td>
    <td align="center">
      <strong>Edit Income</strong><br>
      <img src="Screenshots/05-EditIncome-7.png" width="250">
    </td>
    <td align="center">
      <strong>Edit Bill</strong><br>
      <img src="Screenshots/06-EditBill-7.png" width="250">
    </td>
  </tr>
</table>

---

## App Graphics

<table>
  <tr>
    <td align="center">
      <strong>App Logo</strong><br>
      <img src="Screenshots/SpendGuardLogo.png" width="200">
    </td>
    <td align="center">
      <strong>Feature Graphic</strong><br>
      <img src="Screenshots/SpendGuardFeatureGraphicLogo.png" width="400">
    </td>
  </tr>
</table>

---

## Development Progress

SpendGuard was built through multiple design and testing iterations. The app started as a simple hardcoded dashboard and grew into a full local-storage Android budgeting app with income tracking, bill tracking, paid bill logic, dashboard calculations, settings, dark mode, AdMob integration, privacy policy setup, and Google Play release preparation.

<table>
  <tr>
    <td align="center">
      <strong>Early Dashboard Prototype</strong><br>
      <img src="Development%20Progress/01-dashboard-prototype.png" width="260">
    </td>
    <td align="center">
      <strong>Dashboard Card Iteration</strong><br>
      <img src="Development%20Progress/02-dashboard-card-iteration.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Income Card Iteration</strong><br>
      <img src="Development%20Progress/03-income-card-iteration.png" width="260">
    </td>
    <td align="center">
      <strong>Income and Bill Form Iteration</strong><br>
      <img src="Development%20Progress/04-income-add-bill.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Primary Income Logic</strong><br>
      <img src="Development%20Progress/05-income-primary.png" width="260">
    </td>
    <td align="center">
      <strong>Income Delete Flow</strong><br>
      <img src="Development%20Progress/06-income-delete.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Bills Card Iteration</strong><br>
      <img src="Development%20Progress/07-bills-card.png" width="260">
    </td>
    <td align="center">
      <strong>Bills Delete Flow</strong><br>
      <img src="Development%20Progress/08-bills-delete.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Date Picker Added</strong><br>
      <img src="Development%20Progress/09-date-picker-added.png" width="260">
    </td>
    <td align="center">
      <strong>Add Income Flow</strong><br>
      <img src="Development%20Progress/10-add-income.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Date Validation Error</strong><br>
      <img src="Development%20Progress/11-data-validation-error.png" width="260">
    </td>
    <td align="center">
      <strong>Edit Bill Flow</strong><br>
      <img src="Development%20Progress/12-edit-bill.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Add Bill Flow</strong><br>
      <img src="Development%20Progress/13-add-bill.png" width="260">
    </td>
    <td align="center">
      <strong>Overdue Bill Logic</strong><br>
      <img src="Development%20Progress/14-overdue-bill.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>AdMob Test Integration</strong><br>
      <img src="Development%20Progress/15-ad-testing.png" width="260">
    </td>
    <td align="center">
      <strong>SpendGuard Rebrand</strong><br>
      <img src="Development%20Progress/16-Rebrand.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Dark Mode Conversion</strong><br>
      <img src="Development%20Progress/DarkModeConversion.png" width="260">
    </td>
    <td align="center">
      <strong>Dark Mode Dashboard</strong><br>
      <img src="Development%20Progress/DarkModeDashboard.png" width="260">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Settings Dark Mode</strong><br>
      <img src="Development%20Progress/SetttingDarkMode.png" width="260">
    </td>
    <td align="center">
      <strong>Tutorial Setup</strong><br>
      <img src="Development%20Progress/TutorialSetup.png" width="260">
    </td>
  </tr>
</table>

---

## Development Summary

SpendGuard was created as a practical Android app focused on solving a simple budgeting problem. The first version went through multiple rounds of layout changes, naming changes, testing, and release preparation before being uploaded to Google Play closed testing.

The project includes:

- A full Android app built with Kotlin and Jetpack Compose
- Local data storage
- Income and bill management
- Pay-period based dashboard calculations
- Paid and overdue bill handling
- Dark mode support
- Settings screen
- Tutorial and privacy access
- AdMob banner support
- Privacy policy setup
- Google Play closed testing release
- Updated Play Store screenshots
- Production access preparation

---

## Production Readiness

SpendGuard has completed closed testing requirements and is preparing for production access on Google Play.

Before applying for production, the latest v1.1.4 closed testing build was tested on a physical phone and reviewed for visual polish, dark mode behavior, Settings functionality, privacy policy access, tutorial access, and app flow stability.

Current production readiness status:

- Closed testing completed
- Tester access configured
- v1.1.4 released to closed testing
- Store screenshots updated
- Physical phone test completed
- Production access application pending

---

## Developer

Created by July Wellman  
Tiny Rebellion Studios
