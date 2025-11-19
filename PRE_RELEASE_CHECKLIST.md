# RagNarok's Lobby - Pre-Release Checklist

## ✅ BEFORE YOU POST TO GITHUB

### Code & Documentation
- [ ] **Verify main.js has no console.log() statements** (or keep them minimal for debugging)
  - Current: Check for debug-level logs that should be removed
  
- [ ] **Test on Foundry VTT locally**
  - [ ] Enable module in a test world
  - [ ] Test lobby activation/deactivation
  - [ ] Test GM preview mode
  - [ ] Test countdown timer
  - [ ] Test custom message/image settings
  - [ ] Test with multiple browsers/sessions
  - [ ] Verify no console errors
  
- [ ] **Check all links work**
  - [ ] GitHub URLs in documentation
  - [ ] Patreon link: https://patreon.com/RagNaroks?utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink
  - [ ] Buy Me a Coffee: https://buymeacoffee.com/ragnarokscodex
  - [ ] Discord server link (add if needed)

- [ ] **Verify module.json is correct**
  - [ ] Version is 1.0.0
  - [ ] Correct author name (RagNarok)
  - [ ] Manifest URL points to correct release location
  - [ ] Download URL is valid
  - [ ] License field set to "MIT"
  - [ ] Keywords are relevant

### File Structure
- [ ] **Confirm NO extra/debug files in project**
  - [ ] No node_modules folder
  - [ ] No .DS_Store files (Mac)
  - [ ] No Thumbs.db (Windows)
  - [ ] No local development config files
  - [ ] No API keys or secrets

- [ ] **Verify all necessary files present**
  - [x] README.md
  - [x] system-summary.md
  - [x] LICENSE
  - [x] module.json
  - [x] scripts/main.js
  - [x] styles/lobby.css
  - [x] lang/en.json
  - [x] assets/ragnaroks-codex.jpg
  - [x] templates/ folder with all .hbs files

### README Quality
- [ ] Grammar check (spell check)
- [ ] All code examples work
- [ ] Links are accessible
- [ ] Features accurately described
- [ ] Installation instructions clear
- [ ] Support links prominent

---

## 📦 GITHUB SETUP

### Before First Push
- [ ] Create GitHub account if you don't have one
- [ ] Create repository: `ragnaroks-lobby`
- [ ] Initialize with MIT License (select during repo creation or add LICENSE file)
- [ ] Add .gitignore file for Node projects (if any dev files exist)

### Repository Settings
- [ ] **Add Repository Description**: "System-agnostic maintenance mode module for Foundry VTT"
- [ ] **Add Topics/Tags**:
  - foundryvtt
  - foundry-module
  - maintenance
  - gm-tools
  - vtt
  - tabletop-rpg

- [ ] **Enable Issues** (for bug reports)
  - [ ] Add issue templates
  
- [ ] **Enable Discussions** (for feature requests)

- [ ] **Setup README on main page** (GitHub will auto-display README.md)

### First Commit & Push
```bash
git init
git add .
git commit -m "Initial release: RagNarok's Lobby v1.0.0"
git branch -M main
git remote add origin https://github.com/yourusername/ragnaroks-lobby.git
git push -u origin main
```

---

## 🏷️ CREATE GITHUB RELEASE

### Release Process
1. Go to your GitHub repo → Releases → "Create a new release"

2. **Tag version**: `v1.0.0`

3. **Release title**: "RagNarok's Lobby v1.0.0 - Official Release"

4. **Release description** (use this template):

```markdown
# 🎭 RagNarok's Lobby v1.0.0

A system-agnostic maintenance mode module for Foundry VTT that provides GMs with beautiful, customizable full-screen overlays to manage player access during maintenance and session prep.

## What's New in v1.0.0

### Core Features
✨ Full-screen maintenance overlay with smooth animations
🔒 Complete player access prevention
⏱️ Countdown timers for automatic re-entry
🎨 Fully customizable appearance system
💾 Save and load appearance presets
📊 Real-time chat monitoring
🗳️ Player poll system
📈 Analytics tracking
🎛️ One-click sidebar toggle
🔄 Real-time synchronization

### Features
- GM Preview Mode - test the overlay as a GM
- Sound Notifications - optional audio feedback
- Custom Messages and Images
- Complete Settings Configuration
- 100% System-Agnostic - works with any game system

## Installation

1. Download the ZIP file below
2. Extract to your Foundry `Data/modules` folder
3. Enable in your world's Module Settings
4. Use the sidebar button to toggle!

## Documentation

- **README**: Full user guide and features
- **System Summary**: Technical architecture documentation
- **Issues**: Report bugs on GitHub

## Support

- 🆓 Free and Open Source (MIT License)
- ☕ [Buy Me a Coffee](https://buymeacoffee.com/ragnarokscodex)
- 💜 [Patreon](https://patreon.com/RagNaroks)
- 🎮 Join RagNarok's Codex Discord

## Credits

Special thanks to:
- My amazing players for inspiring this module
- Lisa (my fiancée) for support and encouragement throughout development

---

**Compatibility:**
- Foundry VTT: 12.0+
- All Game Systems
- Modern Browsers (Chrome, Firefox, Safari, Edge)

**License:** MIT License - See LICENSE file for details
```

