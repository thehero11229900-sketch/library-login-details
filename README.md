# library-login-details

# Library Login System

## 1. Introduction
A secure authentication system for library members and administrators.

## 2. Purpose
To provide secure login, session control, and role-based access.

## 3. Functional Requirements

1. Member and librarian login.  
2. Password reset via email/OTP.  
3. Auto logout after 30 minutes.  
4. CAPTCHA after failed attempts.  
5. Lock account after 5 failed attempts.  
6. Remember me (7 days).  
7. Login audit trail.  

## 4. Non-Functional Requirements

- Encrypted password storage.  
- Response time < 2 seconds.  
- Secure session tokens.  
- Audit log retention.  

## 5. Acceptance Criteria

- AC-1: Valid login → dashboard.  
- AC-2: Invalid → error message.  
- AC-3: 5 failed attempts → 1-hour lock.  
- AC-4: Remember me → 7 days login.  
- AC-5: Reset link expires in 24h.  
- AC-6: Librarian sees admin options.  

## 6. Compliance & Auditing

- Data privacy compliance.  
- Login activity audit logs.
