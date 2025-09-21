# Time_Machine_ctf
A challenge that teaches how to inspect and keep track of a file's history

#TIME_MACHINE_CTF_WRITEUP
- The time machine challenge gives insight on how we can review a file’s history (previous versions of how the file looked like).
- The objective of this task was to recover a hidden flag by exploring git history

---

Environment
The challenge was successfully carried out in the following environment:
- Host Machine: Windows 10 with Oracle VirtualBox
- Guest: Ubuntu 20.04 LTS (CLI-based)
- Access: SSH via PuTTY

---

Steps Taken
- The challenge file was downloaded on picoctf website.
- Added file on Ubuntu CLI, oracle virtual manager as a shared folder
- Moved the folder in a home directory (~/challenges)
- Checked previous file changes with git log.
- Found the hidden picoCTF flag after entering git checkout <commit ID>

---

Lessons Learned
- Version control system (VCS) is a software that helps developers see the history of files, code, and documents.
- At the core of VCS is git; a toolkit that tracks these changes.

---

Flag 
picoCTF{[REDACTED]}

