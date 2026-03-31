# User Story 8

## User Story
As a patient, I want to use Google sign-in or OTP fallback so that I have flexible login options.

## Story Points
5 story points

## Acceptance Criteria
### Patient
- Patients should be able to choose Google sign-in as an alternative to standard login.
- If Google sign-in is unavailable or not used, patients should be able to request a one-time password as a fallback login option.
- The one-time password should be sent to the patient's registered contact method and should expire after a limited time.
- The system should prevent reuse of the same one-time password after successful login.
- Patients who authenticate successfully through either method should be signed in and redirected to the portal.
