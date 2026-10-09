# FE Exam Study Plan — 2026 Autumn (16-day sprint)

**Assumed exam date: Sunday, Oct 25, 2026.** ITPEC autumn exams are usually held on the last Sunday of October, but I couldn't confirm the 2026 date online. Check it on philnits.org and shift the plan if it's different.

**Your time:** 1–2 hrs on weekdays, 4–5 hrs on weekends.
**Sources used:** FE Exam Preparation Book Vol.1 and Vol.2, plus the past exams in your folder (2023S/A in the old AM/PM format; 2024S–2026S in the current Subject A/B format).

---

## 1. What the exam looks like (from your 2024S–2026S papers)

| | Subject A | Subject B |
|---|---|---|
| Format | 60 multiple-choice questions (Q1 is the answer-sheet sample) | 20 questions, all required |
| Time | 90 min, about **1.5 min per question** | 100 min, about **5 min per question** |
| Content | Broad theory: technology, management, strategy | Q1–16: pseudocode algorithms. Q17–20: security case scenarios |

### Subject A always follows the same order
I checked all five current-format papers. The topics come in the same question ranges every time (±1), so you can drill one topic by pulling the same question numbers from every paper.

| Q range | Domain | Approx. # Qs | Vol.1 chapter |
|---|---|---|---|
| Q2–7 | CS fundamentals (radix, logic, data structures, sorting, probability, automata) | 6 | Ch1 |
| Q8–17 | Computer systems (CPU/MIPS, cache, HDD, RAID, OS scheduling, paging, availability, multimedia) | 10 | Ch2 |
| Q18–22 | Database (ER, normalization, SQL, ACID, locks, logs) | 5 | Ch5 |
| Q23–27 | Network (OSI, router/L2/L3, subnet/broadcast, ARP, DNS, NAT) | 4–5 | Ch4 |
| Q27–33 | Security (malware, attacks, crypto/signatures, WAF/IDS/SIEM, MFA, CSIRT) | 7 | Ch6 (plus past exams) |
| Q34–40 | Development (UML, OOP, design patterns, testing, Agile/Scrum/XP, CMMI) | 6–7 | Ch3 (plus past exams) |
| Q41–45 | Management (arrow diagram, EVM, FP/COCOMO, SLA downtime, ITSM, audit) | 5 | **Not in the book, so use past exams** |
| Q46–60 | Strategy (BPR, BSC, marketing, PLC, ERP/SCM, IoT/AI, accounting, law/licensing) | **15** | Ch7 (partial) plus past exams |

**What this means for your plan:**
- **Strategy and management are 20 of 60 questions (33%)**, but Vol.1 covers only part of them. Most people under-study this area, and it's where you can gain the most points fastest.
- **Security counts twice:** about 7 questions in A plus 4 in B, roughly 18% of your total effort. It deserves dedicated days.
- Vol.1 is from the old syllabus. Use it for the core theory, and use past exams for the modern terms (cloud, edge, AI/ML, Scrum, WAF, SPF, SIEM).

### Subject B also follows a pattern
| Q | What appears (2024S–2026S) |
|---|---|
| Q1–7 | Basic control flow and number problems: grading, digit sum, GCD, primes, Fibonacci, perfect/Harshad numbers, quadratic equations, procedure call order |
| Q8–10 | Data structures: **stack/queue (Q8), tree or graph traversal (Q9), linked list (Q10, in all 5 papers)** |
| Q11 | **Sorting (in all 5 papers):** bubble, counting, generic sort |
| Q12–13 | Strings and arrays: palindrome, substring, Hamming distance, brackets, isomorphic strings |
| Q14–16 | Applied/data: cosine/Jaccard similarity, IDF, bag of words, percentile, sin/cos approximation, simulation |
| Q17–20 | Security scenarios: ransomware, log analysis, SQLi, password attacks/entropy, cloud/REST API, DB backup/mirroring |

**About Vol.2:** It's written for the **old** afternoon exam (C/Java programs, select-from-8-fields). Ch6 *Algorithms* and Ch7 *Program Design* still help for Subject B. **Skip Ch8 (C/Java)**, because the exam now uses only pseudocode.

---

## 2. Rules for the whole sprint

