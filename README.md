# OverTheWire Bandit: CTF walkthrough
 
A documented walkthrough of all levels (0 → 33) of the [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) wargame, which I completed to practise Linux command-line and security fundamentals.
 
**Report:** [`OverTheWire_Bandit_Walkthrough.docx`](./OverTheWire_Bandit_Walkthrough.docx). GitHub can't preview Word files, so use **Download raw file** to open it.
 
## What's in the report
 
For every level:
 
- **Goal:** the level's objective.
- **Commands used:** the exact commands I ran.
- **Result:** the password or key found.
- **Explanation:** why the approach works.
- **Screenshot:** my terminal output.
The report ends with the main lessons I took from the game.
 
## Skills practised
 
| Area | Examples |
|---|---|
| Linux basics | SSH, navigating the file system, hidden files, special filenames |
| Finding and filtering data | `find`, `grep`, `sort`, `uniq`, `strings`, `diff` |
| Encoding and archives | base64, ROT13 with `tr`, hexdumps with `xxd`, gzip, bzip2, tar |
| Networking | `nc`, `ncat --ssl`, port scanning with `nmap`, SSH keys |
| Privileges and automation | setuid binaries, cron jobs, Bash scripting, brute-forcing a PIN |
| Git | history, branches, tags, pushing to a remote |
| Restricted shells | escaping through `more` and vim, and the `$0` trick |
 
## Spoiler warning
 
The report shows every password and solution. If you plan to play Bandit yourself, try the levels first. OverTheWire also changes the passwords from time to time, so the ones shown may no longer work.
 
## Author
 
Rina Enea
