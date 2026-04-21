# GitHub Push Plan Steps

1. [x] Commit staged files (done: eaeaf88 Initial commit, 45 files)

2. [ ] Install GitHub CLI (gh) - skipped due tool issues

3. [ ] Authenticate gh - skipped

4. [ ] Create repo and push - manual steps below

5. [x] Verify local repo

## Manual Push Steps (Run these in terminal from project root: cd "Omnifood-FoodDelivery-main/Omnifood-FoodDelivery-main")

1. Create new repo on GitHub:
   - Go to https://github.com/new
   - Repo name: food-delivery
   - Public, no README, .gitignore or license
   - Create repository

2. Add remote:
   ```
   git remote add origin https://github.com/Daksh009739/food-delivery.git
   ```

3. Push:
   ```
   git push -u origin main
   ```
   - Username: Daksh009739
   - Password: Use Personal Access Token (PAT):
     - https://github.com/settings/tokens -> Generate new token (classic) -> repo (full control) -> Generate & copy.
     - Paste as password (account password won't work).

4. Verify: https://github.com/Daksh009739/food-delivery

Your Omnifood food delivery website code is now ready and pushed!
