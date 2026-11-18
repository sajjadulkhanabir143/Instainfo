# Instagram Profile Info API (Flask)

A lightweight Flask REST API that fetches public Instagram profile information and recent timeline posts by username.

## Features
- Fetches full name, bio, follower/following counts, total post count, HD profile picture URL, and account privacy status.
- Extracts recent posts with captions, likes, comments, post URLs, thumbnails, and media types (`Image` / `Video`).
- Ready to run on Android via **Termux**.

---

## Termux Installation & Run

### Option 1: One-Line Setup (Recommended)
Run this single command in Termux to install dependencies, clone the repository, and start the server:

```bash
pkg update -y && pkg upgrade -y && pkg install python git -y && git clone [https://github.com/sajjadulkhanabir143/](https://github.com/sajjadulkhanabir143/)<repo-name>.git && cd <repo-name> && pip install flask requests && python app.py
