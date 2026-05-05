# Sample Help Desk Tickets

## Overview
This section contains sample help desk tickets demonstrating common Tier 1 IT support scenarios, troubleshooting steps, and resolution documentation.

---

## Ticket 1: Password Reset Request

**Ticket ID:** 1001  
**User:** John Doe  
**Department:** Sales  
**Issue:** Unable to log in to Microsoft 365 account  

**Description:**  
User reports being locked out after multiple failed login attempts.

**Troubleshooting Steps:**
- Verified user identity (employee ID + phone confirmation)
- Checked account status in Entra ID (account locked)
- Reset password and unlocked account
- Enforced password change at next login

**Resolution:**  
User successfully logged in after password reset. MFA confirmed active.

**Status:** Resolved

---

## Ticket 2: MFA Setup Issue

**Ticket ID:** 1002  
**User:** Sarah Smith  
**Department:** HR  
**Issue:** Unable to complete MFA setup  

**Description:**  
User reports issues receiving verification code during MFA setup.

**Troubleshooting Steps:**
- Verified correct phone number was registered
- Guided user through MFA reconfiguration
- Tested alternative authentication method (Authenticator app)

**Resolution:**  
MFA successfully configured using mobile app.

**Status:** Resolved

---

## Ticket 3: Access Denied to SharePoint

**Ticket ID:** 1003  
**User:** Michael Brown  
**Department:** Finance  
**Issue:** Cannot access shared folder  

**Description:**  
User receives “Access Denied” when attempting to open SharePoint folder.

**Troubleshooting Steps:**
- Verified user group membership
- Confirmed correct permissions required for role
- Added user to appropriate security group

**Resolution:**  
Access restored after group assignment.

**Status:** Resolved

---

## Ticket 4: Suspicious Email Report

**Ticket ID:** 1004  
**User:** Emily Davis  
**Department:** Marketing  
**Issue:** Received suspicious email  

**Description:**  
User reports email requesting urgent password reset with external link.

**Troubleshooting Steps:**
- Reviewed sender domain (spoofed)
- Confirmed phishing indicators present
- Instructed user not to interact with email

**Resolution:**  
Email confirmed as phishing. User deleted message. No compromise detected.

**Status:** Resolved / Monitored

---

## Ticket 5: New User Onboarding

**Ticket ID:** 1005  
**User:** New Hire (David Wilson)  
**Department:** Operations  
**Issue:** New account setup  

**Description:**  
New employee requires system access prior to start date.

**Actions Taken:**
- Created account in Entra ID
- Assigned Microsoft 365 license
- Added to department security groups
- Enabled MFA
- Sent onboarding instructions

**Resolution:**  
User account fully provisioned and ready for first login.

**Status:** Completed

---

## Notes
- All tickets follow standard IT support procedures
- Identity verification is required before sensitive actions
- Security best practices are applied in all scenarios
