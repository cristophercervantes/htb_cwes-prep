# HTB CWES Preparation

> My personal prep repo for the **HackTheBox Certified Web Exploitation Specialist (CWES)** exam. Contains notes, techniques, and references for every module in the path — organized by topic, not by HTB's module order.

This is a living document. Updated regularly as I progress.

---

## Target Certification

- **CWES** — HackTheBox Certified Web Exploitation Specialist
- **Path** — Web Penetration Tester (Job Role Path)

---

## Roadmap

| Phase | Focus |
|-------|-------|
| 1 | Web Development Fundamentals |
| 2 | Tool Usage |
| 3 | Vulnerabilities |
| 4 | Practical & Process |

---

## Phase 1 — Web Development Fundamentals

Foundational knowledge required before touching any tooling or exploitation.

| # | Topic                                  | Link |
|---|----------------------------------------|------|
| 1 | Git Basic                              |      |
| 2 | PHP                                    |[Start learning from here](https://github.com/cristophercervantes/htb_cwes-prep/blob/main/Web%20Dev%20Foundation%20for%20Web%20Hacking/PHP/1.%20Getting%20Started%20with%20PHP.md)  |
| 3 | Information Gathering                  |      |

---

## Phase 2 — Tool Usage

Core tools used throughout web pentesting. Get these down before Phase 3.

| # | Topic | Resource | 
|---|-------|----------|
| 1 | Using Web Proxies | HTB Academy | 
| 2 | Web Fuzzing | [Start learning from here](https://github.com/cristophercervantes/htb_cwes-prep/blob/main/Tools%20Usage/Web%20Fuzzing/1.%20Introduction.md) | 

---

## Phase 3 — Vulnerabilities

| # | Module | Link to learn | Status |
|---|--------|----------|--------|
| 1 | Cross-Site Scripting (XSS) | Injection | Pending |
| 2 | SQL Injection Fundamentals | [Start learning from here](https://github.com/cristophercervantes/htb_cwes-prep/blob/main/Vulnerabilities/SQL-Injection/1.%20Databases.md) | Pending |
| 3 | SQLMap Essentials | Injection | Pending |
| 4 | Command Injections | Injection | Pending |
| 5 | File Inclusion | File | Pending |
| 6 | File Upload Attacks | File | Pending |
| 7 | Server-Side Attacks | Server | Pending |
| 8 | Broken Authentication | Authentication | Pending |
| 9 | Login Brute Forcing | Authentication | Pending |
| 10 | Web Attacks | Mixed | Pending |
| 11 | API Attacks | API | Pending |
| 12 | Attacking GraphQL | API | Pending |
| 13 | Attacking Common Applications | Mixed | Pending |

> Status: `Pending` → `In Progress` → `Completed`

---

## Phase 4 — Practical & Process

The methodology and real-world application side of web pentesting.

| # | Topic | Resource | Link |
|---|-------|----------|------|
| 1 | Bug Bounty Hunting Process | HTB Academy | |
| 2 | HTB Machines — Web | Hack The Box | |
| 3 | CTF Writeups | | |

---

## Repo Structure

```
htb_cwes-prep/
│
├── phase-1_web-basics/
│   ├── web-requests/
│   ├── intro-to-web-apps/
│   ├── javascript-deobfuscation/
│   └── information-gathering/
│
├── phase-2_tools/
│   ├── web-proxies/
│   └── web-fuzzing/
│
├── phase-3_vulnerabilities/
│   ├── xss/
│   ├── sql-injection/
│   ├── sqlmap/
│   ├── command-injection/
│   ├── file-inclusion/
│   ├── file-upload/
│   ├── server-side-attacks/
│   ├── broken-auth/
│   ├── brute-forcing/
│   ├── web-attacks/
│   ├── api-attacks/
│   ├── graphql/
│   └── common-applications/
│
├── phase-4_practical/
│   ├── bug-bounty-process/
│   ├── htb-machines/
│   └── writeups/
│
└── README.md
```

---

## Progress Tracker

| Module | Status |
|--------|--------|
| Web Requests | Completed |
| Introduction To Web Applications | Completed |
| JavaScript Deobfuscation | In Progress |
| Information Gathering - Web Edition | Pending |
| Using Web Proxies | In Progress |
| Web Fuzzing | In Progress |
| Cross-Site Scripting (XSS) | Pending |
| SQL Injection Fundamentals | Pending |
| SQLMap Essentials | Pending |
| Command Injections | Pending |
| File Inclusion | In Progress |
| File Upload Attacks | Pending |
| Server-Side Attacks | Pending |
| Login Brute Forcing | Pending |
| Broken Authentication | Pending |
| Web Attacks | Pending |
| API Attacks | In Progress |
| Attacking GraphQL | Pending |
| Attacking Common Applications | Pending |
| Bug Bounty Hunting Process | In Progress |

---

## Disclaimer

Everything in this repo is for **educational and ethical hacking purposes only**. All practice is done in legal, authorized environments (HTB Academy, HTB labs). Never use these techniques against systems you don't have explicit permission to test.

---

*Started: 2026 | Maintained by [@cristophercervantes](https://github.com/cristophercervantes)*
