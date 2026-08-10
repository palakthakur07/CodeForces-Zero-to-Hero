# 🚀 8-Week Roadmap: LeetCode → Codeforces Specialist

A structured, self-paced plan to go from "I can solve LeetCode problems" to **Codeforces Specialist (1400+)** in 8 weeks — with an optional 3-week extension to **Expert (1600+)**.

---

## Who This Is For

You've solved LeetCode problems and understand basic DSA, but Codeforces feels like a different universe: weird I/O, tight time limits, cryptic problem statements, and ratings that make no sense.

**This roadmap bridges that gap.**

### Prerequisites
- Solved 100+ LeetCode problems (Easy/Medium)
- Comfortable with basic data structures (arrays, stacks, queues, trees)
- Understand Big O notation
- Can code in C++ (or willing to switch)

### Goal
- 🎯 **Specialist (1400+)** by end of Week 8
- 🏆 **Expert (1600+)** by end of Week 11 (optional extension)

---

## LeetCode vs. Codeforces — The Gap

| Aspect | LeetCode | Codeforces |
|---|---|---|
| I/O | Function signature given | Read from stdin, print to stdout |
| Time Limit | Generous (often 1–2s) | Tight (1–2s for 10⁶ ops) |
| Problem Style | Clear, structured | Story-based, need to extract the problem |
| Test Cases | Run before submit | Pretests only, system tests after |
| Edge Cases | Often handled | Will fail you brutally |
| Speed | Accuracy matters | Speed + accuracy both matter |
| Multiple Tests | Usually single | Often T test cases in one run |

---

## Week-by-Week Breakdown

### Week 1 — CF Environment & Speed
- Set up VS Code with CP extensions, build a starter template
- Learn fast I/O (`ios::sync_with_stdio(false)`, `cin.tie(nullptr)`)
- Solve 10× rated-800 problems, focusing on reading problems correctly
- Run 2–3 virtual Div 4 contests (A–D), upsolve everything unsolved

**Target:** 20 problems solved · 2–3 virtual Div 4 contests

### Week 2 — Implementation, Simulation & Basic Bitwise
- String/array manipulation, simulation problems
- Frequency counting with maps, min/max, pairs, coordinates
- Bitwise basics: AND/OR/XOR, shifts, odd/even checks, XOR properties
- 1–2 virtual Div 3 contests (A–C)

**Target:** 25 problems (800–1000) · 1–2 virtual Div 3 contests

### Week 3 — Math & Number Theory Basics
- Divisibility rules, GCD/LCM, prime checking, factor counting
- Modular arithmetic (`MOD = 1e9+7`), overflow avoidance, mod power
- 15 math-tagged problems + 1 virtual contest

**Target:** 20 problems (800–1000) · solid mod-arithmetic understanding

### Week 4 — Sorting & Greedy
- Custom comparators, sorting pairs/tuples/indices, coordinate compression
- Greedy: when it works, exchange argument, interval scheduling
- 1 virtual Div 2 contest (A–C) + aggressive upsolving

**Target:** 20 problems (900–1100) · greedy intuition

### Week 5 — Binary Search & Two Pointers
- Binary search on sorted arrays, lower/upper bound, binary search on answer
- Two pointers / sliding window / subarray problems
- Prefix sums, difference arrays, range queries

**Target:** 20 problems (1000–1200) · 2 virtual contests

### Week 6 — Graphs Basics
- Adjacency list representation, directed vs. undirected
- DFS/BFS, connected components, cycle detection
- Grid graphs, flood fill, 4- vs. 8-directional movement

**Target:** 15 graph problems (1000–1300) · solid DFS/BFS skills

### Week 7 — Dynamic Programming Introduction
- DP fundamentals: memoization vs. tabulation, state & transition
- 1D DP: coin change, LIS, subset sum, unbounded knapsack
- 10 DP problems from CSES/AtCoder + 1 virtual contest

**Target:** 15 DP problems · comfortable with state design

