# Pi Network Wallet Recovery Suite (Free Edition)
A specialized cryptographic toolkit for recovering and validating Pi Network wallet passphrases. This suite focuses on offline-first recovery methods, utilizing the BIP39 standard for the Pi Network.

> [!WARNING]
> **Educational Purpose Only:** This tool is designed for authorized wallet recovery and research. Using this software for unauthorized access or any illegal activities is strictly prohibited.

## 🚀 Free Features

*   **Mnemonic Variant Recovery**: Corrects misspelled or mistyped words at specific positions using BIP39 wordlist matching.
*   **Permutation Recovery (Multi-word Swap)**: Brute-forces word order combinations for phrases where all words are present but in the incorrect sequence.
*   **Missing Word Recovery**: High-performance brute-force algorithm for 1-2 missing words with customizable position scanning.
*   **Typo-Proof Assistant**: Real-time validation and suggestion engine for 24-word passphrases with accuracy scoring and address derivation.
*   **Joined Word Repair (Missing Spaces)**: Algorithmic splitting of phrases where spaces were omitted (e.g., `applebanana` -> `apple banana`).
*   **Pattern-Based Search**: Mask-based word searching using wildcards (e.g., `s***m`) to identify valid words within the BIP39 list.
*   **Local Result Management**: Integrated explorer for reviewing recovered keys and generated QR codes.


## Prerequisites

- Python 3.8 or higher
- The following libraries are required (see `requirements.txt`):
  - `stellar-sdk`, `mnemonic`, `qrcode`, `Pillow`, `tqdm`

## Installation

1. Install dependencies: `pip install -r requirements.txt`
2. Run the tool: `python pi_recovery.py`

## Security Architecture
*   **Zero-Network Core**: All recovery algorithms and key derivations run 100% locally.
*   **Persistence**: Sessions are saved to `RESULTS_STORAGE/` to prevent data loss.
*   **Data Isolation**: Private keys and mnemonics are never logged to system caches.

*   
## 💎 Get Pro Version

The **Pro Version** for advanced automation, Transaction History Scan, Multi-Threaded API Engine, bulk scanning, and deep blockchain analytics.

**Exclusive Pro Features:**
- **Multi-Target Batch Scanner**: Bulk scan lists of addresses or mnemonics simultaneously.
- **Auto-Extraction Scanner**: Automatically extracts and scans all wallets saved in your `RESULTS_STORAGE` folder.
- **Transaction History Deep Scan**: Displays the last 10 transaction logs (IN/OUT, Peer Address, and Dates).
- **Multi-Threaded API Engine**: Uses high-speed threading to check balances 20x faster.
- **Standalone QR Code Generator**: A manual tool to convert any text/key into a QR code on demand.
- **Granular Session Resumption**: Ability to stop and resume massive brute-force searches at a specific percentage/index.
- **Automated  Reports**: Generates a summary of total Pi found across all scanned wallets.
- **Watch-Only Portfolio Tracker**: Real-time balance monitoring for saved addresses.
- **On-Chain Balance Scanner**: Instant blockchain verification.
- **System Speed Test & Benchmark**: Cryptographic performance rating 

**For Pro version access:**
📧 **Contact:** `uworkonline1@gmail.com`

---

