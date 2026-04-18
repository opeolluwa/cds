---
theme: seriph
background: https://images.unsplash.com/photo-1521737711867-e3b97375f902?w=1920&q=80
title: "CVs, Cover Letters & Online Safety — NYSC CDS Talk"
info: A practical NYSC CDS talk covering job hunting (CVs & cover letters) and staying safe online.
class: text-center
drawings:
  persist: false
transition: slide-left
duration: 60min
fonts:
  sans: Poppins
  weights: '400,500,600,700,800'
---

<div class="absolute inset-0 bg-gradient-to-br from-black via-black/70 to-blue-950/60" />

<div class="relative z-10 flex flex-col items-center justify-center h-full">

<div class="text-xs uppercase tracking-widest opacity-50 mb-4">NYSC CDS Talk · 2025</div>

# CVs, Cover Letters<br>& Online Safety

<div class="mt-4 text-lg font-medium text-blue-300 opacity-90">
  Land the job. Don't get scammed doing it.
</div>

<div class="mt-3 text-sm opacity-50">~45–60 mins · Q&A · Raffle Draw</div>

<div @click="$slidev.nav.next" class="mt-10 inline-block px-6 py-2 border border-white/30 rounded-full text-sm cursor-pointer hover:bg-white/10 transition-colors">
  Let's get into it →
</div>

</div>

<!--
Greet the room warmly. You're a peer, not a lecturer.
-->

---
layout: center
class: text-center
transition: fade
---

<div class="text-3xl font-bold">Good afternoon, corps members! 👋</div>

<div class="mt-8 text-lg opacity-70">Quick show of hands before we start —</div>

<v-click>
<div class="mt-6 text-xl font-semibold text-blue-300">
  🙋 Raise your hand if you've sent out a CV in the last 3 months.
</div>
</v-click>

<v-click>
<div class="mt-5 text-xl font-semibold text-yellow-300">
  🙋 Keep it up if you're 100% sure it was your best work.
</div>
</v-click>

<v-click>
<div class="mt-5 text-base opacity-60 italic">
  That's exactly why we're here.
</div>
</v-click>

---
layout: default
transition: slide-up
---

# Today's Agenda

<div class="grid grid-cols-2 gap-4 mt-6">

<div v-click class="flex gap-3 items-start rounded-xl p-4 border border-blue-500/40 bg-blue-900/10">
  <div class="text-3xl leading-none mt-1">📄</div>
  <div>
    <div class="font-bold text-blue-300 text-base">CVs</div>
    <div class="text-xs opacity-60 mt-1">3 types · ATS explained · The Google XYZ formula</div>
  </div>
</div>

<div v-click class="flex gap-3 items-start rounded-xl p-4 border border-green-500/40 bg-green-900/10">
  <div class="text-3xl leading-none mt-1">✉️</div>
  <div>
    <div class="font-bold text-green-300 text-base">Cover Letters</div>
    <div class="text-xs opacity-60 mt-1">Why they matter · 4-para structure · Brag with proof</div>
  </div>
</div>

<div v-click class="flex gap-3 items-start rounded-xl p-4 border border-red-500/40 bg-red-900/10">
  <div class="text-3xl leading-none mt-1">🔐</div>
  <div>
    <div class="font-bold text-red-300 text-base">Online Safety</div>
    <div class="text-xs opacity-60 mt-1">Phishing · RATs · Fake portals · How to stay protected</div>
  </div>
</div>

<div v-click class="flex gap-3 items-start rounded-xl p-4 border border-yellow-500/40 bg-yellow-900/10">
  <div class="text-3xl leading-none mt-1">🎁</div>
  <div>
    <div class="font-bold text-yellow-300 text-base">Raffle Draw</div>
    <div class="text-xs opacity-60 mt-1">Prizes for active participants — stay till the end!</div>
  </div>
</div>

</div>

---
layout: two-cols
transition: slide-up
---

# About Me

<div class="text-sm leading-relaxed mt-4 space-y-4">

<div v-click>

**Software Engineer · ~10 Years in the Industry**

I've been writing code and shipping products for nearly a decade — across startups, scale-ups, and remote teams spanning Nigeria, Europe, and North America.

</div>

<div v-click>

**What that actually looks like:**
- Written code running in production for millions of users
- Collaborated across timezones with engineers, PMs, and designers
- Reviewed hundreds of CVs and sat on both sides of the hiring table

