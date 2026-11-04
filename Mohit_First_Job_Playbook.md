# FIRST PAID ROLE
## Mohit’s field manual for Pathcraft

**Linux · Technical support · Application support · Cloud operations**  
Version 1.0 · 4 November 2026 · Designed for an IITM BS student with Python familiarity, some Linux experience and no professional experience.

**Daily entry:** [START_HERE.md](START_HERE.md) · **Included app:** [Pathcraft.html](Pathcraft.html) · **Local setup/source:** `Pathcraft_Source.zip`

> **The mission:** earn a paid technical role that covers your actual living costs, gives you useful work and lets you continue your degree. The immediate destination is an offer you have checked, accepted and can afford to join.
>
> **The working rule:** one project, one current task, one application pipeline. Read the section needed for today’s work. You do not have to finish reading this manual before starting.

No document can deliver a job with 100% certainty. Employers, eligibility, vacancies and timing remain outside your control. This manual makes your work observable and gives you a way to change tactics when evidence shows a problem. Its schedules and application targets are planning choices, not scientifically established hiring thresholds.

---

## Open this at the moment you need it

| Situation | Go directly to |
|---|---|
| “Tell me what to do now.” | [1. Your first 45 minutes](#1-your-first-45-minutes) |
| “How do I use the website?” | [3. Pathcraft operating manual](#3-pathcraft-operating-manual) |
| “I keep disappearing after a good start.” | [4. The daily return system](#4-the-daily-return-system) |
| “Which topics, and in what order?” | [6. The first-job route](#6-the-first-job-route) |
| “I am stuck on permissions/networking/Docker.” | [8. The hard-topic field guide](#8-the-hard-topic-field-guide) |
| “I keep watching and forgetting.” | [9. How to learn and retain](#9-how-to-learn-and-retain) |
| “Where are the resources?” | [10. The resource shelf](#10-the-resource-shelf) |
| “Am I ready to apply?” | [11. The interview gate](#11-the-interview-gate) |
| “I applied and nothing happened.” | [14. Diagnose the hiring funnel](#14-diagnose-the-hiring-funnel) |
| “A company offered something.” | [15. Check the offer](#15-check-the-offer) |
| “I missed days / exams took over.” | [16. Recovery and real-life obstacles](#16-recovery-and-real-life-obstacles) |
| “Which exact app IDs does this cover?” | [Appendix A. Coverage map](#appendix-a-coverage-map) |

## 1. Your first 45 minutes

Do this before opening another roadmap, productivity video or course catalogue.

| Minutes | Action | Finish with |
|---|---|---|
| 0–10 | Put the kit in a permanent folder. Open Pathcraft and bookmark it as **FIRST JOB — OPEN FIRST**. For now the single HTML is enough. | One working entry point. |
| 10–15 | Leave the target on Level 1. Open `J01`, then `L01`. Enter the next action below. | An explicit restart instruction. |
| 15–30 | In a disposable directory, create a text file, find it using absolute and relative paths, copy it, archive it and recover the copy elsewhere. Use documentation when needed. | Actual terminal evidence. |
| 30–40 | In `L01` and any other topic demonstrated, save your command/output evidence and mark the appropriate status. | A truthful record of what happened. |
| 40–45 | Save the next action and export one JSON backup. Choose the next start time. | Tomorrow already has an entry point. |

Use this first next action if you have none:

```text
Open the lab terminal. Run pwd and ls -la in my practice directory.
Then demonstrate one absolute and one relative path to the same file.
Expected result: both identify the same file. Evidence goes in L01.
```

**A successful first day is a demonstrated task and a restart instruction.** The rest of today can include college and ordinary life. Do not turn setting up this system into a new week-long project.

## 2. Define the job before defining the syllabus

Your first role does not need “DevOps” in its title. It needs enough technical work, acceptable conditions, an affordable joining plan and someone you can learn from.

| Search lane | Useful work to look for | Extra preparation when a real vacancy needs it |
|---|---|---|
| Linux / hosting support trainee; junior system administrator | Logs, services, DNS, SSH, permissions, backups, incidents | Hosting control panels; basic Apache or mail concepts if explicitly required |
| Application / product technical support | Reproduce problems, inspect HTTP/API errors, query data, write clear tickets, escalate to engineering | SQL, API tools and product-specific troubleshooting |
| NOC / infrastructure operations trainee | Monitor alerts, investigate outages, collect evidence, hand over incidents | Network fundamentals and the monitoring product used by that employer |
| Cloud support / cloud operations trainee | Linux, identity, network boundaries, VM lifecycle, cloud incidents | One cloud provider; begin with AWS only if suitable vacancies justify it |
| Junior DevOps / paid DevOps internship | Build, deploy, diagnose and automate under supervision | Docker, one CI pipeline, basic cloud; Terraform if the role needs it |

**Default:** prioritise the first two lanes. Include NOC and eligible trainee cloud roles. DevOps is a parallel application lane when your demonstration supports it, not a title you must obtain before earning money. You can also apply directly to a suitable DevOps internship; support is not a compulsory career stage.

### The 90-second vacancy screen

Before tailoring an application, answer:

1. **Eligibility:** does it accept a current student / your actual qualifications? Is completed graduation mandatory? Is the experience requirement genuinely entry-level?
2. **Work:** will you investigate systems, application issues or operational incidents? Ask what a junior actually does in week one.
3. **Money:** is the position paid, and is the fixed take-home sufficient for this location and shift?
4. **Learning:** who reviews changes, handles escalations and trains a fresher?
5. **Schedule:** can the shifts and joining date coexist with compulsory exams?

Classify as **Apply**, **Clarify**, or **Skip**. For a preferred degree or an ambiguous “equivalent experience” requirement, an honest application can be worthwhile. For a stated mandatory qualification you do not have, clarify once or skip. Do not falsify a form to enter a pipeline.

The job title alone is weak evidence. Zoho’s official technical-support listing, for example, describes customer calls and night shifts; HashRoot’s DevOps page lists prior experience and a wider stack. They illustrate different hiring expectations, not confirmed offers suitable for you. [Sources J1–J2](#job-and-programme-sources)

### State your education accurately

Use wording like this, adjusting only to verified facts:

```text
IIT Madras — BS in Data Science and Applications, pursuing
Currently studying at diploma level; online programme.
Available for [actual hours / full-time work], with scheduled in-person exams.
```

Being **at diploma level** does not mean a diploma has already been awarded. Put an expected completion date only if you can justify it. Your current completed qualification must be reported accurately in mandatory eligibility fields.

**Use the IITM channel, but do not depend on it.** The placement portal’s FAQ currently says a completed diploma is needed for internship opportunities and a BSc for employment opportunities. An older programme page describes different diploma-exit placement routes. Ask the Industry Interaction Cell which current rules apply to your exact credits and status before paying or relying on a route. Keep applying independently meanwhile. [Sources J3–J4](#job-and-programme-sources)

## 3. Pathcraft operating manual

### Choose one stable place to use it

**Fast start:** open `Pathcraft.html`. It contains the app and curriculum. Its external resource links need internet. Local-file browser storage is less predictable across browsers and file locations, so export backups.

**Recommended local use:** extract `Pathcraft_Source.zip`, enter its `Pathcraft` folder and run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Open `http://localhost:8000`. Keep the terminal running while you use it. Use that exact host, port and browser profile each time. `localhost`, `127.0.0.1`, another port and a hosted address can have different saved workspaces. Do not serve the source folder containing personal backups to a public network.

For hosting later, the source README covers deployment of `dist/`. Spend no more than one setup session on hosting before returning to the learning task. A hosted page is convenient; it does not by itself synchronise progress.

### What each screen is for

| Screen | Use it for | Do not infer |
|---|---|---|
| Overview | Your current target, next action, ready topics and totals | A percentage is not a hiring probability. |
| Learning roadmap → Branches | Finding a subject without hiding future subjects | You do not need to complete every branch. |
| Learning roadmap → Graph | Selecting a branch and seeing required connections; zoom or scroll | Dashed nodes are direct prerequisites from other branches, not an exhaustive whole-career graph. |
| Topic library | Search IDs such as `N09`; filter by level, branch, status or readiness | A topic outside your target is still accessible. |
| Topic panel | Read task, proof check and resources; save notes, evidence and next action | Opening a resource does not verify the skill. |
| Project checkpoints | Check demonstrations independently of topic learning | The app does not inspect your terminal or grade a demonstration. |
| Applications | Record role, company, URL, stage, follow-up date and notes | It does not submit applications or contact recruiters. |
| Study log | See recorded sessions and activity | Timer minutes measure elapsed recorded time, not concentration. |
| Data & settings | Change name/target, export/import, optional backup configuration | Cloud backup is not already connected. |

The `/` shortcut opens topic search when you are not typing in a field. `Esc` closes an open dialog. Use the colour-theme control for light/dark mode.

### The honest status policy

| Status | Your meaning |
|---|---|
| Not started | No current attempt. |
| Practising | You have attempted it but cannot yet demonstrate the proof reliably. |
| Verified | You can perform the proof, explain the main decision and handle a small variation. Documentation is allowed unless an interview says otherwise. |
| Revisit | You previously understood it but now need a repair or another retrieval attempt. |

Save three things when you verify a topic:

```text
Evidence: command(s), relevant output and what it proves.
Reasoning: why that command/change was appropriate.
Variation: one changed condition and the result.
```

The software allows you to tick a topic without evidence. **This policy is your discipline, not an enforced app feature.** Later verified topics are not automatically revoked when you reopen an earlier one; review related claims yourself.

A topic becomes “Ready” when its required prerequisites are marked Verified. Readiness is advice, not a lock. You can inspect any topic. Current-path progress counts verified, non-optional topics through your selected level, unless you enable optional topics in settings. Level 1 has **51 core checks**. You can apply before 51/51.

### Notes and the next-action field

Do not transcribe documentation. Keep notes to the misconception, command and evidence you will need again.

Bad next action: “Finish networking.”

Good next action:

```text
In the lab VM, run ss -ltnp and find the port-8080 listener.
Then curl http://127.0.0.1:8080/ from the VM.
If local access works, test from the host before changing a firewall.
```

When another topic is newly ready, finish or park the current task deliberately. The “ready” list is not permission to start six topics.

### Editing, timers and backups

- **Edit:** change a topic’s task, resource, depth, duration or prerequisite IDs. Missing references and dependency cycles are rejected. Built-in content can be restored without discarding its notes/progress. Custom topics can be removed after their references are removed.
- **Do not redesign the curriculum during your first working week.** Put change ideas in a parking note; make a weekly decision using real blockers.
- **Focus:** use the 25-minute timer if it helps you start. Pause/resume as needed; “Record & finish” logs a session. A 60–90 minute practical session can be better for a multi-step incident. Recording does not automatically verify the topic.
- **Export:** use Export backup after important edits and during the weekly review. Keep a dated copy outside the app folder; keep a second private copy off the laptop when practical.
- **Import:** validation runs before restoration. Accepting a restore replaces the current workspace after triggering a download of its existing data. Confirm the download actually arrived. A previous snapshot may also be kept locally; the downloadable file is your dependable recovery mechanism.

Progress, notes, edits, project checks, jobs and recorded sessions live in this browser’s `localStorage`. They normally survive reloads and browser restarts. Clearing site data, private browsing, browser loss or changing origin can remove access to them. Your exported JSON carries that workspace. **Copying `dist/` alone backs up the app, not your browser progress.**

Optional Supabase backup uses manual **Push backup / Restore cloud backup**. Its code, SQL ownership policies and setup instructions are included; live authentication and cross-account isolation still need testing in your own setup. Keep that task parked until you actually need cross-device access. Do not publish backup JSON, credentials, SSH keys or personal recruiter notes in your repository.

## 4. The daily return system

Your known failure point is often **re-entry**, not understanding. Design the first two minutes so they do not require a new decision.

### Put the task in your environment

1. **One doorway:** bookmark the stable Pathcraft address. Configure your browser to open it on startup if useful. Keep only the current task’s resource tab alongside it.
2. **One physical cue:** place a card on the keyboard: “Open FIRST JOB. Read the next action. Do ten minutes.”
3. **One time-and-place cue:** “After breakfast and washing, at my desk or library seat, I open Pathcraft before feeds or AI chat.” Pick a realistic clock window, such as 09:00–09:15, too.
4. **One restart instruction:** leave the command, file or question in the topic’s next-action field before stopping.
5. **One human witness:** if Ashwin agrees, send one brief proof update on agreed days. Ask him for two short practical reviews a week. His help is useful, but the routine must still work when he is busy.

This applies the research idea of an **if–then plan**: connect a recognisable situation to an action. It is a tool, not a guarantee that motivation or obstacles disappear. [Source L2](#learning-method-sources)

**Nothing in the current app sends daily notifications or blocks your phone.** Set a normal calendar/phone reminder yourself, and keep the laptop bookmark visible. An alarm’s wording should say what to do, not just “study”. No new productivity subscription is necessary.

### Your three-line daily card

```text
TODAY'S PROOF: __________________________________________
TODAY'S MARKET ACTION: __________________________________
NEXT START: time/place + first command __________________
```

Before the application phase, a market action can be checking one employer’s eligibility or improving one factual résumé bullet. Afterwards it should usually be an eligible application, referral request, follow-up or interview.

You may keep this card in a private text file or paper notebook. Pathcraft holds detailed progress. The card is only the doorway, not a second elaborate tracker.

### Start, work, close

**Start — 3 minutes:** open the current topic; read yesterday’s next action; move the phone away; open one terminal.

**Work — the available block:** produce the planned proof. If you find a prerequisite gap, repair that exact gap, then return. Do not restart the whole subject.

**Close — 5 minutes:** save evidence; choose an honest status; write the first next action; record any application result. Stop when the block is over unless continuing is a deliberate choice.

**Measure weekly returns, not an unbroken streak.** A small return after a bad day is useful. Opening the page without doing anything is a cue delivered, not a completed study session.

### The roadmap-hopping rule

For the next **four weeks**, this is the default plan. Keep a “Later” note for Kubernetes, a new course, an exciting AI tool or a new career idea. Review it once a week for ten minutes.

Change the plan immediately for a real interview requirement, a confirmed eligibility problem, a financial deadline or an unusable resource. Otherwise change it only when the weekly review can name the bottleneck and the smallest experiment to fix it. “A video made another path sound faster” is not sufficient evidence.

Do not ask an AI for a fresh roadmap when you feel behind. Ask: “Here is my last proof and my current failure. What is the smallest repair inside this plan?”

## 5. A week that can coexist with IITM

Start with **four focused job-preparation hours on five or six days**, not a promise to work every waking minute. Below is an example normal day. Shift the clock to match your actual sleep, meals and gym; keep the order and outputs.

| Window | Work | Boundary |
|---|---|---|
| 09:00–10:30 | Main lab / incident | One topic cluster; 90 minutes including short pauses as needed |
| 10:45–11:30 | Retrieval, explanation and lab repair | Repeat yesterday’s key skill before reading |
| 11:30–12:15 | Applications / employer research | A limited batch, then close the sites |
| 14:00–16:00 | IITM mathematics, coursework or assignments | Active problem solving; adjust upwards when the actual workload needs it |
| 16:15–17:00 | Second lab block or interview practice | Borrow this for college when an assignment is at risk |
| 17:00–17:15 | Evidence, backup if due, next action | Close the work loop |
| Evening | Gym, cooking, food, bath, friends; optional short guitar time | These remain ordinary life, not failures of commitment |

This supplies four job-preparation hours plus two protected college hours before adjustments. Check weekly assignment deadlines first. Two college hours may be insufficient in a hard week; reduce optional infrastructure study rather than quietly allowing coursework to collapse.

| Day mode | Job work | College / life response |
|---|---|---|
| Normal | About 4 focused hours; one main output plus market work | Planned problem-solving block and basic living tasks |
| Good focus | Extend a useful lab to 90 minutes; take a break before deciding on another | Do not spend tomorrow’s sleep or ignore a due assignment |
| Exam / assignment pressure | 20–40 minutes of retrieval, a small repair, or an interview-related action | Move the available study capacity to IITM; protect scheduled interviews |
| Bad day | 10 minutes on the saved next action + 5 minutes recording + 5 minutes choosing the next start | No catch-up marathon; basic meals and hygiene still happen |
| Weekly review day | 30–45 minute review; optionally one light retrieval | Time outside the room and practical errands |

**Do not reuse old festival or exam dates from the chat.** Enter the next real examination, submission and travel dates from your current IITM calendar. Put an exam-pressure mode on the five days before a major exam, then adjust to the actual workload. Tell interviewers about specific unavoidable conflicts early.

If job preparation is not moving, review actual outputs before increasing hours. Four hours of videos or AI conversation is not the same as four hours of attempts, evidence and applications.

## 6. The first-job route

### The map ends at the first suitable offer

| Stage | Outcome | What unlocks the next stage |
|---|---|---|
| A — Establish a working baseline | A stable app, disposable lab, accurate profile and real attempts | You can run a service and capture evidence |
| B — Support foundation | Diagnose service, HTTP, DNS, permission and storage problems; restore a backup | You can demonstrate the support interview gate |
| C — Apply and repair | Suitable applications, practical interviews and a measured failure log | Employer feedback determines the next study task |
| D — Add a narrow extension if needed | Docker/cloud/SQL/CI evidence matching your actual targets | A relevant interview or a repeated vacancy requirement justifies it |
| E — Accept and join | Written paid offer, affordable relocation and workable exam plan | Shift study toward the employer’s actual stack |

**Start trainee applications during A/B.** Do not wait for complete confidence, a polished cloud deployment or 51 ticks. For ordinary support interviews, use the practical gate in section 11 to judge your readiness. Keep applying while you improve.

### The 14-session learning sequence

These are **work sessions, not mandatory consecutive calendar days**. Budget roughly 60–120 minutes per session, with extra continuation for failures. Your existing Linux/Python knowledge can shorten an item only when you demonstrate it. A weak topic may need several sessions.

You can split a session, combine easy ones or move an interview-driven task earlier. Do not mark all IDs verified just because one session finished; each has a separate proof check in Pathcraft.

| Session | Pathcraft IDs | Main task and evidence | Stop here for the first pass |
|---|---|---|---|
| 1 | `J01`, `L01`, `L02`, `G01` | Create the lab folder and repo; demonstrate paths, safe copying, a diff and one real commit. Draft the education line. | No shell customisation or GitHub-profile redesign. |
| 2 | `L03`, `L04`, `L05`, `G02` | Search sample logs; separate stdout/stderr; archive and recover a small directory; ignore personal data. | Basic patterns and pipelines; no advanced awk/regex course. |
| 3 | `L06`, `L07`, `S01` | In the disposable VM, reproduce and fix an access failure for a non-root service user. Record why the permission change is narrow. | Ownership, groups, directory traversal and ordinary rwx. |
| 4 | `L08`, `L09`, `L10`, `L12` | Install one server package from a trusted repository; stop/start it; investigate a failed service with logs. | Explain process vs service, start vs enable, and the evidence. |
| 5 | `N01`, `N02`, `N03` | Draw host, guest VM, loopback and listener; identify addresses and routes; work two CIDR examples. | One request path; no CCNA-sized detour. |
| 6 | `N04`, `N05`, `N06`, `N09` | Separate a name-resolution error, refused connection, timeout and HTTP error in a controlled lab. | Distinguish observations; do not “fix” all failures with firewall changes. |
| 7 | `N07`, `N08`, `N11`, `N12` | Serve Pathcraft through Nginx in the VM. Use SSH from the host. Capture request and error logs. | One server, narrow access, readable configuration. |
| 8 | `L16`, `C03`, `C04` | Write an HTTP health script with a timeout, useful output and correct success/failure exit codes. | Standard library is enough. No API framework required. |
| 9 | `O01`, `O02`, `O04` | Run one incident end to end; write a ticket, customer update and escalation with evidence. | Clear, short operational writing; no ITIL certification course. |
| 10 | `O03`, `O05`, `L14` | Restore service files into a different directory; diagnose a permission failure and inspect byte/inode capacity. | No intentionally filling your everyday laptop disk. |
| 11 | `G03`, `G04`, `J02`, `J03` | Push clean lab evidence; make and revert a harmless change; record a two-minute project explanation. Submit eligible applications. | Repository is inspectable and honest, not visually perfect. |
| 12 | Section 11 gate; `J04` as useful | Let Ashwin or another reviewer introduce an unknown lab fault. Diagnose it aloud; record gaps. | Repair the actual gaps before adding tools. |
| 13 | `L11`, `L13`, `L15`, `L17` | Add a small custom service; inspect CPU/memory/storage; schedule one health check. | Explain behavior after restart/reboot; no kernel tuning. |
| 14 | `C01`, `C02`, `C05`, `C06`, `C07`, `C08`, `N10`, `S02` | Work remaining small checks over continuation blocks: safe scripting, structured output, SQL, TLS and patching. Prioritise SQL for application-support interviews. | This cluster is a queue, not eight mastered topics in 90 minutes. |

**The application deadline is not the end of session 14.** By the end of your first working week, submit to genuine trainee positions you honestly qualify for, even if some foundation checks remain. If you cannot yet perform the advertised work, say so and target training roles; do not claim independent administration.

As a planning estimate, reserve **40–70 hours for the first support lab and foundation work**, then reassess from demonstrated skills. That can span two or three normal weeks or longer around exams. It is not a promised readiness date, and a hiring process can take additional weeks. Existing demonstrated skill can shorten preparation; eligibility cannot be solved by study speed alone.

### What stays parked

Before a suitable first offer, do not study Kubernetes, GPU infrastructure, distributed training, multi-cloud architecture, advanced Terraform modules or a full observability platform unless a concrete suitable interview demands a bounded part. Do not make ECS a compulsory first-job requirement. EC2 is sufficient for the optional basic AWS deployment demonstration.

RHCSA and cloud certifications can be useful for some employers. They are **not purchases required by this plan**. Consider one only when a meaningful share of suitable vacancies requests it, the cost is affordable and your lab proof already exists. Do not replace applications with exam collection.

### Optional extensions — choose from real demand

| Signal from suitable roles | Study next | Demonstration to finish with |
|---|---|---|
| Linux/cloud roles regularly mention containers | `D01–D11`, with required gaps such as `L15` and `C05` repaired first | Build the supplied site image, publish a local port, inspect logs, recreate containers and explain persistent data. |
| Several eligible cloud roles need AWS | `A01–A04`, `A06–A10`, `S03`; add `O06`/`A12` if monitoring is requested | A short-lived controlled deployment; request path, access model, recovery and cleanup record. |
| Junior DevOps interview needs CI | `CI01–CI05`, reading their prerequisites first | One workflow tests the repo and fails when you intentionally break a real check. |
| Employer needs basic Terraform | `T01–T02`; relevant provider documentation | Plan, create, inspect change and destroy in an owned lab; no claim of production IaC ownership. |
| Application support requires SQL | `C07–C08`; extend aggregates and read-only debugging | Explain a join/NULL problem on synthetic data and return the correct rows. |
| Most viable local jobs are Windows/AD support | Bounded `E01–E04` branch, after an informed decision | Show services, Event Viewer and account/DNS concepts in a legitimate lab. |

Keep **one extension active**. On an ordinary application-phase day, reserve about half of job-prep time for market work/interviews, a quarter for retrieval/repair and a quarter for the selected extension. Change those proportions for an actual scheduled assessment.

## 7. One project that earns technical conversations

**Project name:** Pathcraft Operations Lab. The supplied UI is the application you operate. Your contribution is deployment, diagnosis, automation and recovery evidence. State that attribution openly.

### Minimum topology

1. Your laptop browser requests the service.
2. An Ubuntu lab VM runs Nginx and serves the supplied static files.
3. Your health script checks the response with a timeout.
4. Logs and incident notes explain what failed and what restored service.

Use a normal Ubuntu Server LTS VM that your laptop can run comfortably. Start with one guest; allocate resources the host can spare. Use a separate test folder if you temporarily have no VM. For systemd, SSH, firewall and privileged configuration drills, move to a disposable VM with a recovery console. Do not experiment on Ashwin’s or anyone else’s live server.

Prefer host-only networking or a deliberately configured NAT forward for host-to-guest practice. Write down which side owns each address and forwarded port. If a VM cannot be installed, do read-only fundamentals locally and explicitly mark unperformed server drills as pending.

### Build it in releases

| Release | Add | Inspectable proof |
|---|---|---|
| `v0.1-local` | Source attribution, local serving, accurate README | Screenshot/recording and the exact launch command |
| `v0.2-support` | Nginx VM, health script, backup/restore, three incident notes | Known URL/port, logs, correct exit codes and recovered files |
| `v0.3-recovery` | Unknown-fault drill, scheduling, service configuration, handover | Before/after evidence and a reviewer’s feedback |
| Optional `v0.4-container` | Container build and controlled recreation | Your Dockerfile explanation, image tag and state-location demonstration |
| Optional `v0.5-cloud` | Short-lived cloud lab with restricted access | Diagram, observed checks, resource inventory and cleanup evidence |
| Optional `v0.6-ci` | One real automated check | A failing run that blocks your chosen release step, then a passing fix |

The first three releases are enough to start serious support conversations. The optional releases extend the same repository. Do not turn “one big project” into “one endlessly unfinished project”. Each release must be demonstrable alone.

### Suggested repository shape

```text
pathcraft-operations-lab/
  README.md
  app/                 supplied static site; preserve attribution
  ops/                 your reviewed service/proxy examples
  scripts/             your health check and safe backup helper
  docs/incidents/      short, synthetic incident reports
  docs/runbooks/       start, diagnose, recover, hand over
  docs/architecture.md
  evidence/            selected, sanitised output and demo link
  .gitignore
```

Use a separate repository folder or deliberately document changes to the supplied source structure. A README command must match the real layout; do not claim the source package’s `dist/` command works after moving files into `app/` without updating it.

Do not publish private progress exports, application notes, host keys, access tokens or credentials. Synthetic logs and a small demo dataset are enough. Audit staged files with `git diff --cached` before publishing.

**README order:** what the service does → how to run → topology → your contributions → incident evidence → recovery → limitations. Put the best two-minute demonstration near the top. A recruiter should not have to watch a twenty-minute screen recording to discover the result.

Example résumé bullet **only after completing and measuring the work**:

```text
Operated a Linux/Nginx lab serving Pathcraft; wrote a timeout-aware
Python health check and documented recovery from [actual number]
controlled service, permission and HTTP failures, with reproducible evidence.
```

This is a personal lab, not employment or a production service. Speed and scale claims belong in the résumé only when you actually measured them.

## 8. The hard-topic field guide

Use the relevant card **while the failure is in front of you**. Its purpose is to reduce confusion and produce one transferable skill. The commands below illustrate observations; run them only against your lab, adjusting names and paths to your real setup. They are not a universal production runbook.

### 8.1 Permissions: reason as the process’s user

**Model:** a process runs with a user identity and group memberships. Access depends on the file and the path leading to it. A web server can fail to read a perfectly readable file because a parent directory cannot be traversed by its worker user.

**First attempt:** put a synthetic page in a lab-only directory. Confirm the Nginx worker identity in your configuration/process list. Introduce one controlled permission error, then inspect:

```bash
id
ls -ld /srv /srv/pathcraft
ls -l /srv/pathcraft/index.html
namei -l /srv/pathcraft/index.html
```

If the lab worker really is `www-data`, test as it:

```bash
sudo -u www-data test -r /srv/pathcraft/index.html
printf 'read test exit=%s\n' "$?"
```

`0` means that test succeeded. A failed test does not tell you the whole cause: examine the path, ownership and groups. Directory execute permission means traversal/search; it does not mean the directory is a runnable programme.

**Proof:** restore access with a narrow, explained ownership/group/mode change; show the HTTP response and relevant log evidence. State whether ACLs or a mandatory access-control policy could matter if ordinary permissions appear correct.

**Stop:** understand user/group/other, `rwx`, common modes and parent traversal. Park advanced ACL/SELinux work until a real need. Avoid `chmod -R 777`, running the service as root, or disabling protections to make the error disappear. [R1, R2]

### 8.2 Services: separate process state from application health

**Model:** systemd supervises a configured service process. “Active” is an observation about that unit; it is not proof that the expected web page works.

Use a real unit name from your lab:

```bash
systemctl status nginx --no-pager
journalctl -u nginx --since '15 minutes ago' --no-pager
ss -ltnp
curl --max-time 3 -i http://127.0.0.1/
```

If a service exits, read its first relevant error. Check its executable, working directory, user, configuration and environment before restarting repeatedly. Your interactive shell’s environment is not automatically the service’s environment.

For a custom unit, explain `User`, `WorkingDirectory`, `ExecStart`, restart policy and the install target. `start` affects current runtime; `enable` configures startup links. After changing a unit definition, use `daemon-reload`; changing Nginx’s own config is a separate action. Validate that config before a reload.

**Proof:** make one harmless lab configuration fail, collect its error, fix it and verify the HTTP result. Later confirm the intended boot behavior in the VM.

**Stop:** one simple supervised service. Park every unit type and every restart/hardening option. Use the upstream manual as a reference, not a book to memorise. [R3, R4]

### 8.3 Network reachability: identify where the observation was made

**Model:** browser → name lookup → destination address → route/access boundary → listening socket → HTTP handler. Name the machine or namespace at every step.

`127.0.0.1` in a guest VM is the guest. In a container it is that container. On the laptop it is the laptop. `0.0.0.0` is a bind wildcard, not the address you should use as a portable browser destination.

| Observation | Investigate next | Avoid concluding |
|---|---|---|
| Name cannot resolve | Name, resolver, record, cache and local configuration | “The web server is down.” |
| Connection refused | Wrong port/address, absent listener, explicit rejection | “It must be DNS.” |
| Connection times out | Route, dropped traffic, target state, access boundaries | “Every timeout is a security-group problem.” |
| HTTP 403/404 | You reached an HTTP handler; inspect permissions, path and routing | “The port is closed.” |
| HTTP 502 through a proxy | Proxy/upstream path and the relevant logs | “Restart everything.” |
| HTTP 200, wrong content | Host/path, stale deployment, redirect or wrong service | “The application is healthy.” |

On the target, inspect the listener and test locally first. Then test the guest address from the host. Only then inspect network boundaries. Run `curl -v --max-time 3` to see connection/request details; keep private headers and tokens out of shared output.

**Proof:** explain a local-success / remote-failure case without randomly changing three things. Draw the request path and identify the untested boundary. [R5, R6]

### 8.4 DNS and CIDR: use small examples, then return to the request

For DNS, compare a hostname lookup with a known destination. In an owned local lab, this command deliberately bypasses DNS for one request while preserving the requested hostname:

```bash
curl --resolve pathcraft.test:8080:127.0.0.1 \
  --max-time 3 http://pathcraft.test:8080/
```

It assumes a service really listens on your current machine’s port 8080. A successful result does not repair DNS; it helps isolate the failing layer. A hosts-file entry also does not prove public DNS works. For HTTPS, certificate names must still match; bypassing certificate checks is not a valid fix.

For IPv4 CIDR, first explain that `/24` leaves 8 address bits, giving 256 addresses. `/26` leaves 6, giving blocks of 64. Practise the boundaries of `192.168.10.0/26`, `.64/26`, `.128/26` and `.192/26`. Separate total addresses from usable addresses; provider reservations differ. Then identify your lab IP, subnet and default route.

**Proof:** explain whether two example addresses share a given subnet and where traffic to another subnet goes. Park long binary calculation drills after you can do the common cases and verify with a calculator. [R5, R7]

### 8.5 Health scripts: define what success means

You already have Python familiarity. Do not repeat a general Python course. Write the smallest tool that meets these requirements:

| Requirement | Test it with |
|---|---|
| URL is configurable; no embedded credentials | Change the lab port without editing source |
| A timeout prevents hanging | An intentionally non-responsive owned endpoint or a mocked timeout |
| Expected HTTP status and a small content marker are checked | A real page versus a 404 or a different service |
| Useful structured output includes outcome and timing | Both success and failure runs |
| Exit `0` for your defined healthy result, nonzero otherwise | A shell checking the exit code immediately |
| Errors are handled explicitly | Connection refused, HTTP error and malformed input |

`urllib.request` is sufficient. An HTTP error response can raise `HTTPError`; handle it deliberately rather than assuming every failed check is a missing network connection. Give `urlopen` an explicit timeout. If you measure elapsed duration, use an appropriate monotonic clock. [R8]

Start with one URL and one attempt. Add retries only after you can explain the trade-off: retrying can hide a transient error and increases total time. A health check never means “restart a real service automatically with no safeguards”.

**Proof:** run the check once while the lab service is available and once after a deliberate stop; show correct exit status and useful output. Then return an unexpected page from a listener and show that status alone is insufficient.

### 8.6 Backup: the restore is the evidence

Separate three things: **app source**, **service configuration**, and **your private browser workspace**. They need different recovery actions.

For ordinary static lab files: create an archive, list its contents, restore into a new directory, compare expected files/content, and serve the recovered copy on a test port. Keep the original intact while verifying. Record what was intentionally excluded.

For Pathcraft progress: export JSON; record its date; restore it in a disposable browser profile/origin before trusting the procedure. Check a note, a verified topic and a project check. Do not overwrite your only working copy just to run a test.

For a live database: copying the main file during writes may not produce the recovery state you expect. SQLite provides a backup API; other databases have their own consistent-backup procedures. In Pathcraft, `O09` currently links to a broad PostgreSQL resource; if you implement SQLite history for `O08/O09`, use Python’s SQLite backup documentation instead. The app itself has not been modified by this manual. [R9]

**Proof:** “I recovered the expected data and checked these things,” with evidence. An archive existing on the same failed disk is not a complete recovery plan.

### 8.7 Storage and resource incidents: learn without damaging your machine

Use `df -h` for filesystem byte usage, `df -i` for inode usage, and `du` for directory attribution. A filesystem can run out of inodes while bytes remain. A path may be on a different mount than you assume. Compare with `findmnt`/`lsblk` when available.

Do not simulate exhaustion by filling your main laptop’s root filesystem. Start with a supplied/synthetic incident description and inspect real read-only output. If a reviewer wants a live exhaustion drill, use a small separate disposable VM disk/filesystem with an explicit recovery plan.

For CPU/memory, observe a harmless workload and inspect processes. Do not diagnose from one load number alone or kill an unknown process because it looks busy.

**Proof:** identify the relevant mount and the resource under pressure, propose a narrow reversible action, then verify the service outcome. For a first support interview, sound observation and escalation are more valuable than pretending to know kernel internals. [R1]

### 8.8 SQL: understand which rows survive

For application-support roles, practise `SELECT`, `WHERE`, sorting, aggregates, `JOIN`, `LEFT JOIN` and `IS NULL` on synthetic users/tickets.

Example question: “Which users have no tickets?” A left join followed by a null check on the joined ticket identifier can express it. Explain why a filter on a right-hand table in `WHERE` may remove the unmatched rows you expected to keep.

**Proof:** predict the output on five hand-written rows, run the query, explain any mismatch. Use read-only queries, sample data and sensible result limits. Do not practise destructive statements on someone else’s database. Stop before query tuning and database administration unless the vacancy needs them. [R10]

### 8.9 Docker: locate the listener, files and process

**Model:** image = packaged starting point; container = an instance with its own runtime context. Keep four questions visible: what process starts, where it listens, how the host reaches it, where persistent data lives.

Build the supplied site first, then explain every Dockerfile instruction. In a mapping such as `127.0.0.1:8080:80`, 8080 belongs to the host and 80 to the container. Inside-container loopback is not another container or the host.

**Proof:** build a tag, start it on a local-only published port, inspect logs, stop and recreate it. Demonstrate which runtime changes vanish and what a deliberately mounted volume retains. A bind mount can hide files already present at that path in the image.

For Compose, connect services using their configured service names on the shared network. Do not hard-code temporary container IPs. Stop after you can rebuild and diagnose this one setup; park orchestration internals and Kubernetes. [R11]

### 8.10 AWS: keep identity, network and cost separate

Before creating anything, identify your account plan, allowed services, credit/billing model and resource-cleanup method. Current eligible new-customer Free plans differ from old “12 months free” tutorials: AWS documents a six-month-or-credit-exhaustion boundary. Your existing account may have different terms. Read your actual console and current documentation. [R12]

**Model:** IAM answers what a principal may do through AWS permissions. Routing and network rules answer whether traffic can reach a listener. Neither automatically fixes the other.

Practise one VM and its network boundary before load balancers or Kubernetes. Learn roles and temporary credentials, least privilege, MFA and narrow inbound access. A private IP is not generally reachable from your laptop over the public internet without a path. A running VM is not proof that its application listens correctly. [R13]

**Proof:** explain the entire request path, investigate one access issue, recover a controlled failure and list all created resources. Clean up the VM plus any volumes/snapshots, IPs, buckets and other resources you created. Stopping compute is not the same as removing every chargeable resource. Budget alerts are notifications, not spending caps. Avoid NAT gateways and paid GPU/cluster exercises on this route.

No cloud account or card available? Finish the Linux/VM demonstration and state that cloud work is conceptual/pending. Do not label a local simulation as hands-on AWS experience. Local support applications continue.

### 8.11 Git, CI and Terraform: make changes inspectable

**Git:** work on a branch; inspect `status` and `diff`; commit one meaningful change; review before pushing. For a shared history, understand a reverting commit before experimenting with history-rewriting commands. Demonstrate a reversible lab config change, not twenty memorised commands. [R14]

**CI:** the runner starts from an environment that does not automatically contain your laptop files, packages, secrets or current directory. Start with checkout and one relevant test. Find the first meaningful error in the failed step, reproduce it locally where possible, then change one thing. A green empty workflow does not demonstrate application testing. [R15]

**Terraform:** distinguish desired configuration, the plan, provider operations and state. Start with a low-risk local provider lab if suitable. Inspect the plan before applying and inspect what remains after destroying. State can contain sensitive data. Do not copy cloud credentials or commit state just to make a tutorial work. [R16]

These are extensions. A Terraform syntax issue must not stop you sending a Linux support application for which Terraform is irrelevant.

## 9. How to learn and retain

### The learning loop

1. **Predict:** before reading, state what you think will happen.
2. **Read just enough:** one relevant section, usually 5–15 minutes.
3. **Attempt:** perform the task while consulting syntax as needed.
4. **Verify:** compare output with the expected result.
5. **Vary:** change one condition and predict again.
6. **Retrieve later:** next session, try the main task before reopening your old notes.

Practice testing/retrieval and distributed practice have research support. They do not establish one perfect schedule for infrastructure learning. Use a practical starting cadence: repeat a small skill at the next session, a few days later, then about a week later. Shorten the interval for a skill you cannot retrieve. [Source L1](#learning-method-sources)

For a linked cluster such as Nginx → permissions → logs, a 60–90 minute lab may preserve useful context better than rigid 25-minute stops. Use short blocks to enter a difficult task or practise a narrow question. The task determines the block length.

### A 30-minute stuck protocol

| Elapsed effort | Move |
|---|---|
| First 5 minutes | Copy the exact error and state expected vs observed behavior. |
| Next 10 | Inspect the relevant log/config/command help; make one hypothesis. |
| Next 10 | Test one narrow change, or ask AI/a person for one hint using the evidence. |
| At about 30 | Choose a prerequisite repair or request a focused review. Save the exact blocker before switching to a useful fallback task. |

Do not repeat commands randomly for hours, but do not restart the course at the first error either. If the blocker is installation rather than the day’s concept, ask for help setting up the lab and continue a different ready task.

### AI as a tutor and reviewer

Use AI to shorten explanations, generate controlled variations and review reasoning. You may use generated code if you inspect, test and can maintain it. For the first attempt, ask for hints before a full replacement solution.

```text
EXPLANATION
Explain [concept] using this exact command/output. In 150 words or less,
give the mental model, one common wrong assumption and one prediction question.
Do not introduce additional tools.

DEBUGGING
Goal: [...]. Expected: [...]. Observed: [...]. Exact error/output: [...].
Environment and versions: [...]. Changes already tried: [...].
Give one next diagnostic step and what each possible result would mean.

REVIEW
Here is my script/config and the tests I ran. Find correctness, security
and failure-handling problems. Prioritise the three most important.
Do not rewrite everything. Ask me to explain any unclear decision.

MOCK INTERVIEW
Give me one fresher Linux/application-support scenario. Reveal evidence
only as I request a relevant observation. Do not reveal the cause early.
Afterwards assess my reasoning, safety, verification and communication.
```

Do not paste credentials, private recruiter messages or customer data. Check version-sensitive advice against the linked official source. In an assessment, follow the employer’s rules about AI and outside help. Practise some interviews without AI so a tool outage cannot remove your ability to reason.

### Listening time has a smaller job

While cooking or walking, explain aloud one incident or mentally trace a browser request. You can replay your own two-minute project explanation. Stop when another task needs attention. Listening supports familiarity; it does not verify a command-line skill. You do not need technology running in your mind all day to retain progress.

Your dual-monitor setup can help: task/docs on one screen, terminal on the other. Close the feed and AI-conversation panels when they are not serving the task. More open panels are not inherently more productive.

## 10. The resource shelf

**Pin only the resource needed for the current task.** This is a shelf to consult, not a reading assignment. Use the official source for exact syntax; ask AI to explain a short relevant passage when it is dense. If reading has consumed most of a work session, switch to a small attempt.

Time boxes below mean the initial relevant reading, not total mastery. If a link moves, search its title on the same publisher’s site; do not start another full course.

| Ref | Resource and exact use | First reading limit / finish with |
|---|---|---|
| R1 | [Linux Upskill Challenge](https://linuxupskillchallenge.org/). Use the navigation for files/text, services, networking, users/groups, permissions, transfer and archives as needed. [Local server option](https://linuxupskillchallenge.org/00-Local-Server/). | 10–20 minutes per matching lesson, then the Pathcraft task. You do not need to follow its calendar or publish a server to the internet for this manual’s initial local practice. |
| R2 | [Ubuntu user management](https://ubuntu.com/server/docs/how-to/security/user-management/) and the local `man chmod`, `man chown`, `man namei`. Consult only the command/permission behavior you need. | 10 minutes, then diagnose a lab user’s access. Avoid changing your everyday account’s groups just to experiment. |
| R3 | [systemd.service](https://www.freedesktop.org/software/systemd/man/latest/systemd.service.html). Find `ExecStart`, `Type` and `Restart`; use your installed system’s manuals for version-specific behavior. | 10 minutes, then annotate your small unit. Do not read all configuration directives. |
| R4 | [NGINX Beginner’s Guide](https://nginx.org/en/docs/beginners_guide.html). Read configuration structure, serving static content and reload. Simple proxy section only for the later proxy task. | 15 minutes, then serve the supplied page and find its logs. Ignore FastCGI initially. |
| R5 | [Ubuntu networking explanation](https://documentation.ubuntu.com/server/explanation/networking/) plus `ip route`, `ss` and resolver documentation on your lab system. | Read for one request path, then draw and test it. Do not read every network configuration guide. |
| R6 | [curl manual](https://curl.se/docs/manpage.html) and [MDN HTTP status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status). Find `--max-time`, `--resolve`, `--fail`, `--verbose`; look up observed status codes. | 5–10 minutes, then distinguish a transport error from an HTTP response. |
| R7 | [AWS subnet CIDR blocks](https://docs.aws.amazon.com/vpc/latest/userguide/subnet-sizing.html). Use the small subnet example; follow IPv4 details when checking AWS reservations. | 10 minutes, then do `/24`, `/25` and `/26` examples without guessing usable counts. |
| R8 | [Python urllib.request](https://docs.python.org/3/library/urllib.request.html) and [urllib.error](https://docs.python.org/3/library/urllib.error.html). Find `urlopen`, timeout and `HTTPError` / `URLError`. | 10–15 minutes, then test the health-check acceptance cases. No HTTP framework required. |
| R9 | [Python sqlite3](https://docs.python.org/3/library/sqlite3.html). Find `Connection.backup`; relevant only if your lab adds SQLite history. | Read the backup example, then verify restored synthetic rows. Skip database additions for the basic support release. |
| R10 | [SQLBolt](https://sqlbolt.com/). Work the interactive sections on selection, filtering, joins, NULL and aggregates. | One or two exercises, then reproduce a small support query using your own rows. Stop after you can explain the result. |
| R11 | [Docker: build and share an application](https://docs.docker.com/get-started/tutorials/run-an-app/) and [Docker concepts](https://docs.docker.com/get-started/docker-concepts/). Use the run, build, ports, storage and Compose sections for the selected extension. | 15–20 minutes, then operate your own site container. One image, not a collection of tutorial apps. |
| R12 | [AWS account plans](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/free-tier-plans.html) and [EC2 guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html). Read current account boundaries before a VM exercise. | One account/cost check, then one controlled VM lifecycle. Skip a paid course until the actual need is clear. |
| R13 | [AWS IAM best practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html), then the precise role/permission page you need. | Understand temporary credentials, MFA and least privilege; apply a bounded lab example. |
| R14 | [Pro Git](https://git-scm.com/book/en/v2); [Undoing Things](https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things). Read the matching basics/remotes/branch section, not the full book. | 10–15 minutes, then inspect, commit, push and reverse a harmless lab change. |
| R15 | [GitHub Actions quickstart](https://docs.github.com/en/actions/get-started/quickstart). Then inspect your actual workflow’s trigger, job, runner, steps and permissions. | One starter workflow, followed by one meaningful failing/passing check. It is not an entire DevOps course. |
| R16 | [Terraform tutorials](https://developer.hashicorp.com/terraform/tutorials). Choose one beginner provider path compatible with an owned low-risk lab. | `init` → inspect plan → apply → inspect state/change → destroy. No modules or multi-cloud tutorial tour. |
| R17 | [Cloudflare Static Assets](https://developers.cloudflare.com/workers/static-assets/get-started/) and [billing/limits](https://developers.cloudflare.com/workers/static-assets/billing-and-limitations/). Optional website hosting; use the source package’s README and configuration. | One setup session. Export your workspace before moving origins. Hosting and database backup are separate. |

### When a resource is failing you

If ten focused minutes leave a basic concept opaque, do not force another hour. Ask for one smaller example, inspect command help, or use the other official reference already listed for that subject. If a source repeatedly fails after two attempts, replace **that source**, keeping the same task and proof. This is a local repair; it does not require a new roadmap.

If you need video, search the exact topic and publisher rather than “complete DevOps roadmap”. Choose a short matching explanation and stop when you can attempt the task. A video’s confident delivery is not evidence that its cloud pricing or security instructions are current.

## 11. The interview gate

Use this to test whether your support demonstration is coherent. It is a personal readiness check, **not an employer’s universal standard**. Do not delay eligible trainee applications while waiting to pass it.

Allow about 60–90 minutes. Documentation is allowed. For a useful rehearsal, ask the reviewer to withhold the cause, give you time to think and require verification after a fix.

| Check | What a pass looks like |
|---|---|
| Service fault | Locate the relevant process/unit/listener, collect logs, identify the cause and verify the intended response. |
| Connectivity fault | Separate name lookup, connection and HTTP behavior; name the next untested boundary. |
| Permission/storage scenario | Inspect the relevant user/path/mount and propose a narrow fix or sensible escalation. No blanket permission changes. |
| Recovery | Restore expected lab content to a separate location and demonstrate that it works. |
| Script explanation | Explain inputs, timeout, success definition, output and failure exit code. Modify one condition. |
| Communication | Give a two-minute project explanation and a short incident handover with evidence and remaining uncertainty. |

Pass means you can perform the reasoning and demonstrate the result, not recite a memorised sequence. If you need to look up a flag, do so. If you cannot explain the principle, mark the affected topic Practising/Revisit and repair it.

You should not claim independent support readiness while you expose credentials, make destructive guesses, cannot distinguish the tested machine or report recovery without verifying it. Those require repair. Less critical syntax gaps can improve while you apply.

### Twelve interview questions worth rehearsing

| Question | What your answer must contain |
|---|---|
| “The website is down. What do you do?” | Confirm impact and expected behavior; gather request, listener and log evidence; isolate; make a controlled change; verify; communicate. |
| “The service says active. Why might users still fail?” | Wrong bind/port, path, network boundary, proxy, application behavior; active process alone is insufficient. |
| “What is a port?” | An endpoint selector for transport/application communication; distinguish a listener from a connection. |
| “A file is 644. Why can Nginx still fail?” | Worker identity, parent traversal, correct path/config, and possible ACL/security-policy factors. |
| “DNS fails. How would you isolate it?” | Observe lookup, compare a controlled destination request, preserve Host/TLS naming, and avoid pretending a bypass repairs DNS. |
| “Start versus enable?” | Current execution versus configured startup behavior; describe how you would verify both. |
| “Disk full but du looks small?” | Check the right mount, byte/inode usage, permissions and deleted-but-open file possibilities; avoid deleting blindly. |
| “What makes a backup trustworthy?” | Successful restore, expected data, recovery location, access and an understood retention/failure model. |
| “How do you handle something you do not know?” | Say what is known, gather evidence, consult docs, propose a safe next test and escalate with useful context. |
| “Why this role with an online degree?” | Your actual availability, exam constraints, relevant demonstrated work and willingness to learn the employer’s systems. |
| “Why a gap after school?” | Accurate brief history, current online study and current lab evidence; no invented employment or self-insult. |
| “What did you personally build?” | Separate the supplied UI from your operations scripts/configuration/tests; state how AI helped if asked; demonstrate ownership of the result. |

Practise spoken English for ten minutes using real incidents. Aim for clear sequence and accurate observations. Accent polishing and elaborate vocabulary are unnecessary side projects.

## 12. Make your work easy to assess

### A one-page résumé

Order it for a fresher: contact/links → two-line target summary → demonstrated skills → one lab project with evidence → accurate education → relevant additional experience if any.

Example summary, after the lab exists:

```text
IIT Madras BS student seeking a Linux/application-support trainee role.
Hands-on personal lab in Linux services, HTTP troubleshooting, Python
health checks and verified backup recovery. Open to [actual locations/shifts].
```

Include only skills you can discuss at the claimed depth. Keep a Linux-support version and a small application-support variation emphasising SQL/API diagnosis. You do not need ten completely different résumés. Use the employer’s terminology where it matches actual work; do not stuff keywords from tools you have never used.

Label the project **Personal infrastructure lab**. Label paid employment only when it really happened. Do not list the lab as client experience or claim you authored the supplied frontend. A working demonstration is enough to establish your practical contribution.

### The two-minute demonstration

1. **20 seconds:** what runs, where it runs and what you contributed.
2. **30 seconds:** the request path and health evidence.
3. **45 seconds:** one incident, your observations, fix and verification.
4. **25 seconds:** recovery procedure and one limitation.

Record once with readable terminal text. If the recording is understandable, publish/share a sanitised version and move on. Do not spend a day editing transitions or branding.

### Two short templates

Use these as starting points. Send only through a legitimate listed channel; no messages have been sent for you.

**Application / recruiter note:**

```text
Hello [name], I am applying for [exact role / job ID]. I am pursuing the
IIT Madras online BS and am currently at diploma level. I have built an
operations lab covering [two relevant things], with a short demo here: [link].
I can work [actual availability] and relocate to [actual options].
Does this opening accept candidates currently pursuing their degree?
Résumé: [link/attachment]. Thank you, Mohit.
```

**A focused request to a friend/engineer:**

```text
I am looking for paid Linux/application-support trainee roles. Here is my
one-page résumé and a two-minute lab demo. Could you tell me whether your
team hires current degree students, or point me to an appropriate opening?
No problem if there is no fit.
```

Ask Ashwin to critique the demonstration or introduce you where he genuinely knows the team. Do not assume his technical background or contacts guarantee a referral. Avoid sending a long account of your life or urgency to a stranger.

## 13. Run the job search like an operational queue

### Start with actual vacancies

During the first week, examine **ten recent, relevant listings** and record: role, employer, official URL, experience, education, location, shift, top repeated skills and whether pay is disclosed. Ten is a practical sample, not market research establishing all of India’s hiring demand.

Use official company career pages to verify listings. Discovery channels can include LinkedIn Jobs, Naukri, Indeed and Wellfound, plus IITM contacts and credible local employers. Set searches for the lanes in section 2; use fresher/trainee/0–1 or 0–2 year filters. Do not restrict yourself to remote roles if relocation is genuinely possible, but screen location and cost before committing.

Search phrases to adapt:

```text
Linux support trainee / Linux administrator fresher
Application support trainee SQL Linux
Technical support engineer API Linux fresher
NOC engineer trainee / infrastructure operations trainee
Cloud operations intern / cloud support trainee
DevOps intern paid / junior DevOps Linux Docker
```

For each good match, verify the application route on the company’s own domain when possible. Check publication/closing dates and whether the form is still accepting applicants. An old page remaining online is not proof of an active vacancy.

### The working application rhythm

- Aim initially for **15–25 eligible, reasonably matched applications per normal week**, with fewer during major exams. This is a workload target, not a guaranteed response formula.
- Give each application enough attention to confirm eligibility and match two demonstrated requirements. Reuse your core résumé.
- Add a small number of specific human contacts/referral requests; five thoughtful requests in a week can be more manageable than hundreds of generic messages.
- Record the submission immediately in Pathcraft. The next action is often “check reply on [date]”, not “refresh inbox all day”.
- When appropriate, make one polite follow-up after roughly five to seven working days. Respect explicit hiring instructions and do not keep chasing a closed role.

Use Pathcraft’s stages: **Saved → Applied → Interview → Offer / Closed**. In notes, record eligibility, pay uncertainty, the two matching proofs and any promised next step. Its follow-up date does not create a notification; use your daily queue review or a normal calendar reminder.

### A useful incident report doubles as interview evidence

```text
Title: clear symptom and affected lab service
Impact / scope: who or what failed; this was a controlled lab
Time and environment: enough to reproduce
Observations: commands and relevant results
Hypothesis: what the observations suggested
Action: one explained change
Verification: request/data checks after the change
Follow-up: prevent recurrence, improve alerting or document a limitation
```

Write three strong reports before collecting twenty screenshots. Include at least one wrong hypothesis you ruled out with evidence. It shows reasoning rather than a memorised success path.

## 14. Diagnose the hiring funnel

Review once a week for 30–45 minutes. The point is to identify a bottleneck, not judge your character.

| What happened | Investigate | Next experiment |
|---|---|---|
| Almost no eligible vacancies | Mandatory completed degrees, geography, unrealistic title filter, stale listings | Broaden adjacent technical-support lanes and locations; ask directly about current students. |
| Applications but no screens | Eligibility, résumé clarity, broken evidence link, targeting, normal delay | Have a human review three real applications; revise one weak element and try another matched batch. |
| Screens end after education/availability | Qualification or shift mismatch | Put accurate status earlier; target employers accepting it. Do not study Kubernetes to fix eligibility. |
| Technical rounds expose the same gap | A concrete missing skill or inability to explain | Repair it using a lab variation and repeat a mock before the next round. |
| Knowledge is present but answers are unclear | Too much detail, weak sequencing or pressure | Rehearse a two-minute incident with evidence and a concise conclusion. |
| Good interviews but no offer | Competition, a missing requirement, salary/shift fit, timing | Ask for feedback where appropriate, keep other applications moving and change only evidence-supported gaps. |
| Only unpaid / fee-based “internships” respond | Discovery channels and programme-versus-job confusion | Search actual payroll/paid trainee roles; validate employer and compensation before proceeding. |

After roughly **30 eligible applications and at least ten working days**, a very low response rate is a reason to inspect the funnel. It is not proof that you are unemployable or that the entire career is wrong. Those numbers are a practical review trigger, not a labour-market benchmark. Some processes take longer.

### The weekly five numbers

```text
Independent practical demonstrations completed: ____
Eligible applications submitted: ____
Screens / interviews scheduled: ____
Repeated technical or eligibility blockers: ____
Days I returned and did a real task: ____ / planned ____
```

Also record the next week’s college deadlines and financial runway in ordinary language. Avoid measuring hours of content consumed, GitHub contribution squares or the number of AI chats as primary success metrics.

Choose **one repair and one market experiment** for the next week. Example: “Repeat DNS/HTTP diagnosis without AI; apply to product-support trainees accepting students.” Keep the project and the rest of the plan intact unless evidence demands a larger change.

If no suitable offer appears after four weeks, review this evidence with Ashwin or another working engineer. Continue what is working, change a demonstrated bottleneck and set the next two-week review. Do not buy another roadmap to escape discomfort.

## 15. Check the offer

“Good enough” means workable finances and conditions **plus useful technical growth**. A lower title with good supervision can be a stronger first step than a grand title with no training.

### Questions before accepting

| Area | Ask specifically |
|---|---|
| Fixed pay | “What is the fixed monthly take-home after deductions? What part is variable? What changes during probation?” |
| Training | “Is training paid? For how long? What exactly determines continuation or conversion?” |
| Actual work | “What tickets or systems would I handle in the first month? Is there investigation or only scripted routing?” |
| Supervision | “Who reviews junior changes and handles escalations? What happens if I cannot solve an incident?” |
| Hours | “What are the normal hours, roster, weekly offs and night/on-call expectations?” |
| Exams | “Can the listed compulsory exam dates be accommodated? What notice and leave process apply?” |
| Joining / relocation | “What is the reporting location and date? Is remote onboarding, relocation assistance or a joining advance available?” |
| Written conditions | “Please share the offer, probation, notice, training-repayment/bond terms and any required documents for review.” |

A phone-heavy product-support role can still be useful if you learn the product, diagnose real problems and have a route toward deeper work. Ask rather than assuming “voice” means no growth. Conversely, server access alone does not compensate for unsafe solo responsibility with no escalation path.

### Calculate your own pay floor

Use actual quotations for a safe room, commute and food in the offered city. This example is **only arithmetic, not a claim about current city prices or an entry-level salary**:

| Monthly item | Example only |
|---|---:|
| Rent / room | ₹7,000 |
| Utilities | ₹1,500 |
| Food | ₹5,000 |
| Transport | ₹1,500 |
| Phone / internet | ₹500 |
| College-cost provision | ₹1,000 |
| Contingency | ₹2,000 |
| **Example recurring total** | **₹18,500** |

Replace every number. Then separately calculate deposit, travel, setup and the gap until the first salary. A salary covering the monthly total does not automatically fund joining. Clarify salary dates. Do not assume CTC divided by twelve equals money available to spend.

If the offer cannot fund survival, negotiate, investigate a genuinely cheaper safe arrangement or keep searching. A local or paid remote technical role may be more viable than an unaffordable relocation. Do not borrow or move based only on an unverified promise.

### Distinguish a job from a paid training product

Verify the legal employer name, official communication channel, reporting person, office/location and written compensation. Ask to speak to the actual team when practical. Do not pay a stranger to reserve a job or surrender original certificates as security. A course or placement-training fee is a different transaction from an employer paying you; do not treat it as a guaranteed job.

If contract or repayment terms are unclear, get qualified independent advice before signing; this manual is not legal advice. Do not assume every bond is harmless or make legal conclusions from a recruiter’s explanation alone.

For a substantial take-home assignment, clarify scope, expected time, assessment criteria and whether it involves real customer work. Keep your exercise separate from any production access. A short assessment and unpaid ongoing operational work are different commitments.

If your funds are running out before a multi-week search is viable, say so to someone you trust and prioritise paid roles you can join sooner while keeping a smaller technical-preparation block. Do not conceal a cash deadline behind an indefinitely expanding syllabus.

**When you accept a suitable role:** obtain written joining details, settle the exam discussion, preserve your evidence and shift preparation toward that team’s actual tools. Keep some other applications active until joining is sufficiently certain; communicate honestly if you withdraw. This manual’s next milestone is successful joining and the first paid work, not immediately choosing another enormous roadmap.

## 16. Recovery and real-life obstacles

These are operating choices to test, not a claim that one document can solve every personal difficulty.

| Obstacle | A specific response |
|---|---|
| “I have the whole day, so I never start.” | Choose a first-start window and a fixed stop for the first task. Book a library/study-space visit if available; begin with the saved command, not a planning session. |
| “The 10×10 room makes every day blur.” | Move one work block to a safe library or quiet shared space several days a week. Keep the monitor at home for deeper lab work. Leave the room for an ordinary errand or walk even on non-gym days. |
| Phone / feeds | Put the phone outside arm’s reach before the first block. Use your existing focus controls if helpful. Schedule limited check windows; keep essential calls reachable. Do not spend the afternoon comparing blockers. |
| AI conversation replaces work | Open AI only with an error, a concept or a review request. After one useful answer, return to the terminal and produce evidence before another question. |
| “I want the perfect day.” | Pick one proof and one market action. A late first block still counts. Resume at the next available block without waiting for tomorrow. |
| “The task feels too difficult.” | Shrink it to one prediction and one observation. Ask for a small example or prerequisite repair, not a whole new explanation of Linux. |
| “I understand it immediately, so I skip practice.” | Change one input and explain the result. Intuition is useful; evidence determines your status. |
| Cooking and cleaning expand endlessly | Keep a short repeatable meal/cleanup routine and a basic daily reset. Batch suitable errands. Do not make skipping food, bathing or necessary cleaning the productivity strategy. |
| Gym or guitar takes the entire evening | Decide the session boundary beforehand. Keep useful recreation inside a finite window; reduce optional duration during a deadline instead of abandoning everything indefinitely. |
| College mathematics feels harder than tech | Put the hard problem-solving in a protected block. Write the exact failed step; get course-specific help. Easy infrastructure tasks must not become avoidance of required assignments. |
| One rejection ruins the day | Log the stage and any concrete feedback; complete the next small scheduled task. One outcome cannot diagnose your entire ability. |
| No human contact / accountability | Arrange two bounded technical reviews a week if a friend agrees; consider a local Linux/community event when accessible. You need a working relationship, not constant public performance. |

### The restart ladder

**Missed one block:** use the next block; no schedule rewrite.

**Missed one day:** read the saved next action and work for ten minutes. Keep existing evidence and ticks.

**Missed several days:** take 15 minutes to identify the last reliable proof, the next real deadline and the current blocker. Do one small reproduction, then resume. Do not clear your progress for a “fresh start”.

**The minimum day keeps failing:** ask Ashwin or another trusted person for a short check-in; change the work environment or reduce the task to an observable first step. If difficulties with everyday functioning persist, seek appropriate human support rather than answering with a more punishing schedule.

### A four-week review horizon

| Week | Main emphasis | The evidence to inspect |
|---|---|---|
| 1 | Re-entry routine, baseline, foundational lab and early eligible trainee applications | Working service, honest profile, first incident attempt and real application records |
| 2 | Support demonstration, recovery and clearer explanations | Interview gate attempts, three useful reports, targeted applications |
| 3 | Interviews and repairs; one justified extension | Repeated employer requirements, technical gaps and screen outcomes |
| 4 | Funnel correction, interviews and offer scrutiny | Eligible application quality, interview progress and financial viability |

These are review themes, not promises to learn everything or receive an offer within four weeks. Move faster when proof permits; allow more time when reality demands it. The schedule is adjustable. Returning, demonstrating and reaching the market are the commitments.

---

## Appendix A. Coverage map

**How to read this:** the “First application core” is a compact study index of **38 existing Level 1 topics**, including the dependency closure for the support checkpoint, basic web/SSH operations, communication and secret hygiene. It is not a prerequisite imposed by employers or a reason to defer trainee applications. The remaining **13 core Level 1 topics** stay in your queue and can move earlier for a specific role. Together they are Pathcraft’s 51 non-optional Level 1 checks.

The table is generated from the shipped curriculum so IDs and proof checks match the app. Read the individual topic for its dependencies. Existing knowledge counts when you can perform the proof; no full beginner course is necessary.

### First application core — 38 checks

| ID | Topic | Proof to demonstrate |
|---|---|---|
| `L01` | Paths and filesystem navigation | Explain an absolute and a relative path, then reach the same file with both. |
| `L02` | Safe file operations and inspection | Show the resulting tree and explain what was copied versus moved. |
| `L03` | Text inspection, grep and basic patterns | Extract only matching lines and explain why they matched. |
| `L05` | Archives, compression and links | Compare file contents after restore and explain what happens when a link target is renamed. |
| `L06` | Users, groups and sudo | Explain your effective identity and when elevation is needed. |
| `L07` | Ownership, rwx permissions and umask | Explain the fix without using chmod 777. |
| `L08` | Processes, signals and exit codes | Distinguish a process, a shell job and an exit status. |
| `L09` | Packages and trusted repositories | Show its version, package origin and removal command. |
| `L10` | systemd service lifecycle | Explain active versus enabled and find the service's unit definition. |
| `L12` | journalctl and service failure evidence | Point to the log entry that explains the failure and verify recovery. |
| `L14` | Disk capacity and inode exhaustion | Explain why df and du can report different totals. |
| `L16` | Environment variables and shell configuration | Show the difference between shell-local and exported configuration. |
| `N01` | Addresses, localhost and listening ports | Explain why localhost inside a container may not mean your laptop. |
| `N02` | TCP, UDP and connection establishment | Explain what a successful TCP connection does not prove about the app. |
| `N03` | CIDR, private addresses and default routes | Decide whether two example addresses share that subnet. |
| `N04` | DNS resolution and caching | Distinguish a resolution failure from a connection failure. |
| `N05` | HTTP requests, responses and status codes | Explain the three outcomes using the request path. |
| `N06` | Listening sockets and reachability | Match the listener to its process and diagnose a failed connection. |
| `N07` | SSH keys and host identity | Explain public versus private keys and why a changed host key needs investigation. |
| `N08` | Firewalls and narrow inbound access | Explain why opening a port cannot fix an application that is not listening. |
| `N09` | A layered connectivity diagnosis | Identify the failing layer and verify only the necessary fix. |
| `N11` | Nginx static serving and configuration | Request the page and identify the configuration that selected it. |
| `N12` | Access logs, error logs and 4xx/5xx | Match a timestamped request to its evidence. |
| `G01` | Git status, diff and commits | Explain working tree, index and commit using your repository. |
| `G02` | Ignore rules and credential hygiene | Show ignored files and explain the response to an exposed credential. |
| `G03` | Remotes, push and pull | Show the same commit identifier in both locations. |
| `G04` | Branches, merges and safe revert | Show the resulting history and restored content. |
| `C03` | Python environments and configuration | Recreate the environment and change the setting without editing code. |
| `C04` | HTTP health script with timeout | Stop the lab service and show a bounded, clear failure. |
| `O01` | Evidence-first troubleshooting | Another person can follow the evidence to the same cause. |
| `O02` | Support tickets and severity | A reviewer can identify the next action without asking for basic context. |
| `O03` | Backup and verified restore | Demonstrate recovered files and explain the recovery limitation. |
| `O04` | Escalation, runbooks and shift handover | State when the operator should stop and escalate. |
| `O05` | Disk and permission incident drill | Identify the cause and verify the minimal repair. |
| `S01` | Least privilege and secret handling | Explain one removed permission and one protected credential boundary. |
| `J01` | Honest résumé and role targeting | Each technical claim links to work you can explain. |
| `J02` | README and a two-minute project explanation | Someone else can locate setup steps and understand your contribution. |
| `J03` | Applications and follow-up practice | Tailor one application using honest evidence and a viable relocation budget. |

### Continue while applying — 13 checks

| ID | Topic | Proof to demonstrate |
|---|---|---|
| `L04` | Pipes, redirection and standard error | Demonstrate that errors and normal output went to the intended destinations. |
| `L11` | A custom systemd unit | Start it successfully and show which user and working directory it uses. |
| `L13` | CPU, memory and load inspection | Explain one measurement and one conclusion it cannot support alone. |
| `L15` | Block devices, filesystems and mounts | Trace one mounted path to its backing device and filesystem. |
| `L17` | cron and systemd timers | Show the execution evidence and explain how you would prevent overlapping runs. |
| `N10` | TLS certificates and name matching | Explain a name mismatch versus an expired certificate. |
| `C01` | Bash arguments, quoting and conditions | Run it with spaces in the path and show its failure status for invalid input. |
| `C02` | Loops and safe command composition | Handle a filename with spaces without splitting it incorrectly. |
| `C05` | JSON, YAML and structured data | Explain a string versus a number and fix one malformed example. |
| `C06` | Logging and exception handling | Show useful failure evidence with no credentials in output. |
| `C07` | SQL SELECT, filters, ordering and NULL | Explain why equality with NULL is not the right test. |
| `C08` | SQL joins and safe support queries | Explain the join key and why the row count changed. |
| `S02` | Patching and suspicious-access triage | Explain how to preserve evidence and confirm service health after patching. |


## Appendix B. Reusable working pages

### Daily record — under five minutes

```text
Date:
Mode: Normal / Exam / Minimum
Main proof and Pathcraft ID:
What I observed:
Evidence location:
Market action and outcome:
Next start: when, where, first command / question:
```

### Weekly review — 30–45 minutes

```text
Demonstrations I can now perform:
Applications / screens / interviews / offers:
Most repeated hiring blocker:
One technical repair for next week:
One market experiment for next week:
Actual college deadlines and capacity:
Next week’s specific start cue:
Backup exported and located:
One thing I will deliberately keep parked:
```

### Ask Ashwin for a bounded review

```text
Could we do a 20-minute review twice this week, if you have time?
One call: give me a small fault in my disposable lab and watch my reasoning.
Other call: review my two-minute demo and three actual applications.
I will prepare the environment and send one short evidence link.
I need specific feedback, not another roadmap.
```

## Sources and maintenance notes

This guide combines the shipped Pathcraft curriculum, official technical documentation and a small current sample of employer/programme pages. **Source check: 4 November 2026.** Listings can close, programme rules can change and your eligibility must be confirmed directly. These examples do not establish a salary distribution or guarantee that an employer accepts your status.

### Job and programme sources

- **J1 — [Zoho technical-support listing](https://careers.zohocorp.com/jobs/Careers/193779000024445975).** Used to check actual support duties, communication and shift expectations. Degree eligibility and present availability still need confirmation.
- **J2 — [HashRoot careers](https://hashroot.com/careers).** Used to compare a DevOps listing’s experience/stack expectations with the proposed entry path. This is not a recommendation to apply to every listed experienced role.
- **J3 — [IITM study placement portal](https://placements.study.iitm.ac.in/).** Current FAQ describes diploma/BSc thresholds and programme training/assessment steps.
- **J4 — [IITM programme placements/internships page](https://study.iitm.ac.in/ds/placements/students.html).** Describes diploma-stage/exit routes that should be reconciled with current portal guidance by the programme team.
- **J5 — [Bobcares application page](https://bobcares.com/apply/).** An example of an explicit academic eligibility note; do not assume a generic “fresher” search overrides an employer’s stated criteria. No assumption is made here that you qualify.

### Learning-method sources

- **L1 — [John Dunlosky, “Strengthening the Student Toolbox”](https://www.aft.org/ae/fall2013/dunlosky).** Author’s account of practice testing and distributed practice. Used for the retrieval/revisit approach; the specific working intervals in this manual are adjustable choices.
- **L2 — [Gollwitzer and Sheeran, implementation intentions](https://www.socmot.uni-konstanz.de/publications/implementation-intentions-health-behavior-constructs-theory-measurement-and-research).** Used for situation-linked if–then plans. The findings do not promise a particular person will stop procrastinating or obtain a job.

The numbered **R** links in section 10 are the technical references. Some are broad manuals; the table names the small section or lookup to use. The guide does not claim every resource can be mastered in thirty minutes. Command examples were reviewed for scope, but your own OS, configuration and provider terms still determine behavior. Perform mutation and failure drills in your disposable lab, then verify the result.

**Completion of this manual’s agenda:** you have joined a paid, financially workable technical role with understood duties, supervision and exam arrangements. Until then, the next move is chosen from your last proof and your real hiring feedback. Keep the same working system; change what the evidence says needs changing.