1. **Keep an error log** (notebook or spreadsheet). For every wrong or guessed answer, write: exam/Q#, topic, *why* you got it wrong (didn't know / misread / calculation slip / ran out of time), and the correct reasoning. Use it for your Oct 22–24 review.
2. **Trace by hand on paper.** For every Subject B question, write a variable table (one column per variable, one row per loop iteration). This is the most important Subject B skill, and you can't skip it on exam day.
3. **Time every mock.** Set a timer for 90 min (A) or 100 min (B). Don't pause it.
4. **Don't read the book cover to cover.** For each chapter: skim the section, do its Quiz, do its "Questions and Answers," then drill the matching past-exam range.

---

## 3. Day-by-day schedule

### Week 1: Diagnose, then build the core
| Date | Time | Subject A | Subject B / other |
|---|---|---|---|
| **Fri Oct 9** | 1.5 h | **Diagnostic:** 2026S Subject A, timed 90 min. Score it, then fill in your error log by domain using the table above. | — |
| **Sat Oct 10** | 4 h | Review the 2026S A errors (1 h) | **Diagnostic:** 2026S Subject B, timed 100 min. Then study the **pseudocode notation page** at the front of the paper until you know it by heart (`←`, `for/endfor`, arrays starting at 1 vs 0, `.next`, class/instance syntax). Review every wrong answer by tracing it. |
| **Sun Oct 11** | 4–5 h | **Vol.1 Ch1** (1.1 radix and two's complement, 1.2 logic/BNF/RPN, 1.3 data structures, 1.4 search/sort/graphs) plus the chapter Q&A | Drill **B Q1–7** from 2025S and 2024S (14 questions, about 5 min each) |
| **Mon Oct 12** | 1.5 h | **Vol.1 2.1 Hardware and 2.4 Performance/Reliability.** Practice the calculations: MIPS, cache effective access time, HDD access time, availability (series/parallel), RAID levels | Drill A **Q8–17** from 2025S |
| **Tue Oct 13** | 1.5 h | **Vol.1 2.2 OS, 2.3 System configuration.** Practice: scheduling (FCFS/SJF/RR/priority), page replacement (FIFO/LRU), CPU utilization | Drill A **Q8–17** from 2025A, plus B **Q8 (stack/queue)** from 2026S and 2025A |
| **Wed Oct 14** | 1.5–2 h | **Vol.1 Ch5 Database:** normalization (1NF→3NF, transitive dependency), SQL (GROUP BY/HAVING, joins, subqueries), ACID, locks, logs/recovery | Drill A **Q18–22** from 2024S, 2024A, 2025S, 2025A (20 questions) |
| **Thu Oct 15** | 1.5 h | **Vol.1 Ch4 Network:** OSI layers and devices, TCP/IP, ARP, DNS, NAT, QoS, **subnet/broadcast calculation** (appeared in both 2024 papers) | Drill A **Q23–27** from all 4 remaining papers |
| **Fri Oct 16** | 1.5–2 h | **Vol.1 Ch6 Security**, then the modern terms from past exams: ransomware, Trojan, DNS cache poisoning, SQLi, XSS, phishing/social engineering, WAF, IDS/IPS, SIEM, SPF, CSIRT, MFA, digital signatures (which key signs and which verifies), CIA triad | Drill A **Q27–33** from all papers. Make flashcards for every term you missed. |

### Weekend 2: Core of Subject B, plus first full mock
| Date | Time | Plan |
|---|---|---|
| **Sat Oct 17** | 5 h | **Morning (3.5 h): Full mock under exam timing.** 2025S Subject A (90 min), break, 2025S Subject B (100 min). **Afternoon (1.5 h):** Review the errors and update the error log. |
| **Sun Oct 18** | 5 h | **Data structures for Subject B (3 h):** Do **Q8–Q11 from all five papers** (20 questions on stack/queue, tree/graph, linked list, sort). For linked lists, draw boxes and arrows for every pointer change. Then read **Vol.2 Ch6 Algorithms** (Q1–Q2). **Then (2 h):** Vol.1 **Ch3 System development** plus a past-exam supplement on UML diagram types, OOP (encapsulation, abstraction, polymorphism), design patterns (Adapter, etc.), testing (white/black box, decision/condition coverage, integration/acceptance), Agile/Scrum/XP, maintenance types, CMMI levels. Drill A **Q34–40**. |

### Week 3: Management/strategy, applied Subject B, final review
| Date | Time | Subject A | Subject B / other |
|---|---|---|---|
| **Mon Oct 19** | 1.5–2 h | **Management (A Q41–45, all 5 papers = 25 questions).** Learn: **arrow diagram / critical path**, WBS, **EVM** (EV/PV/AC, SPI/CPI), **function points**, COCOMO, **SLA downtime calculation**, incident vs problem management, MTD, system audit. Not in the book, so learn from the explanations in the questions themselves. | — |
| **Tue Oct 20** | 1.5–2 h | **Vol.1 Ch7** (7.1 strategy, 7.2 accounting, 7.3 OR/IE/statistics) plus strategy drills **A Q46–60** from 2025S and 2025A. Calculations to practice: **break-even point** (2026S Q59), **depreciation** (2025S Q60), financial statements, OC curve. | — |
| **Wed Oct 21** | 1.5–2 h | Strategy drills **A Q46–60** from 2024S and 2024A. Make flashcards: BPR, BSC perspectives, PLC stages, SCM/ERP/CRM/MRP, franchising, M&A, sharing economy, Green IT, smart grid, RFID, ML vs. deep learning, licensing (shrink-wrap, cross-licensing), WTO/TBT. | — |
| **Thu Oct 22** | 1.5–2 h | — | **Subject B applied plus security.** Do **B Q12–16** from 2024A and 2025A (string/array/data-science). Then **B Q17–20** from 2025S and 2025A (8 security scenarios). For security scenarios, underline every fact in the story; the answer is almost always tied to one specific detail. |
| **Fri Oct 23** | 1.5 h | **Last A mock:** 2024A Subject A, timed 90 min. Quick review. | — |
| **Sat Oct 24** | 3 h max | **No new topics.** Do 2024S Subject B timed (100 min), then review the **error log and flashcards** only. Prepare pencils, eraser, and admission card. Sleep early. | |
| **Sun Oct 25** | — | **EXAM DAY.** Subject A 9:30–11:00, Subject B 12:30–14:10 (per the 2026S papers; confirm on your admission card). | |

**Still unused if you have extra time:** 2024S Subject A, 2024A Subject B Q1–11 and Q17–20, and the 2023S/2023A papers. The 2023 AM papers have 80 questions in the old format but are still good topic drills. In the 2023 PM papers, Q1 (security) and Q6 (pseudo-language algorithm) are good extra Subject B practice. Skip Q7–Q8 (C/Java).

---

## 4. Calculations that appear repeatedly (practice until they're automatic)

| Topic | Where it showed up |
|---|---|
| Radix conversion, two's complement, fractions | A Q2 in 2025S, 2025A, 2026S |
| Reverse Polish (postfix) notation | 2024S Q3, 2024A Q2, 2026S Q5 (3 of 5 papers) |
| Probability / combinatorics | 2024S Q2, 2025A Q3 |
| MIPS / clock cycles / CPI | 2024A Q8, 2025S Q8 |
| Cache effective access time | 2025S Q10, 2026S Q10 |
| HDD average access time | 2025A Q9 |
| Availability (series/parallel), MTBF/MTTR | 2025S Q12 |
| Page replacement (FIFO/LRU), virtual→physical address | 2025A Q15, 2025S Q13 |
| CPU scheduling / utilization | 2026S Q14–15, 2025A Q13 |
| Subnet broadcast address (/22, /23) | 2024S Q24, 2024A Q24 |
| Critical path (arrow diagram) | 2024S Q41, 2025A Q41 |
| SLA maximum downtime | 2025S Q43, 2025A Q43 |
| Function points / cost estimation | 2026S Q42, 2025A Q42 |
| Break-even point, depreciation | 2026S Q59, 2025S Q60 |

---

## 5. Exam-day strategy

- **Subject A (1.5 min/question):** Do one fast pass and answer every term/definition question immediately. Mark the calculation questions and come back to them. Never leave a blank, because there's no penalty for guessing.
- **Subject B (5 min/question):** If a trace hasn't converged after about 7 minutes, guess, mark it, and move on. Do **Q17–20 (security) first or early**: they're reading comprehension, faster, and more predictable than the algorithm questions.
- For "fill in the blank" pseudocode: **test each answer choice against a tiny input** (n = 1 or 2, an array of 2–3 elements). Elimination is often faster than deriving the code.

---

## 6. How to adjust after the diagnostics (Oct 9–10)
- **A score < 50%:** Keep the plan as is, but cut the Wed Oct 21 strategy flashcards in half and spend that time on whichever technology domain scored lowest.
- **B score < 50%:** Your bottleneck is almost certainly tracing speed, not knowledge. Add 20 minutes of hand-tracing every weekday (one past B question per day from the unused list).
- **Both ≥ 65%:** Swap some reading for more timed mixed drills. Speed matters more than coverage at that point.