</div>

<div v-click>

**Why I'm here:**

After NYSC, nobody handed me a playbook. I made every mistake I'm about to warn you about — and figured the rest out the hard way.

Today, I'm handing you the shortcut.

</div>

</div>

::right::

<div class="ml-8 mt-4 space-y-3">

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">🌍</div>
  <div class="font-semibold">Global Teams</div>
  <div class="opacity-50 text-xs mt-1">Nigeria · Europe · North America</div>
</div>

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">💻</div>
  <div class="font-semibold">~10 Years in Tech</div>
  <div class="opacity-50 text-xs mt-1">Startups to scale-ups</div>
</div>

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">🎯</div>
  <div class="font-semibold">Hiring Experience</div>
  <div class="opacity-50 text-xs mt-1">Hundreds of CVs reviewed, interviews led</div>
</div>

</div>

---
layout: section
---

<div class="text-blue-300 text-xs font-semibold uppercase tracking-widest mb-3">Part 1</div>

# CVs

*Your first impression — and you won't be in the room when it's made*

---
transition: slide-up
---

# The 3 Types of CV

<div class="grid grid-cols-3 gap-4 mt-5 text-sm">

<div v-click class="rounded-xl p-5 border border-blue-400/40 bg-blue-900/10">
  <div class="text-3xl mb-2">📋</div>
  <div class="font-bold text-blue-300 text-base mb-2">Chronological</div>
  <div class="opacity-60 text-xs mb-3">Experience listed newest → oldest. Shows clear career progression.</div>
  <div class="text-xs rounded p-2 bg-blue-900/30">
    <span class="text-blue-300 font-semibold">Best for:</span> Steady career growth in one field
  </div>
</div>

<div v-click class="rounded-xl p-5 border border-green-400/40 bg-green-900/10">
  <div class="text-3xl mb-2">🛠</div>
  <div class="font-bold text-green-300 text-base mb-2">Functional</div>
  <div class="opacity-60 text-xs mb-3">Leads with skills and achievements — not dates or job titles.</div>
  <div class="text-xs rounded p-2 bg-green-900/30">
    <span class="text-green-300 font-semibold">Best for:</span> Fresh grads, career changers, corps members
  </div>
</div>

<div v-click class="rounded-xl p-5 border border-purple-400/40 bg-purple-900/10">
  <div class="text-3xl mb-2">🔀</div>
  <div class="font-bold text-purple-300 text-base mb-2">Combination</div>
  <div class="opacity-60 text-xs mb-3">Skills section first, then chronological experience below.</div>
  <div class="text-xs rounded p-2 bg-purple-900/30">
    <span class="text-purple-300 font-semibold">Best for:</span> Mid-senior roles with strong skills + experience
  </div>
</div>

</div>

<v-click>
<div class="mt-4 rounded-xl p-3 border border-yellow-500/30 bg-yellow-900/15 text-xs text-yellow-200">
  💡 <strong>NYSC Tip:</strong> Lean Functional or Combination. You have real project and community skills — don't let "limited full-time experience" bury them.
</div>
</v-click>

---
transition: fade
---

# ATS — The Robot Gatekeeper

<div class="text-sm mt-3 opacity-70">Most companies use software to screen CVs <strong>before a human ever sees them.</strong></div>

<v-click>

<div class="grid grid-cols-2 gap-4 mt-5 text-sm">

<div class="rounded-xl p-4 border border-red-400/40 bg-red-900/10">

### How it works
Scans your CV for **keywords from the job description**.

No keyword match → auto-rejected. No human review. Ever.

</div>

<div class="rounded-xl p-4 border border-green-400/40 bg-green-900/10">

### How to beat it
- Mirror the **exact phrases** in the job description
- *"Stakeholder management"* — not *"managing people"*
- No tables, text boxes, or image-heavy layouts — ATS can't read them

</div>

</div>

</v-click>

<v-click>
<div class="mt-4 rounded-xl p-3 border border-red-500/30 bg-red-900/15 text-xs text-red-200">
  ⚠️ A beautifully designed CV that fails ATS is <strong>completely invisible.</strong> Design for the robot first, then the human.
</div>
</v-click>

---

# The XYZ Formula — Google's Hiring Secret

