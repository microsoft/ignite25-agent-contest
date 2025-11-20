# 🚨 Contest Challenge: The TreyLink Crisis

## 📖 Setting

Your fast-growing startup, **Trey Research** (treyresearch.net), is about to go live with its first flagship product — **TreyLink**, a voice-enabled AI assistant for smart devices.

⏰ **Five minutes before the livestream launch**, internal systems crash:
- 🎤 Voice commands fail
- 📊 Dashboards freeze  
- 🔐 Team credentials are suddenly invalid

---

## 🎯 Your Task

Build an AI agent that uses one or more clues from different sources (image, email) to:
- 🔍 Detect what went wrong
- 🛠️ Determine how to fix it before launch

---


## 🧩 The Situation

The engineering team suspects that an **unauthorized model update** might have replaced a production module — but no one's sure which one or how it happened.

### Your AI agent must:

1. ✅ **Analyze** incoming clues
2. 🔎 **Diagnose** the problem
3. 💡 **Recommend** the quickest fix

---

## 🔑 Clues


### 🖼️ ASSET 1: Image Evidence

![Image Asset](./assets/asset-image.png)

---


### 📧 ASSET 2: Email — Engineering Escalation

**Subject:** URGENT: Launch blocked — speech model rejecting tokens  
**From:** Madison Kim, Engineer - LaunchOps Team  
**To:** Alex Lee, Engineering Lead  
**Time:** 9:25 AM

> Hi Alex,
>
> We've traced the issue. The speech-to-command model currently running was pushed from our **test server** (`test-deploy.adatum.com`), not the production registry.
>
> This version doesn't recognize live API tokens, which is why all devices are refusing commands.
>
> **The fix:** Disable the test update channel and revert to **v2.8.3**, our last verified production model.
>
> — Madison

📎 [Download Email PDF](./assets/asset-email.pdf)

---


**Deadline:** November 20, 2025 at 12:00pm (noon) PST

---



