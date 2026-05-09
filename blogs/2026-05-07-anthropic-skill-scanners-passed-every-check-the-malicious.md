---
title: "Anthropic Skill scanners passed every check. The malicious code rode in on a test file."
url: "https://venturebeat.com/security/anthropic-skill-scanners-passed-every-check-malicious-code-test-file"
date: "2026-05-07"
author: "louiswcolumbus@gmail.com (Louis Columbus)"
feed_url: "https://venturebeat.com/category/security/feed/"
---
Picture this scenario: An Anthropic Skill scanner runs a full analysis of a Skill pulled from ClawHub or skills.sh. Its markdown instructions are clean, and no prompt injection is detected. No shell commands are hiding in the SKILL.md. Green across the board.The scanner never looked at the .test.ts file sitting one directory over. It didn’t need to. Test files aren’t part of the agent execution surface, so no publicly documented scanner inspects them (as of publication of this post). The file runs anyway.