<div class="text-xs mt-2 opacity-60">How Google & Amazon train interviewers to score candidates. Use it to write your bullet points.</div>

<div class="mt-5 text-xl text-center font-bold py-4 rounded-xl bg-white/5 border border-white/10">
  "Accomplished <span class="text-green-400">X</span> as measured by <span class="text-yellow-400">Y</span>, by doing <span class="text-red-400">Z</span>."
</div>

<div class="grid grid-cols-3 gap-4 mt-4 text-sm">

<div v-click class="rounded-xl p-4 bg-green-900/15 border border-green-500/30">
  <div class="text-green-400 font-bold mb-1">X — The Win</div>
  <div class="text-xs opacity-60">What you achieved. The positive outcome.</div>
</div>

<div v-click class="rounded-xl p-4 bg-yellow-900/15 border border-yellow-500/30">
  <div class="text-yellow-400 font-bold mb-1">Y — The Proof</div>
  <div class="text-xs opacity-60">Numbers. %. ₦. People reached. Hours saved.</div>
</div>

<div v-click class="rounded-xl p-4 bg-red-900/15 border border-red-500/30">
  <div class="text-red-400 font-bold mb-1">Z — The How</div>
  <div class="text-xs opacity-60">Tools, skills, and actions you took.</div>
</div>

</div>

<v-click>
<div class="mt-4 text-center text-xs opacity-40">
  🧠 Recruiters spend ~7.4 seconds scanning a CV. Numbers make them stop and read.
</div>
</v-click>

---
layout: two-cols
---

# XYZ: Before & After

<div class="text-sm space-y-4 mt-4">

<div v-click class="rounded-xl p-4 bg-red-900/15 border border-red-500/30">
  <div class="text-red-400 font-semibold text-xs mb-2">❌ Weak</div>
  <div class="opacity-60 italic text-xs">"Assisted with NYSC community projects."</div>
</div>

<div v-click class="rounded-xl p-4 bg-green-900/15 border border-green-500/30">
  <div class="text-green-400 font-semibold text-xs mb-2">✅ XYZ Strong</div>
  <div class="opacity-80 text-xs leading-relaxed">"Led 15 corps members to organise a health outreach <strong class="text-green-300">(X)</strong>, reaching 450 community members and raising awareness by 40% <strong class="text-yellow-300">(Y)</strong>, by partnering with local PHCs and creating Canva IEC materials <strong class="text-red-300">(Z)</strong>."</div>
</div>

</div>

::right::

<div class="text-sm space-y-4 mt-4 ml-5">

<div v-click class="rounded-xl p-4 bg-red-900/15 border border-red-500/30">
  <div class="text-red-400 font-semibold text-xs mb-2">❌ Weak</div>
  <div class="opacity-60 italic text-xs">"Handled data entry during teaching."</div>
</div>

<div v-click class="rounded-xl p-4 bg-green-900/15 border border-green-500/30">
  <div class="text-green-400 font-semibold text-xs mb-2">✅ XYZ Strong</div>
  <div class="opacity-80 text-xs leading-relaxed">"Built a student performance database for 120 pupils <strong class="text-green-300">(X)</strong>, cutting grading errors by 85% and saving 15 hrs/week <strong class="text-yellow-300">(Y)</strong>, using automated Excel templates and pivot tables <strong class="text-red-300">(Z)</strong>."</div>
</div>

</div>

---

# CV Quick Checklist

<div class="grid grid-cols-2 gap-5 mt-4">

<div class="space-y-2">

<v-clicks>

<div class="flex gap-3 items-center py-2 border-b border-white/10 text-xs">✅ <span>1–2 pages max — no exceptions</span></div>
<div class="flex gap-3 items-center py-2 border-b border-white/10 text-xs">✅ <span>Clean font: Arial or Calibri, size 10–12</span></div>
<div class="flex gap-3 items-center py-2 border-b border-white/10 text-xs">✅ <span>Always send as <strong>PDF</strong> — never Word</span></div>
<div class="flex gap-3 items-center py-2 border-b border-white/10 text-xs">✅ <span>No photo unless the JD specifically asks</span></div>
<div class="flex gap-3 items-center py-2 border-b border-white/10 text-xs">✅ <span>Tailor every application — job keywords matter</span></div>
<div class="flex gap-3 items-center py-2 text-xs">✅ <span>Every bullet starts with a strong action verb</span></div>

