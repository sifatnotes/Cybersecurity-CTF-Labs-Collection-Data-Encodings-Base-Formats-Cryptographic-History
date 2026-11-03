# Cybersecurity-CTF-Labs-Collection-Data-Encodings-Base-Formats-Cryptographic-History
A curated, searchable index of hands-on CTF labs covering multi-encoded strings, Unicode/URL parsing, Octal/Binary/Hex triage, Base32/Base58/Base85 formats, phantom ledger analysis, archive relay memos, and rotor relay ciphers from Learn SecByte.
# Data Encodings, Base Formats & Cryptographic History CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Low-Level Numerical & String Encodings (Multi-Encoded Madness, Unicode Mystery, URL-Encoded Escape, Octal Obsession, Binary Secrets, Hex Detective), Specialized Base Encodings (Layers of Base85, Base58 Treasure Map, The Base32 Vault), and Cryptographic History & Ledger Forensics (Phantom Ledger, Archive Relay Memo, Rotor Relay Revisited) hosted on Learn SecByte.

This collection is designed for security analysts, incident responders, cryptanalysts, reverse engineers, and web application security specialists seeking practical experience in decoding non-standard string formats, reversing numerical conversions, and analyzing historical cipher mechanisms.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Low-Level Numerical & String Encodings](#low-level-numerical--string-encodings)
  - [Specialized Base Encodings](#specialized-base-encodings)
  - [Cryptographic History & Ledger Forensics](#cryptographic-history--ledger-forensics)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Modern security telemetry, web applications, and adversary payloads rely heavily on data transformations. Threat actors obfuscate scripts using nested URL/Unicode escapes, octal byte sequences, and raw binary/hex encodings to evade signature-based detection. Furthermore, modern blockchain protocols and binary storage containers utilize specialized formats such as Base32, Base58, and Base85 for efficient data packing. Understanding these encodings, alongside historical mechanical rotor ciphers and transactional ledger forensics, is vital for forensic analysis and threat hunting.

This repository organizes hands-on data encoding, numerical conversion, and historical cipher labs from Learn SecByte into structured learning paths covering artifact analysis and stream decoding.

---

## Lab Collection & Index

| Lab Title | Data Domain | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **Multi-Encoded Madness** | Data Formats | Chained & Nested Encoding Transformations | [Access Lab](https://learn.secbyte.org/ctf/multi-encoded-madness) |
| **Unicode Mystery** | Web / Strings | Unicode Normalization & Homograph Parsing | [Access Lab](https://learn.secbyte.org/ctf/unicode-mystery) |
| **URL-Encoded Escape** | Web Security | Percent-Encoding & Evasion Decoding | [Access Lab](https://learn.secbyte.org/ctf/url-encoded-escape) |
| **Octal Obsession** | Base Conversion | Octal Byte Representation & Shell Code | [Access Lab](https://learn.secbyte.org/ctf/octal-obsession) |
| **Binary Secrets** | Base Conversion | Raw Bitstream Analysis & Endianness | [Access Lab](https://learn.secbyte.org/ctf/binary-secrets) |
| **Hex Detective** | Base Conversion | Hexadecimal Stream Parsing & Magic Bytes | [Access Lab](https://learn.secbyte.org/ctf/hex-detective) |
| **Layers of Base85** | Specialized Base | Base85 / ASCII85 Stream Unpacking | [Access Lab](https://learn.secbyte.org/ctf/layers-of-base85) |
| **Base58 Treasure Map** | Specialized Base | Bitcoin/IPFS Base58 Encoding Triage | [Access Lab](https://learn.secbyte.org/ctf/base58-treasure-map) |
| **The Base32 Vault** | Specialized Base | Base32 Padding & Case-Insensitive Streams | [Access Lab](https://learn.secbyte.org/ctf/the-base32-vault) |
| **Phantom Ledger** | DFIR / Ledger | Hidden Transaction Logs & Ledger Forensics | [Access Lab](https://learn.secbyte.org/ctf/phantom-ledger) |
| **Archive Relay Memo** | DFIR / Communications | Historical Memo Archives & Transmission Triage | [Access Lab](https://learn.secbyte.org/ctf/archive-relay-memo) |
| **Rotor Relay Revisited** | Cryptanalysis | Mechanical Rotor Machine & Enigma Mechanics | [Access Lab](https://learn.secbyte.org/ctf/rotor-relay-revisited) |

---

## Categories

### Low-Level Numerical & String Encodings
Hands-on CTF labs detailing string escapes, character sets, base conversion (Binary, Octal, Hex), and web encoding schemes:

* **Multi-Encoded Madness:** Identifying and stripping complex, multi-pass encodings across web and shell payloads.
  * Lab Link: https://learn.secbyte.org/ctf/multi-encoded-madness
* **Unicode Mystery & URL-Encoded Escape:** Resolving UTF-8/UTF-16 escape sequences, handling percent-encoding obfuscation in HTTP traffic, and detecting homograph attacks.
  * Lab Links:
    * Unicode Mystery: https://learn.secbyte.org/ctf/unicode-mystery
    * URL-Encoded Escape: https://learn.secbyte.org/ctf/url-encoded-escape
* **Octal Obsession, Binary Secrets & Hex Detective:** Translating raw octal byte streams, parsing binary bitwise operations, inspecting file magic numbers (`4D 5A`, `89 50 4E 47`), and converting raw hex dumps.
  * Lab Links:
    * Octal Obsession: https://learn.secbyte.org/ctf/octal-obsession
    * Binary Secrets: https://learn.secbyte.org/ctf/binary-secrets
    * Hex Detective: https://learn.secbyte.org/ctf/hex-detective

### Specialized Base Encodings
Practical security labs focused on non-standard positional numeral systems used in modern web APIs, container formats, and cryptocurrency protocols:

* **The Base32 Vault:** Parsing 5-bit character groupings, handling `=` padding rules, and decoding Base32 TOTP secret streams.
  * Lab Link: https://learn.secbyte.org/ctf/the-base32-vault
* **Base58 Treasure Map:** Analyzing Bitcoin-style Base58 alphabets (excluding `0OIl`), validating checksums, and decoding wallet address representations.
  * Lab Link: https://learn.secbyte.org/ctf/base58-treasure-map
* **Layers of Base85:** Unwrapping Adobe/ZeroMQ Base85 (ASCII85) encodings, handling `<~ ~>` delimiters, and unpacking compressed binary payloads.
  * Lab Link: https://learn.secbyte.org/ctf/layers-of-base85

### Cryptographic History & Ledger Forensics
Security forensics labs covering historical mechanical encryption hardware, archival message recovery, and ledger analysis:

* **Rotor Relay Revisited:** Cryptanalyzing multi-rotor electromechanical cipher machines, configuring rotor stepping orders, reflector settings (Umkehrwalze), and plugboard (Steckerbrett) configurations.
  * Lab Link: https://learn.secbyte.org/ctf/rotor-relay-revisited
* **Phantom Ledger & Archive Relay Memo:** Investigating obscure financial ledger records, uncovering deleted transaction entries, and triaging historic transmission memos.
  * Lab Links:
    * Phantom Ledger: https://learn.secbyte.org/ctf/phantom-ledger
    * Archive Relay Memo: https://learn.secbyte.org/ctf/archive-relay-memo

---

## Learning Path

Follow this structured roadmap to master data encodings, positional base systems, and historical ciphers:

1. **Numerical Representations & Web Encodings**
   - Convert binary, octal, and hex streams in Binary Secrets, Octal Obsession, and Hex Detective.
   - Resolve web-layer escape formats using URL-Encoded Escape and Unicode Mystery.
2. **Specialized Base System Decoding**
   - Master Base32 structures in The Base32 Vault.
   - Parse cryptocurrency formats in Base58 Treasure Map and unwrap high-density streams in Layers of Base85.
3. **Multi-Pass & Obfuscation Decoding**
   - Solve nested encoding sequences in Multi-Encoded Madness.
4. **Historical Ciphers & Ledger Analysis**
   - Reconstruct historical communications in Archive Relay Memo and solve mechanical rotor ciphers in Rotor Relay Revisited.
   - Investigate transactional artifacts in Phantom Ledger.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using data transformation tools (CyberChef, Python scripts, `xxd`, `base58`, `hexdump`, `iconv`, and Enigma simulator tools).
4. Review post-lab solution guides, encoding standards, and analytical frameworks to strengthen your forensic readiness.

---

## Disclaimer

This repository is strictly intended for educational research, authorized digital investigations, and defensive security training. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise networks. Unsanctioned data scraping, unauthorized payload obfuscation, or malicious activities against external systems are strictly illegal.
