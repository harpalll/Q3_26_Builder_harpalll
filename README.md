# Q3'26 Builder — Harpalsinh Sindhav

Welcome to my central index and submission repository for the **Turbin3 Q3'26 Builder** cohort. 

This repository acts as the central hub tracking my progress and weekly submissions throughout the program. Each week's assignment is developed and maintained in its own dedicated GitHub repository and linked here as a **Git submodule** to keep individual codebases clean, modular, and self-contained.

---

## 📚 Assignments

| Week | Assignment | Repository | Description | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01** | Solana SPL Token & Metaplex Core NFT Suite | [`spl-nft-q326`](https://github.com/harpalll/spl-nft-q326) | End-to-end SPL Token and Metaplex Core NFT implementation on Solana Devnet. | ✅ `Completed` |
| **02** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **03** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **04** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **05** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **06** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **07** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |
| **08** | *Upcoming Assignment* | *TBD* | *To be announced* | ⏳ `Pending` |

---

## 🗂️ Repository Structure

```text
Q3_26_Builder_harpalll/
├── spl-nft-q326/          # Week 1 assignment (Git submodule)
├── .gitmodules            # Submodule configurations & remote mappings
└── README.md              # Central hub & submission index
```

> **Note:** Each assignment folder is an independent Git repository with its own history, dependencies, scripts, and documentation. This index repository tracks the exact commit hash of each submodule corresponding to the submitted milestone.

---

## 🔗 Submodules

### Cloning with Submodules
To clone this repository along with all linked assignment submodules in a single command:

```bash
git clone --recurse-submodules https://github.com/harpalll/Q3_26_Builder_harpalll.git
```

### Initializing Submodules in an Existing Clone
If you have already cloned the repository without submodules, initialize and fetch them with:

```bash
git submodule update --init --recursive
```

### Tracking & Updating Submodules
To pull the latest commits for all submodule repositories:

```bash
git submodule update --remote --merge
```
Whenever an assignment is updated, a commit in this repository captures and updates the submodule pointer to the latest verified commit.

---

## 🚀 Progress

- [x] **Week 1** — SPL Token & Metaplex Core NFT
- [ ] **Week 2**
- [ ] **Week 3**
- [ ] **Week 4**
- [ ] **Week 5**
- [ ] **Week 6**
- [ ] **Week 7**
- [ ] **Week 8**

---

## 🎯 Goal

The objective of this journey is to master practical, production-ready Solana and Web3 engineering skills throughout the **Turbin3 Q3'26 Builder** program. Each week represents a focused milestone—from core token and NFT standards to advanced program architecture, testing, and deployment.

---

## 📌 Notes

- **Central Index**: This repository serves purely as an index and milestone submission tracker.
- **Independent Repositories**: Source code, test scripts, and execution proofs reside directly in the respective submodule repositories.
- **Decoupled Workflow**: Each submodule can be cloned, developed, tested, and pushed independently without polluting the main index workspace.
- **Commit Pinning**: The main repository explicitly records which commit of each assignment repository represents the official submission.

---

## 🧑‍💻 About Me

**Harpalsinh Sindhav**
- **GitHub**: [@harpalll](https://github.com/harpalll)
- **X (Twitter)**: [@harpalll_dev](https://x.com/harpalll_dev)
