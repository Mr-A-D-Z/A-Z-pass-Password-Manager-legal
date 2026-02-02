# Account Deletion — A-Z Password Manager 🗑️
Last updated: 2026-02-03

A-Z Password Manager supports **in-app account deletion**.

## How to delete your account
1) Open the app  
2) Go to: **Settings → ABOUT → Delete Account**  
3) Enter your **Master Password**  
4) Type **HESABI SİL** to confirm  
5) Confirm deletion

## What we delete
- Firebase Authentication user (your email login)
- Firestore documents associated with your user ID (encrypted vault sync data and support messages)

## After deletion
- You will not be able to access your cloud-synced vault
- This action cannot be undone
