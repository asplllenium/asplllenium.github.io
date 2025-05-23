---
layout: post
title: Work Retro
---

At work, I committed something that broke things twice. Luckily, this was not truly serious, did not block anyone, and not too many people noticed. However, it irritates my commit history a bit, and as a foreshadowing, I notice that people who make these types of mistakes tend to leave in a few months past the incidents. I did not dev test thoroughly enough the first time and the second time. I thought I fixed the first problem by conducting a smoke test, but that didn't work, and that caused the second breakage.

Some lessons I think I should learn are:
- I'll have bad days once in a while
- To not enable auto-merge for code reviews ever
- When someone offers a suggestion that completely changes the nature of the code review, think about the implications to testing
- Dev test thoroughly, even if the setup steps are annoying. If they are annoying and don't work, fix them until they do work
- Do not be afraid of being slow. Better to be slow than to break things
- Update commit section every time with clear instructions of the dev test
- Don't rely on tricks to get around testing. Use tricks to reinforce the fact that the real dev test worked
- Drink tea every day to calm my anxiety