5. **Upload ZIP file** (create this):
   - Zip entire ragnaroks-lobby folder
   - Name it: `ragnaroks-lobby-1.0.0.zip`
   - Upload as release asset

6. Click "Publish release"

---

## 📝 OPTIONAL BUT RECOMMENDED

### Create Additional Documentation (in repo)
- [ ] **CHANGELOG.md** - Document version history
  ```markdown
  # Changelog

  All notable changes to this project will be documented in this file.

  ## [1.0.0] - 2025-11-09

  ### Added
  - Initial release of RagNarok's Lobby
  - Full-screen maintenance overlay system
  - Appearance customization with presets
  - Countdown timer functionality
  - Chat monitoring
  - Poll system
  - Analytics panel
  - GM preview mode
  - Sound notifications

  ### Features
  - System-agnostic design
  - Real-time synchronization
  - Responsive design
  - Complete customization options
  ```

- [ ] **CONTRIBUTING.md** - Guidelines for contributors
  ```markdown
  # Contributing to RagNarok's Lobby

  Thank you for your interest in contributing!

  ## How to Contribute

  1. Fork the repository
  2. Create a feature branch
  3. Make your changes
  4. Test thoroughly
  5. Submit a pull request

  ## Bug Reports

  Use GitHub Issues to report bugs. Include:
  - Foundry version
  - Browser and OS
  - Steps to reproduce
  - Console errors
  ```

- [ ] **CODE_OF_CONDUCT.md** - Community guidelines (optional but good practice)

---

## 🚀 SOCIAL MEDIA & ANNOUNCEMENTS

### Posts to Make (after GitHub release)
- [ ] **Reddit post** to r/FoundryVTT (use provided template)
- [ ] **Reddit post** to r/VTT (use provided template)
- [ ] **Facebook post** to Foundry VTT groups
- [ ] **Facebook post** to TTRPG communities
- [ ] **Twitter/X post** (use provided templates)
- [ ] **Discord announcements** in relevant communities

### Communities to Notify
- [ ] Foundry Discord server
- [ ] TTRPG Discord communities
- [ ] Reddit subreddits (r/FoundryVTT, r/VTT, r/TTRPG)
- [ ] Foundry forums (if applicable)
- [ ] Your personal networks

---

## 🔗 FOUNDRY PACKAGE REGISTRY (Future)

### Add to Foundry Package Registry
1. Ensure module.json is complete and correct
2. Go to https://foundryvtt.com/packages/
3. Submit module for inclusion
4. Wait for approval (usually 24-48 hours)

**Requirements:**
- Valid module.json ✓
- GitHub repository ✓
- MIT or compatible license ✓
- Proper documentation ✓
- Working manifest URL ✓

---

## 📊 POST-RELEASE MONITORING

### First Week
- [ ] Monitor GitHub Issues for bug reports
- [ ] Respond to all comments/questions
- [ ] Fix any critical bugs immediately
- [ ] Engage with social media comments
- [ ] Collect user feedback

### Performance Tracking
- [ ] GitHub Stars (track growth)
- [ ] Downloads (check Foundry registry)
- [ ] Community feedback (Discord, Reddit)
- [ ] Bug reports (GitHub Issues)

### Documentation Updates
- [ ] Update based on user questions
- [ ] Add FAQ section if needed
- [ ] Clarify unclear parts
- [ ] Add more examples if requested

---

## ❌ THINGS TO AVOID

- ❌ Don't include node_modules, .git, or build files
- ❌ Don't hardcode URLs (use relative paths)
- ❌ Don't commit API keys or secrets
- ❌ Don't include development config files
- ❌ Don't use console.error() for normal operations
- ❌ Don't make the repo private (keep it open source)
- ❌ Don't forget to update version numbers consistently

---

## ✅ FINAL VERIFICATION CHECKLIST

Before you click "Publish Release":

- [ ] Code tested locally in Foundry VTT
- [ ] No console errors
- [ ] All links verified
- [ ] module.json correct
- [ ] README complete and accurate
- [ ] LICENSE file present
- [ ] No extra/debug files included
- [ ] ZIP file created and named correctly
- [ ] GitHub repository created
- [ ] Release notes written
- [ ] Release ZIP uploaded
- [ ] "Publish Release" button clicked

---

## 📋 QUICK POST-RELEASE ACTION ORDER

1. **Publish to GitHub** (release v1.0.0)
2. **Copy release URL** (you'll need this for posts)
3. **Post to Reddit** (r/FoundryVTT) - Tuesday-Thursday morning
4. **Post to Facebook** - Wednesday-Thursday evening
5. **Post to Discord** - relevant communities
6. **Post to Twitter/X** - same day or day after
7. **Submit to Foundry Registry** - next day
8. **Monitor for feedback** - daily for first week
9. **Address issues** - as they come up

---

## 🎉 YOU'RE READY!

Once you've completed this checklist, your module is production-ready and you can release it with confidence!

---

**Questions to ask yourself:**
- Is the code clean and tested? ✓
- Are the docs comprehensive? ✓
- Is the license clear? ✓
- Are the links all working? ✓
- Have I tested it in Foundry? (Do this!)
- Is the GitHub repo public? ✓
- Are the release notes clear? ✓

If you answer YES to all of these, you're good to go! 🚀
