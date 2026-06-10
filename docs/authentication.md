# Project Homepage > Authentication

![Authentication Mockup](../public/logo.png)

---

## Functional Description
The **Authentication** module provides a secure and flexible way for users to access the GamâLokal platform. It supports traditional email/password registration as well as modern social login options.

Key features include:
- **Social Login:** Sign in quickly using Google OAuth.
- **Role-Based Accounts:** Users can choose to join as a "Client" (to buy art/commissions) or an "Artist" (to sell and take requests).
- **Secure Sessions:** Managed through Supabase Auth with encrypted credential storage.
- **Onboarding Workflow:** Specialized setup for Artists to define their specialty, location, and price range.

---

## Use Case Scenario

| Actor | Action | System Response |
| :--- | :--- | :--- |
| User | Navigates to the Sign Up page | System displays registration form and Google login option. |
| User | Enters email, name, and password | System validates input and creates a pending account. |
| User | Selects "Client" or "Artist" role | System updates the user profile and directs to the appropriate dashboard or onboarding. |
| User | Clicks "Continue with Google" | System redirects to Google for authentication and creates/links account. |
| Artist | Completes onboarding form | System saves specialty and location details and activates the artist profile. |

---

[← Back to Project Homepage](project-homepage.md)

© 2026 Arktic
