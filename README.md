# ✅ GitHub Contribution Automator

Automatically generate **daily GitHub contributions** using GitHub Actions — no manual commits needed!

---

## 🚀 What this does
This workflow runs **once every day around 12:00 UTC (GMT +0)** and pushes an empty commit.  
✔ Keeps your contribution graph active  
✔ No need to open GitHub daily  
✔ Fully automated

---

## 📌 How to Use

1. **Create a new repository** using this template  
   🔗 [How to create from template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)

2. **Add your GitHub email** in repository secrets  
   - Go to: `Settings → Secrets and variables → Actions → New repository secret`
   - Create a secret named **`USER_EMAIL`**
   🔗 [How to add secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository)

3. ✅ Done! The workflow will start running automatically.

---

## 🛠 How it Works
- A scheduled GitHub Action triggers once per day
- It creates an empty commit (`--allow-empty`)
- That commit counts as a daily contribution on your profile

---

## 📄 Example Commit Message
