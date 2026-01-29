# GitHub Profile TODO


**High Priority:**

- [x] Add a [github-profile-3d-contrib](https://github.com/yoshi389111/github-profile-3d-contrib) to my README.md. (Found through [j178 Github Profile](https://github.com/j178))
- [x] Add a brief "About Me" introduction to README.md 
- [x] Add contact/social links (LinkedIn, Email)
- [ ] Make a github IO & add it 

**Medium Priority:**

- [ ] Add shields.io badges for technologies
  - [x] Python, Git, Linux, Semantic Web 
  - [ ] For the future when i master them : C++, Docker, 
- [ ] Pin the best repositories on my profile page 

**Low Priority:**

- [ ] Deploy my own instance of [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) on Vercel for private use

## Self-Hosted GitHub Stats Setup (Vercel)

1. **Fork the repo**: https://github.com/anuraghazra/github-readme-stats

2. **Deploy to Vercel**:
   - Sign in to [vercel.com](https://vercel.com) with GitHub
   - New Project &xrarr; Import forked repo
   - **Framework Preset**: Other
   - **Build Command**: Leave blank
   - Deploy

3. **Create GitHub Token**:
   - Go to: https://github.com/settings/tokens
   - Generate new token (classic)
   - Scopes: full `repo` + only `read:user`
   - Expiration: 1 year or No expiration
   - Copy token

4. **Add Token to Vercel**:
   - Project &xrarr; Settings &xrarr; Environment Variables
   - Name: `PAT_1`
   - Value: Paste GitHub token
   - Check all environments (Production, Preview, Development)
   - Save &xrarr; Redeploy

5. **Use in README**:

**Live instance**: https://github-readme-stats-rapture244.vercel.app