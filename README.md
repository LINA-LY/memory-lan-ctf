# Memory Lane CTF - Write-up

- Category: Misc
- *Flag:* `shellmates{history_repeats_when_forgotten}`
- challenge website: https://lina-ly.github.io/memory-lan-ctf/
---

##  Challenge Description

*Sometimes the past whispers secrets if you know what to listen for. Chat with an old friend who remembers everything... almost.*

---

## Solution

### Stage 1: Company Identification
**Clue:** "Company starting with Y, CEO Marissa Mayer"  
**Keyword:** `yahoo` or `marissa`  
**Research:** Google "Marissa Mayer CEO" → Yahoo

### Stage 2: Breach Timeline
**Clue:** "When did it happen? 2012, 2013, or 2014? BILLIONS of accounts"  
**Keyword:** `2013` or `billion`  
**Research:** Yahoo breach occurred in 2013 (3 billion accounts)

### Stage 3: Attack Attribution
**Clue:** "Sophisticated foreign actors, forged authentication cookies"  
**Keyword:** `state-sponsored` or `forged` or `cookies`  
**Research:** State-sponsored attack attributed to Russia

### Stage 4: Second Major Breach
**Clue:** "2017 breach, credit reporting agency, one of the big three"  
**Keyword:** `equifax`  
**Research:** Equifax breach (2017) - 147M users compromised

### Stage 5: Technical Vulnerability
**Clue:** "Apache something, Java web framework, known vulnerability"  
**Keyword:** `apache` or `struts` or `cve-2017-5638`  
**Research:** Apache Struts vulnerability CVE-2017-5638

### Stage 6: Security Lesson
**Clue:** "Failures to REMEMBER lessons, learn from history"  
**Keyword:** `remember` or `learn` or `history`  
**Concept:** "Those who cannot remember the past are condemned to repeat it"

---

## Quick Reference

| Stage | Keyword | Info |
|-------|---------|------|
| 1 | `yahoo` | Company with Marissa Mayer as CEO |
| 2 | `2013` | Year of Yahoo breach (3B accounts) |
| 3 | `state-sponsored` | Russian state-sponsored attack |
| 4 | `equifax` | 2017 credit bureau breach (147M users) |
| 5 | `apache struts` | CVE-2017-5638 vulnerability |
| 6 | `remember` | Learn from history |

**Commands:**
- Type `hint` for clues
- Type keywords naturally in conversation

**Flag:** `shellmates{history_repeats_when_forgotten}`

---

## Key Learnings

- **Yahoo (2013):** 3 billion accounts, state-sponsored attack, forged cookies
- **Equifax (2017):** 147M users, unpatched Apache Struts (CVE-2017-5638)
- **Lesson:** Organizations must learn from past security incidents

---

