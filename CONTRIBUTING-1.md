# CONTRIBUTING — CLAUDE STUDIO

> The bar is high. The vision is clear. Here's how to add to it.

---

## WHAT WE ACCEPT

- A tool that genuinely makes Claude more capable
- Must be open source (MIT or Apache preferred)
- Must be actively maintained (last commit within 6 months)
- Must not duplicate an existing module's function

## WHAT WE DON'T ACCEPT

- Wrappers around wrappers
- Abandoned repos with no maintenance
- Tools that only work in one specific IDE
- Anything that requires a paid API with no free tier

---

## HOW TO PROPOSE A NEW MODULE

1. Open an **Issue** using the Module Proposal template
2. Fill in: repo link, star count, what problem it solves, which existing module it replaces or extends
3. Wait for discussion — if it fits, submit a PR

---

## HOW TO SUBMIT A PR

```bash
# Fork the repo
git fork https://github.com/er4700345-coder/claude-studio

# Create a branch
git checkout -b feat/module-name

# Make your changes
# Update README.md, .gitmodules, and SETUP.md

# Commit
git commit -m "feat: add [module-name]"

# Push and open PR
git push origin feat/module-name
```

---

## PR CHECKLIST

- [ ] README updated with module card
- [ ] `.gitmodules` updated with submodule entry
- [ ] `SETUP.md` updated with install steps
- [ ] Architecture diagram updated if needed
- [ ] Use case table updated

---

## CODE OF CONDUCT

Be direct. Be useful. No fluff.

---

*Built by [er4700345-coder](https://github.com/er4700345-coder)*