</v-clicks>

</div>

<div v-click class="rounded-xl p-4 bg-red-900/15 border border-red-500/30 text-xs">

<div class="font-bold text-red-300 mb-3">🚫 Stop Doing These</div>

<div class="space-y-2 opacity-70">
  <div>· "References available on request" — remove it</div>
  <div>· Listing every WAEC subject</div>
  <div>· "To obtain a challenging role in a reputable organisation..."</div>
  <div>· Lying about your skills — you will be tested</div>
  <div>· Sending the same CV to every role</div>
</div>

</div>

</div>

---
layout: section
---

<div class="text-green-300 text-xs font-semibold uppercase tracking-widest mb-3">Part 2</div>

# Cover Letters

*The document most people skip — the one that tips the scale*

---

# Why a Cover Letter Matters

<div class="grid grid-cols-3 gap-4 mt-6 text-sm">

<div v-click class="rounded-xl p-5 border border-white/10 bg-white/5 text-center">
  <div class="text-4xl font-black text-green-300 mb-2">70%</div>
  <div class="text-xs opacity-60">of hiring managers read them — especially for entry-level roles where every CV looks the same</div>
</div>

<div v-click class="rounded-xl p-5 border border-white/10 bg-white/5 text-center">
  <div class="text-3xl mb-2">✍️</div>
  <div class="text-xs opacity-60">Proves you can <strong>communicate in writing</strong> — a skill nearly every role needs, and interviews can't always test</div>
</div>

<div v-click class="rounded-xl p-5 border border-white/10 bg-white/5 text-center">
  <div class="text-3xl mb-2">🪟</div>
  <div class="text-xs opacity-60">Lets you explain what your CV can't — gaps, career switches, NYSC placements, relocation</div>
</div>

</div>

<v-click>
<div class="mt-6 text-center text-yellow-300 font-semibold text-sm">
  A strong cover letter moves you from the "maybe" pile to the interview list — even if your CV is average.
</div>
</v-click>

---
layout: two-cols
---

# The 4-Paragraph Structure

<div class="text-sm space-y-3 mt-4">

<div v-click class="rounded-xl p-3 border border-blue-400/30 bg-blue-900/10">
  <div class="text-blue-300 font-bold text-xs mb-1">Para 1 — Who You Are</div>
  <div class="opacity-60 text-xs italic">"As a recent NYSC graduate with hands-on experience in digital marketing, I was genuinely excited to find the Marketing Associate role at your company."</div>
</div>

<div v-click class="rounded-xl p-3 border border-green-400/30 bg-green-900/10">
  <div class="text-green-300 font-bold text-xs mb-1">Para 2 — The Brag</div>
  <div class="opacity-60 text-xs">2–3 XYZ achievements. Connect directly to their needs. This paragraph wins interviews.</div>
</div>

<div v-click class="rounded-xl p-3 border border-purple-400/30 bg-purple-900/10">
  <div class="text-purple-300 font-bold text-xs mb-1">Para 3 — Why Them</div>
  <div class="opacity-60 text-xs">Name one specific thing about the company that genuinely excites you. Research first. Don't go generic here.</div>
</div>

<div v-click class="rounded-xl p-3 border border-yellow-400/30 bg-yellow-900/10">
  <div class="text-yellow-300 font-bold text-xs mb-1">Para 4 — Call to Action</div>
  <div class="opacity-60 text-xs">Thank them. Express availability for an interview. Confident — not desperate.</div>
</div>

</div>

::right::

<div class="ml-8 mt-4">

<v-click>

<div class="rounded-xl p-5 bg-white/5 border border-white/10 text-sm">

### The Golden Rule

**Brag with proof, not arrogance.**

<div class="mt-3 text-xs opacity-60 leading-relaxed space-y-2">

<div>You're not saying <em>"I'm the best candidate."</em></div>

<div>You're saying <em>"Here is evidence of what I've achieved — and here is why it's directly relevant to this role."</em></div>

<div class="mt-2">One sounds entitled. The other sounds confident. There's a big difference.</div>

</div>

</div>

</v-click>

</div>

---
layout: section
---

<div class="text-red-300 text-xs font-semibold uppercase tracking-widest mb-3">Part 3</div>

# Staying Safe Online

*The landmines nobody warns you about — until it's too late*

---

