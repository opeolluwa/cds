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

<div class="text-xs uppercase tracking-widest opacity-50 mb-4">NYSC CDS Talk · 2026</div>

# CVs, Cover Letters<br>& Online Safety

<div class="mt-4 text-lg font-medium text-blue-300 opacity-90">
  Land the job. Don't get scammed doing it.
</div>

<div class="mt-3 text-sm opacity-50">~45–60 mins · Q&A</div>

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


</div>

---
layout: two-cols
transition: slide-up
---

# About Me

<div class="text-sm leading-relaxed mt-4 space-y-3">

<div v-click>

**Adefemi Adeoye · @opeolluwa**

Electrical Engineering graduate, software engineer, and open-source contributor — nearly a decade building production systems and working with teams across Nigeria and internationally.

</div>

<div v-click>

**What I do:**
- Software engineer working on backend systems and developer tooling
- Active in global open-source communities — contributor, editor, and programme committee member

</div>

<div v-click>

**Why I'm giving this talk:**

I built most of what I know the hard way — no mentor, no playbook, just trial and error after service year.

Today you get the shortcut.

</div>

</div>

::right::

<div class="ml-8 mt-4 space-y-3">

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">⚡</div>
  <div class="font-semibold">Electrical Engineering · Software</div>
  <div class="opacity-50 text-xs mt-1">FUNAAB · Backend · Full-Stack</div>
</div>

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">🌍</div>
  <div class="font-semibold">Open Source · Global Community</div>
  <div class="opacity-50 text-xs mt-1">Editor · Conference Programme Committee</div>
</div>

<div v-click class="rounded-xl p-4 border border-white/10 bg-white/5 text-sm">
  <div class="text-2xl mb-1">📺</div>
  <div class="font-semibold">@opeolluwa</div>
  <div class="opacity-50 text-xs mt-1">GitHub · YouTube · X/Twitter</div>
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
transition: slide-up
---

# Phishing & Worms — A Closer Look

<div class="grid grid-cols-2 gap-5 mt-4 text-sm">

<div>

<div v-click class="rounded-xl p-4 border border-red-400/40 bg-red-900/10 mb-4">
  <div class="font-bold text-red-300 mb-2">🎣 How Phishing Works</div>
  <div class="text-xs opacity-70 leading-relaxed">Attacker crafts a message that looks legitimate — a job offer, interview invite, or HR portal link. You click. They either harvest your credentials on a fake login page, or silently drop malware on your device.</div>
</div>

<div v-click class="rounded-xl p-4 border border-red-500/30 bg-red-900/15 text-xs mt-3">
  <div class="font-semibold text-red-300 mb-2">Real-Looking Subject Lines Used by Scammers</div>
  <div class="space-y-1 opacity-70 font-mono">
    <div>"Your application to GTBank has been reviewed"</div>
    <div>"Urgent: Complete your Andela onboarding"</div>
    <div>"You've been shortlisted — confirm your slot"</div>
    <div>"Action required: verify your NYSC portal"</div>
  </div>
</div>

</div>

<div>

<div v-click class="rounded-xl p-4 border border-orange-400/40 bg-orange-900/10 mb-4">
  <div class="font-bold text-orange-300 mb-2">🐛 Worms — Self-Spreading Malware</div>
  <div class="text-xs opacity-70 leading-relaxed space-y-2">
    <div>Unlike a virus, a worm needs <strong>no action from you</strong> after the first infection. It copies itself across your contacts, shared drives, and connected devices automatically.</div>
    <div><strong>Job-hunt vector:</strong> You open a "CV template.docx" sent by a "career coach." The worm quietly emails itself to everyone in your Gmail contacts.</div>
  </div>
</div>

<div v-click class="rounded-xl p-4 border border-orange-500/30 bg-orange-900/15 text-xs">
  <div class="font-semibold text-orange-300 mb-2">RAT — Remote Access Trojan</div>
  <div class="opacity-70 space-y-1">
    <div>· Full access to your screen and files</div>
    <div>· Records every keystroke — including passwords</div>
    <div>· Can activate your camera and microphone silently</div>
    <div>· Often hidden inside "offer letter" PDFs or ZIP attachments</div>
  </div>
</div>

</div>

</div>

---
transition: slide-up
---

# Viruses, Typo-Squatting & More

<div class="grid grid-cols-2 gap-5 mt-4 text-sm">

<div>

<div v-click class="rounded-xl p-4 border border-purple-400/40 bg-purple-900/10 mb-4">
  <div class="font-bold text-purple-300 mb-2">🦠 Viruses — Attach & Corrupt</div>
  <div class="text-xs opacity-70 leading-relaxed space-y-2">
    <div>A virus attaches itself to a legitimate file. When you open the file, the virus runs. It can delete files, corrupt your OS, or use your device to attack others.</div>
    <div><strong>Common delivery:</strong> Cracked MS Office, "free CV templates" from random sites, pirated software with a bundled installer.</div>
  </div>
</div>

<div v-click class="rounded-xl p-4 border border-yellow-400/40 bg-yellow-900/10 text-xs">
  <div class="font-semibold text-yellow-300 mb-2">📄 Malicious PDFs & Image Files</div>
  <div class="opacity-70 space-y-1">
    <div>· Embedded JavaScript that runs on open</div>
    <div>· Hidden links disguised as QR codes</div>
    <div>· "Offer letter.pdf" that auto-downloads a payload</div>
    <div>· JPG or PNG files with steganographic malware</div>
  </div>
</div>

</div>

<div>

<div v-click class="rounded-xl p-4 border border-red-400/40 bg-red-900/10 mb-4">
  <div class="font-bold text-red-300 mb-2">🌐 Typo-Squatting — Fake Portals</div>
  <div class="text-xs opacity-70 leading-relaxed mb-3">Scammers register domains that look almost identical to real job sites. You type the URL slightly wrong — or click a link in an email — and land on a pixel-perfect fake.</div>
  <div class="font-mono text-xs space-y-1">
    <div class="text-green-400">✅ jobberman.com</div>
    <div class="text-red-400">❌ jobberman.ng.co &nbsp;·&nbsp; j0bberman.com</div>
    <div class="text-green-400">✅ linkedin.com</div>
    <div class="text-red-400">❌ linkdin.com &nbsp;·&nbsp; linkedln.com</div>
    <div class="text-green-400">✅ andela.com</div>
    <div class="text-red-400">❌ andelaa.com &nbsp;·&nbsp; andela-apply.com</div>
  </div>
</div>

<div v-click class="rounded-xl p-3 border border-white/10 bg-white/5 text-xs">
  <div class="font-semibold mb-1">How to verify before you enter credentials</div>
  <div class="opacity-60 space-y-1">
    <div>· Check the padlock — but know it's not enough alone</div>
    <div>· Type the URL yourself; don't copy from emails</div>
    <div>· Search the company on Google; click the official result</div>
    <div>· If unsure — close the tab. Find it another way.</div>
  </div>
</div>

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

# Thank You! 🙏

<div class="mt-5 text-lg opacity-70">Questions? I'm right here.</div>

<div class="mt-2 text-sm opacity-40 italic">No dumb questions — only missed opportunities.</div>

<div class="mt-10 text-xs opacity-30">
  Stay safe · Stay sharp · Go get that bag 🚀
</div>
