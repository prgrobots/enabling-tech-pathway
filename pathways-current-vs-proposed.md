# Robotics & Automation Pathways — Current vs Proposed
**To:** [Director's name] · **From:** [Your name]

## Current published pathway (NMTAFE Robotics & Automation map, Dec 2025)

```mermaid
flowchart TD
    I1[Cert II Integrated Technologies<br/>Robotics Control Stream · 22586VIC]
    I2[Cert II Autonomous Workplace<br/>Operations · RII21222]

    S1[PLC-Based Industrial<br/>Robotics Skill Set]
    S2[Industrial Robotics &<br/>IoT Coding Skill Set]
    S3[ICT30120 Cert III<br/>Information Technology]
    S4[Cert III Engineering<br/>Apprenticeship]

    C1[Cert IV: General Robotics,<br/>Mechatronics & Automation<br/>22697VIC CIV Robotics]
    C2[Cert IV: Instrumentation<br/>Control & Automation]
    C3[Cert IV: Robotics<br/>Software Engineering]
    C4[Cert IV: Advanced Industrial<br/>Manufacturing]

    M[Micro-learning:<br/>Intro Cyber Security · CAD & 3D Printing<br/>AI Skill Set · Drones]

    I1 --> S1 --> C1
    I2 --> S2 --> C1
    S3 --> C3
    S4 --> C4
```

**The gap:** micro-learning skill sets exist (cyber, CAD/3D printing, AI), but there's no dedicated Cert III on-ramp for IoT/electronics-curious students who aren't ready to commit to Robotics or straight ICT30120 — they either jump into ICT30120 cold or don't enter at all. That's a chunk of interested school leavers with nowhere obvious to land.

## Proposed: Enabling Technologies on-ramp

```mermaid
flowchart TD
    T1[3D Printing Taster<br/>free/short]
    T2[Electronics Basics<br/>Taster · free/short]

    S1[3D Printing Skill Set]
    S2[IoT / Arduino Skill Set<br/>ESP32]
    S3[Cyber Security Skill Set]

    C3[22588VIC Cert III<br/>Enabling Technologies]
    D3[Dual Cert III<br/>+ ICT30120]
    CIVR[Existing Cert IV<br/>Robotics pathway<br/>22697VIC CIV Robotics]

    T1 --> S1 --> C3
    T2 --> S2 --> C3
    S3 --> C3
    C3 --> D3
    C3 --> CIVR
```

**The fix:** the same skill-set → Cert III model already proven in the published Robotics map, extended one lane over. It fills the gap without inventing a new structure — it feeds the existing Cert IV Robotics pathway rather than competing with it, and avoids the Electrotechnology-stream CIV's UEE exposure entirely by routing through 22588VIC instead.

**Next:** I'll bring real enrolment/SCH numbers once pulled — see separate quick brief.
