# Bug Report — Login button not clickable on mobile

**ID:** BUG-LOGIN-001  
**Title:** Login button not clickable on mobile devices  
**Severity:** High • **Priority:** P1  
**Environment:** Chrome 120 — Android 13 (also observed on iOS 17)

## Steps to Reproduce
1. Open the login page on a mobile device
2. Enter valid email and password
3. Tap the **Login** button

## Expected Result
User should sign in and be redirected to the dashboard.

## Actual Result
The **Login** button is not clickable on mobile. User cannot sign in.

## Notes
- Works on desktop browsers
- Likely CSS overlay / JS event-blocking on mobile viewport
- Impact: high — blocks mobile users from accessing the app

## Evidence
N/A (example report)

**Reported by:** Ana Karoliny • **Date:** 14 Sep 2025
