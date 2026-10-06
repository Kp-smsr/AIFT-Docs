# Test Cases

This page describes the standard format for test cases and includes examples.

## Test Case Format

- **Test Case ID:** TC-001
- **Test Scenario:** Verify user login with valid credentials
- **Preconditions:** Test environment up; test user exists
- **Test Data:** username: `tester`, password: `P@ssw0rd` (use secure storage in real projects)
- **Steps:**
  1. Navigate to login page
  2. Enter username and password
  3. Click login
- **Expected Result:** User is successfully authenticated and redirected to dashboard
- **Actual Result:** (to be filled during execution)
- **Status:** Not executed / Passed / Failed
- **Evidence:** Screenshots, logs, or traces

## Example Test Cases

- **TC-002:** Password recovery flow
  - Preconditions: Email service available
  - Steps: Request password reset, confirm email received, reset password
  - Expected: Reset completes and user can login with new password
