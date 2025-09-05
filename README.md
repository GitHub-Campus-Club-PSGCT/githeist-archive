# githeist-archive

Overview
This repository contains the forensic evidence archive related to the TechSphere Treasury Heist investigation. It features a collection of old backups, partial data recoveries, and corrupted digital artifacts. The files here represent some of the most challenging pieces of evidence, including partially corrupted backups that hint at the true sequence of events despite deliberate tampering.

Contents
/bkp_old/: Old backup files recovered from the treasury system and employee terminals. Includes a heavily corrupted partial backup containing fragmented logs crucial for timeline reconstruction.
/documents/: Corrupted financial spreadsheets with hidden formulas encoding secret keys related to the heist.
/metadata/: Contains hidden metadata blobs and encoded logs. These require forensic tools for analysis and contain cryptic clues about suspect activities.
/chain_custody_old/: Chain of custody documentation ensuring the integrity and handling of the seized digital evidence.

Important Evidence Highlights
The corrupted_partial_conversation.bak in /bkp_old/ contains fragmented logs with timestamps 12:14 AM to 12:18 AM, including unusual badge signatures, USB mounts, and log deletion events. These fragments provide the core timeline for the heist's digital breach.

The financial_summary.xlsx in /documents/ holds a hidden Base64 decoded formula revealing a secret key: "SUGARBOX_KEY=VALID". This key is central to decrypting further clues.

Tools you can use to encode:
Hex encoding: convert ASCII text to hex representation (reverse of hex to ASCII)
Base64 encoding: encode ASCII to Base64 string

Online converters like:
https://www.base64encode.org/
https://www.rapidtables.com/convert/number/ascii-to-hex.html
