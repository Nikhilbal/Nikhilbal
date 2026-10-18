# Installing your GitHub profile kit

This kit belongs in the **special profile repository** `Nikhilbal/Nikhilbal` — **not** `Nikhilbal/synthshield`.

Your profile repository was missing when this kit was prepared. To activate the GitHub profile README, create a public repository named exactly `Nikhilbal`, with `README.md` in its root.

## Simplest terminal setup (you already installed `gh`)

1. Download `Nikhilbal_GitHub_Profile_Kit.zip` to `~/Downloads`.
2. On your Mac, run:

```bash
mkdir -p ~/Projects/github-profile
cd ~/Projects/github-profile
unzip -o ~/Downloads/Nikhilbal_GitHub_Profile_Kit.zip -d .

git init -b main
git add README.md assets/security-banner.svg
git diff --cached --check
git commit -m "docs: launch professional cybersecurity GitHub profile"

gh repo create Nikhilbal/Nikhilbal --public --source=. --remote=origin --push
```

If GitHub says `Repository already exists`, stop — do not overwrite it; retrieve the existing repository and merge the new README safely.

3. Open **https://github.com/Nikhilbal** and refresh.

**Safety:** This creates a public profile README; review the content and links before publishing. No credentials, tokens, or private documents are in this kit.

## Suggested GitHub profile fields

On https://github.com/settings/profile set:

- **Name:** Bala Nikhil
- **Bio:** `Cybersecurity-focused developer | AI-agent security, IAM & secure backends | Building SYNTHSHIELD | Open to internships`
- **Website:** Your portfolio only if you have verified that its link is live and updated.
- **Social link:** `https://www.linkedin.com/in/bala-nikhil-91225b287/` (verify it points to your current account).
- **Location:** Optional, share at your comfort level; a city/country is enough.
- **Public email:** Optional; do not publish your personal email unless you intend to receive public contact.

## Recommend pinning these six repositories

1. `synthshield` — flagship AI-agent cybersecurity research
2. `Ai-smartcart-billing` — multi-service full-stack project
3. `poolgo-app` — mobile application, links to `poolgo-backend`
4. `customer-360` — data analysis and machine-learning application
5. `Smartspark` — AI application / frontend-backend integration
6. `travel-planner-ai` — multi-agent application experiment

You can edit pinned items on your GitHub profile page under **Customize your pins**. Do not pin blank or duplicate repositories just to fill all six slots.

## Polishing the repositories themselves

- Add concise descriptions and 3–6 relevant topics to each featured repository in its GitHub **About** sidebar.
- Ensure each featured project has a truthful README, a screenshot when appropriate, setup instructions, and status/limitations.
- Review near-empty and duplicate public repositories and choose whether to archive, consolidate, or make them private **only after you confirm** that you no longer need them publicly.
- Do not publish hard-coded credentials, private datasets, or unreviewed generated logs.
- Keep your resume wording consistent with verified project accomplishments. Do not label in-progress prototypes as deployed production services.

## Important

GitHub **profile README** and an individual project README are different. This kit updates the profile only. It does not overwrite SYNTHSHIELD or any other project.
