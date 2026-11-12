# Khomchan Wisesnakorn

Final-year Computer Engineering student at Khon Kaen University, graduating May 2027 and heading into graduate study and a career in HPC systems. I'm interested in the whole stack: schedulers, storage, monitoring, and the people who depend on them.

[khomchan.wi@kkumail.com](mailto:khomchan.wi@kkumail.com) · [LinkedIn](https://linkedin.com/in/khomchan-wisesnakorn) · Khon Kaen, Thailand

---

## Experience

### HPC Web Portal — Co-op project, Synchrotron Light Research Institute (SLRI)
*Jun – Oct 2026 · 17 weeks*

SLRI's cluster (22 nodes, ~200 cores, Torque 6.1.1 with Maui) was reachable only over SSH. I built and deployed a Next.js/TypeScript portal so researchers who don't use Linux can submit jobs, see whether each one succeeded and what it used, and manage files from a browser. It has been in service on an internal SLRI server since August 2026.

- **Identity vs. execution** — Microsoft Entra ID proves who the user is; a separate layer decides which Unix account each command runs as, so the scheduler still records every job's true owner.
- **HPC Gateway** — replaced per-user SSH passwords with a service account whose forced-command key reaches a single program, which drops to the user through narrow `sudo` rules.
- **Monitoring** — a collector reads cluster state and the Torque accounting log every 30 s. Queue limits are checked before submission, and administrators can see at a glance which nodes need attention.

### Engineering Intern — Electrical & Electronics Systems Division, SLRI
*Apr – Jun 2026 · 7 weeks*

Four devices across embedded, IoT and web:

- **PM2.5 air purifier** — PMS3003 → ESP32 → industrial HMI with relay-driven fan and filter, auto/manual modes, streaming to ThingSpeak and Supabase behind a Next.js dashboard. Taken from breadboard to a working machine.
- **Standalone PM reader** — all nine units delivered; enclosure designed in Fusion 360 and 3D-printed.
- **Supervisory-control design** for a heatstroke cooling machine, and a **tester for medical tourniquets** bound for border aid work.

---

## HPC training

- **LANTA HPC Experience Day 2026** (Aug 2026) — ThaiSC (NSTDA) with NARIT and Thammasat University, HPC Ignite Initiative. Hands-on with LANTA, Thailand's national supercomputer: Slurm (`sbatch`, job arrays, `sacct`), JupyterLab on compute nodes, OpenMP and MPI. Built two simulations swept as Slurm job arrays, toured NARIT's CHALAWAN cluster, and had 1:1 mentoring with Asst. Prof. Dr. Worawan Diaz Carballo.
- **HPC School Bangkok: Zero** (Aug 2026, inaugural cohort) — workload-shaped resource requests, job optimisation, and tuning AI/LLM training runs on HPC systems.
- **ANSCSE29** (Jul 2026) — 29th National Symposium on Computational Science and Engineering, co-hosted by SLRI.

---

## Skills

| Area | Tools |
|---|---|
| HPC & systems | PBS/Torque with Maui, Slurm, OpenMP, MPI, Ganglia, Linux, SSH, `sudo`, Docker |
| Languages | C/C++, Python, TypeScript/JavaScript, Bash, LaTeX |
| Web & data | Next.js, React, Node.js, PostgreSQL, MongoDB, REST APIs, Entra ID (OIDC) |
| Embedded | ESP32, Arduino, STM32, Modbus RTU, UART/I²C, industrial HMI, Fusion 360, 3D printing |

---

## Education

**B.Eng. Computer Engineering**, Khon Kaen University — expected May 2027 · GPAX 3.30
Coursework: Computer Architecture, Operating Systems, Data Structures, Microprocessor Design, Databases, Digital Signal Processing

---

## Earlier

- **CESCa 20th (2025)** — instructor for Digital Logic Design basics (logic gates, circuits, Karnaugh maps); the session was voted the most interesting subject by participants. General staff at CESCa 19th (2024).
- **Welcome KKU Freshmen 2024** (May 2024) — worked with the KKU Student Organization on the freshman registration and orientation platform, including activity-point tracking. Full-stack development and Thai/English translation with Next.js, Firebase, Redux and MUI.

---

## Certifications & languages

- MongoDB: Retrieval-Augmented Generation (2025)
- KKU Faculty of Engineering: Machine Learning for Engineering; Python Programming for Engineers (2023)
- Thai (native) · English — IELTS 5.5 (B2), EF SET 73/100 (C2)
