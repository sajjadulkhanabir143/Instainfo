# Instagram Profile Info API (Flask)

A lightweight Flask REST API that fetches public Instagram profile information and recent timeline posts by username.

## Features
- Fetches full name, bio, follower/following counts, total post count, HD profile picture URL, and account privacy status.
- Extracts recent posts with captions, likes, comments, post URLs, thumbnails, and media types (`Image` / `Video`).
- Ready to run on Android via **Termux**.

---

## Termux Installation & Run

Run the following all-in-one command in Termux to update packages, install Python & dependencies, and create the project directory:

```bash
pkg update -y && pkg upgrade -y && pkg install python git -y && pip install flask requests && mkdir -p ig-profile-api && cd ig-profile-api