### Week 8 — Contest Strategy & Consolidation
- Time management, when to skip, reading problems effectively
- Review all WA/TLE submissions → personal mistake log
- 3 virtual Div 2 contests + 1 live contest

**Target:** 3 virtual contests · 1 live contest · full mistake review

---

## Weeks 9–11 — Road to Expert (Optional Extension)

| Week | Focus |
|---|---|
| 9 | 2D/Grid DP, Tree basics & Tree DP · 2 virtual contests |
| 10 | DSU (Union-Find), Segment Tree basics · focus on 1400–1600 problems |
| 11 | Bit manipulation, String basics · contest marathon (3 virtual + 1–2 live) |

---

## Daily Schedule Template

```
┌─────────────────────────────────────────────────────┐
│           IDEAL CP DAY (2–3 hours)                   │
├─────────────────────────────────────────────────────┤
│  0:00 – 0:30   Upsolve yesterday's problems           │
│  0:30 – 1:30   Solve 2–3 new problems                 │
│  1:30 – 2:00   Read editorial for any you couldn't    │
│  2:00 – 2:30   Review and add to notes                │
│  (Weekend)     Virtual contest + full upsolve         │
└─────────────────────────────────────────────────────┘
```

---

## Progress Tracking

| Week | Expected Rating | Problems Solved (cumulative) | Key Skill |
|---|---|---|---|
| 1 | 800–900 | 20 | CF format comfortable |
| 2 | 900–1000 | 45 | Implementation solid |
| 3 | 1000–1100 | 65 | Math basics done |
| 4 | 1100–1200 | 85 | Greedy intuition |
| 5 | 1150–1250 | 105 | Binary search mastered |
| 6 | 1200–1300 | 120 | Graphs basics |
| 7 | 1250–1350 | 135 | DP started |
| 8 | 1300–1400 | 150 | **Specialist!** |
| 11 | 1500–1600 | 200 | **Expert!** |

### Self-Assessment Checklist (after Week 8)

- [ ] Solve CF Div2 A in under 5 minutes
- [ ] Solve CF Div2 B in under 15 minutes
- [ ] Attempt CF Div2 C with a reasonable approach
- [ ] Write a fast I/O template from memory
- [ ] Implement DFS/BFS without looking it up
- [ ] Recognize greedy vs. DP problems
- [ ] Debug using stress testing
- [ ] Read problems carefully (no silly WAs)

---

## ⚠️ Common Pitfalls to Avoid

**Weeks 1–2**
- Not reading problems fully (missing constraints)
- Forgetting `long long` for large numbers
- Not handling multiple test cases properly
- Submitting without testing edge cases

**Weeks 3–4**
- Overcomplicating greedy problems
- Not proving the greedy approach works
- Integer overflow in math problems
- Off-by-one errors in loops

**Weeks 5–8**
- Using the wrong binary search variant
- Infinite loops in binary search
- Not initializing graph arrays
- DP state design too complex

---

## Resources by Week

| Week | Primary Resource | Backup Resource |
|---|---|---|
| 1 | CF 800-rated problems | USACO Guide |
| 2 | CF 800–900 problems | AtCoder Beginner |
| 3 | CF Math problems | CSES Math section |
| 4 | CF Greedy + Sorting | CSES Sorting |
| 5 | CSES Searching | CF Binary Search tag |
| 6 | CSES Graph | CF DFS/BFS tag |
| 7 | AtCoder DP Contest | CSES DP section |
| 8 | Virtual contests | Past Div 2 rounds |

---

## Repo Structure (suggested)

```
.
├── week01/
├── week02/
├── week03/
├── ...
├── week08/
├── expert-extension/
│   ├── week09/
│   ├── week10/
│   └── week11/
├── templates/
│   └── fast-io-template.cpp
└── notes/
    └── mistake-log.md
```

---

*Roadmap adapted for personal tracking of an 8-week (+3-week) push from LeetCode-level DSA to Codeforces Specialist/Expert.*