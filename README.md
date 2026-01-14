# Security Vulnerability Profile

A showcase of security vulnerabilities discovered and responsibly disclosed across various platforms.

---

## Summary

| Severity | Total | Triaged |
|----------|-------|---------|
| Critical | 3 | 2 |
| High | 3 | 1 |
| Medium | 1 | 0 |

---

## Vulnerabilities

### Critical

```
┌─────────────────────────────────────────────────────────────────┐
│ SQL Injection (SQLi)                                            │
├─────────────────────────────────────────────────────────────────┤
│ Status: Triaged                                                 │
│ Impact: Database compromise, unauthorized data access           │
└─────────────────────────────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────────┐
│ Remote Code Execution (RCE)                                     │
├─────────────────────────────────────────────────────────────────┤
│ Status: Triaged                                                 │
│ Impact: Complete system compromise                              │
└─────────────────────────────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────────┐
│ OTP Bypass                                                      │
├─────────────────────────────────────────────────────────────────┤
│ Status: Triaged                                                 │
│ Impact: Authentication bypass, unauthorized account access      │
└─────────────────────────────────────────────────────────────────┘
```

### High

```
┌─────────────────────────────────────────────────────────────────┐
│ Password Hash Exposure in API Response                         │
├─────────────────────────────────────────────────────────────────┤
│ Status: Pending Triage                                          │
│ Impact: Credential compromise via hash cracking                 │
└─────────────────────────────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────────┐
│ Reflected XSS in Avatar Image Endpoint                         │
├─────────────────────────────────────────────────────────────────┤
│ Status: Pending Triage                                          │
│ Impact: Session hijacking, credential theft                     │
└─────────────────────────────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────────┐
│ IDOR in EdTech Startup                                          │
├─────────────────────────────────────────────────────────────────┤
│ Status: Triaged                                                 │
│ Impact: Unauthorized access to user data                        │
└─────────────────────────────────────────────────────────────────┘
```

### Medium

```
┌─────────────────────────────────────────────────────────────────┐
│ Stack Trace Exposure via Improper Input Validation             │
├─────────────────────────────────────────────────────────────────┤
│ Status: Pending Triage                                          │
│ Impact: Information disclosure, internal architecture exposure  │
└─────────────────────────────────────────────────────────────────┘
```

---

## Disclosure Policy

All vulnerabilities reported following responsible disclosure practices. Technical details withheld to protect affected systems.
