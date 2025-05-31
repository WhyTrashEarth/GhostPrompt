# GhostPrompt 👻

**A Cognitive Security Protocol for Behavioral Authentication & Decoy Detection**

---

## Overview

**GhostPrompt👻** is a security concept and open-source protocol that introduces *multi-prompt deception* as a defense layer. It targets a critical blind spot in modern authentication:

> Even if an attacker has the correct credentials...  
> **they can still fail.**

How? By turning the *login interface itself* into part of the authentication process.

---

## Key Principles

- **UI as a Security Layer:**  
  Users must know *which* of multiple login prompts is real. All others are decoys.

- **Wrong Prompt = Silent Tripwire:**  
  If an attacker uses correct credentials on the wrong prompt, you get alerted — **without them knowing.**

- **Cognitive Obfuscation:**  
  Most attackers (and bots) default to the first visible form. GhostPrompt👻 exploits this behavior to detect breaches.

- **No Extra Passwords Required:**  
  The login UI becomes part of the security — *no need to modify backend auth logic*.

---

## Real-World Use Cases

- **Sysadmin panels & developer tools**
- **Internal dashboards & CMS backends**
- **High-value WordPress admin areas**
- **Decoy honeypots for leaked credentials**
- **Bot defense & behavioral intrusion detection**

---

## How It Works

- Display 3–90+ login prompts on a single page.
- Only 1 prompt is *real*.
- All others are fake:
  - Trigger silent logging
  - Serve false environments
  - Redirect to dummy panels
- The correct prompt can change daily, randomly, or via TOTP logic.

---

## Example Scenario

An attacker gains authentic credentials

They reach the login screen.

There are **5 login prompts.**  
They guess the first one and enter the credentials.  
It fails.  
But they don't know why.

**Meanwhile:**  
- You receive an instant alert.  
- Real login access is locked.  
- They're chasing ghosts. 👻

---

## Why GhostPrompt?

Most security systems fail **after** credentials are breached.  
GhostPrompt aims to detect threats **at the moment of misuse**, even when the password is correct.

It’s not about blocking access —  
**it’s about breaking certainty.**

---

## License

Apache 2.0 License  
Protects open-source usage and prevents patent abuse.

---

## Status

**Currently in development.**  
Mockups, demos, and implementation guides coming soon.

Want to contribute? Fork this repo and start building haunted login pages with us.

---

**Made with mischief by Alec (WhyTrashEarth)**  
*“Just because the door opens… doesn’t mean you’re welcome.”*