# The Job Hunt Makes You a Target

<div class="text-xs mt-2 opacity-60">Scammers know you're anxious, distracted, and checking your email obsessively. That makes you vulnerable.</div>

<div class="grid grid-cols-2 gap-4 mt-4 text-sm">

<div v-click class="rounded-xl p-4 border border-red-400/40 bg-red-900/10">
  <div class="font-bold text-red-300 text-sm mb-2">🎣 Phishing</div>
  <div class="text-xs opacity-60">"Congratulations! You've been shortlisted — click here to accept." They steal your credentials or install malware the moment you click.</div>
</div>

<div v-click class="rounded-xl p-4 border border-red-400/40 bg-red-900/10">
  <div class="font-bold text-red-300 text-sm mb-2">🐛 Worms & RATs</div>
  <div class="text-xs opacity-60"><strong>Worms</strong> spread and infect automatically. <strong>RATs (Remote Access Trojans)</strong> hand hackers full control — your screen, camera, keystrokes, saved passwords.</div>
</div>

<div v-click class="rounded-xl p-4 border border-orange-400/40 bg-orange-900/10">
  <div class="font-bold text-orange-300 text-sm mb-2">📄 PDF & Image Hijacking</div>
  <div class="text-xs opacity-60">22% of malicious email attachments are PDFs. A "job offer letter" with hidden links, QR codes, or embedded JavaScript. Opening it is enough.</div>
</div>

<div v-click class="rounded-xl p-4 border border-orange-400/40 bg-orange-900/10">
  <div class="font-bold text-orange-300 text-sm mb-2">🌐 Typo-Squatting</div>
  <div class="text-xs opacity-60">Fake sites: <code>linkdin.com</code>, <code>jobberman.ng.co</code>, <code>andelaa.com</code>. You think you're applying. You're handing your data to a scammer.</div>
</div>

</div>

---

# More Threats Worth Knowing

<div class="grid grid-cols-2 gap-5 mt-5 text-sm">

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5">

### 📧 Email Masking

Scammers send from `hr@outlook.com` or `recruitment.gtb@gmail.com`.

Real companies use their own domain.

<div class="mt-3 font-mono text-xs space-y-1">
  <div class="text-green-400">✅ hr@guarantytrust.com</div>
  <div class="text-red-400">❌ hr.gtbank@gmail.com</div>
</div>

<div class="mt-2 text-xs opacity-60 font-semibold">Check the actual sender address — not the display name.</div>

</div>

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5">

### 📱 Fake & Modded Apps

"Free Premium LinkedIn", cracked job-alert apps, modded WhatsApp from random websites.

Almost always packed with spyware.

<div class="mt-3 text-xs opacity-60">If you didn't pay for a premium product, <strong>someone else is — with your data.</strong></div>

<div class="mt-2 text-xs opacity-40">Only install from Google Play or the App Store.</div>

</div>

</div>

<v-click>
<div class="mt-4 rounded-xl p-3 border border-red-500/30 bg-red-900/15 text-xs text-red-200">
  ⚠️ <strong>68% of all cyberattacks start in your inbox.</strong> The job hunt keeps you there constantly. Every unsolicited email is a potential threat.
</div>
</v-click>

---

# Your Non-Negotiable Safety Rules

<div class="grid grid-cols-2 gap-5 mt-4 text-sm">

<div class="space-y-1">

<v-clicks>

<div class="flex gap-2 items-start py-2 border-b border-white/10 text-xs">
  <span>🚫</span><span>Never click links in unsolicited emails — go to the company website directly</span>
</div>
<div class="flex gap-2 items-start py-2 border-b border-white/10 text-xs">
  <span>📞</span><span>Verify every offer by calling the official company number — find it yourself</span>
</div>
<div class="flex gap-2 items-start py-2 border-b border-white/10 text-xs">
  <span>🏢</span><span>Official portals only: LinkedIn, Jobberman, MyJobMag, Glassdoor, NGCareers</span>
</div>
<div class="flex gap-2 items-start py-2 border-b border-white/10 text-xs">
  <span>🔐</span><span>Enable 2FA on everything — email, LinkedIn, banking, social media</span>
</div>
<div class="flex gap-2 items-start py-2 border-b border-white/10 text-xs">
  <span>🔑</span><span>Unique password per account + password manager (Google Password Manager is free)</span>
</div>
<div class="flex gap-2 items-start py-2 text-xs">
  <span>🛡</span><span>Scan every download before opening — Windows Defender is fine if it's updated</span>
</div>

</v-clicks>

</div>

<div v-click class="rounded-xl p-4 bg-blue-900/15 border border-blue-500/30 text-xs">

### 📬 Email Setup for Job Hunting

<div class="space-y-2 mt-3 opacity-70">
  <div>✅ Use <code>firstname.lastname@gmail.com</code></div>
  <div>✅ Create a dedicated <strong>Job Applications</strong> folder</div>
  <div>✅ Link a recovery email and phone number</div>
  <div>✅ Store recovery codes offline</div>
  <div>❌ Never share OTPs — no real recruiter ever asks</div>
</div>

<div class="mt-4 text-yellow-300 font-semibold">
  A professional email is a first impression too. <code>cutegirl2k@yahoo.com</code> is not getting callbacks.
</div>

</div>

</div>

---
layout: center
class: text-center
transition: fade
---

# Recap

<div class="grid grid-cols-3 gap-4 mt-6 text-left max-w-3xl mx-auto text-sm">

<div v-click class="rounded-xl p-4 bg-blue-900/15 border border-blue-500/30">
  <div class="text-blue-300 font-bold mb-2">📄 CVs</div>
  <div class="text-xs opacity-60 space-y-1">
    <div>· XYZ in every bullet point</div>
    <div>· Tailor to every job description</div>
    <div>· PDF · clean font · 1–2 pages</div>
    <div>· Beat ATS before you design</div>
  </div>
</div>

<div v-click class="rounded-xl p-4 bg-green-900/15 border border-green-500/30">
  <div class="text-green-300 font-bold mb-2">✉️ Cover Letters</div>
  <div class="text-xs opacity-60 space-y-1">
    <div>· Don't skip — 70% of HMs read them</div>
    <div>· Intro · Brag · Why them · Close</div>
    <div>· Proof beats arrogance every time</div>
  </div>
</div>

<div v-click class="rounded-xl p-4 bg-red-900/15 border border-red-500/30">
  <div class="text-red-300 font-bold mb-2">🔐 Online Safety</div>
  <div class="text-xs opacity-60 space-y-1">
    <div>· Verify before you click or download</div>
    <div>· Check domains, not display names</div>
    <div>· 2FA + unique passwords</div>
    <div>· Official portals only</div>
  </div>
</div>

</div>

<v-click>
<div class="mt-8 text-base font-semibold text-yellow-300">
  Stay consistent. Stay safe. Go get that bag after NYSC. 🚀
</div>
</v-click>

---
layout: center
class: text-center
---

# 🎁 Raffle Draw!

<div class="text-xs opacity-50 mt-2">Winners drawn from participants who submitted questions in the WhatsApp group</div>

<div class="grid grid-cols-3 gap-4 mt-8 text-sm max-w-2xl mx-auto">

<div v-click class="rounded-xl p-5 border border-yellow-400/50 bg-yellow-900/15">
  <div class="text-3xl mb-2">🥇</div>
  <div class="font-bold text-yellow-300 mb-1">1st Prize</div>
  <div class="text-xs opacity-60">LinkedIn Learning Premium — 1 month</div>
</div>

<div v-click class="rounded-xl p-5 border border-gray-400/40 bg-gray-800/20">
  <div class="text-3xl mb-2">🥈</div>
  <div class="font-bold text-gray-300 mb-1">2nd Prize ×2</div>
  <div class="text-xs opacity-60">Professional CV Review Vouchers</div>
</div>

<div v-click class="rounded-xl p-5 border border-orange-400/50 bg-orange-900/15">
  <div class="text-3xl mb-2">🥉</div>
  <div class="font-bold text-orange-300 mb-1">3rd Prize ×3</div>
  <div class="text-xs opacity-60">Data bundles — job hunting eats data</div>
</div>

</div>

---
layout: center
class: text-center
---

# Thank You! 🙏

<div class="mt-5 text-lg opacity-70">Questions? I'm right here.</div>

<div class="mt-2 text-sm opacity-40 italic">No dumb questions — only missed opportunities.</div>

<div class="mt-10 text-xs opacity-30">
  Stay safe · Stay sharp · Go get that bag 🚀
</div>
