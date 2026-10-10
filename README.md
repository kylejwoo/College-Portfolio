# Kyle Woo – Engineering Portfolio

## About Me
I am a **Master of Science in Electrical Engineering (MSEE) candidate** at USC and a **Viterbi Fellow**, building on my strong foundation as a **magna cum laude graduate** with a B.S. in Electrical & Computer Engineering. I am also a recipient of the **USC Trustee Scholarship**, the university’s highest merit award.  

My academic and project experience focus on **PCB design, embedded systems, power electronics, and robotics**, with hands-on work in **custom circuit design, impedance matching, phase shifting, and real-time autonomous system integration**. I am passionate about leveraging hardware design and system-level engineering to solve challenges in **medical devices, autonomous vehicles, and next-generation computing hardware**.

## Projects
- [Autonomous Underwater Vehicle (AUV) – Custom PCB + Electrical Architecture](./AUV/README.md)  
- [Flexible MRI Coil Research – Impedance Matching & Phase Shifting](./Khan%20Lab%20MRI%20project/README.md)  
- [Drone Control with Vicon + ROS2](./SIA%20Drone%20Lab/README.md)  

## Software Engineering & Workflow Automation

### [CentralReach ESSC Bulk Payment Automation](https://github.com/kylejwoo/centralreach-ESSC-bulkapply-automation)
**Technologies:** Python, Playwright, Chromium, JSON, CSV

Built a browser automation workflow to match client billing appointments with electronic payment records and apply payments in CentralReach. The tool verifies client identity against appointment dates and amounts, cross-checks payment totals before submission, and tracks completed invoices to support repeatable processing. Designed for safe operation with dry-run mode by default, explicit commit mode, stop-on-uncertainty behavior, batch controls, and failure diagnostics.

### [CentralReach Patient Responsibility Automation](https://github.com/kylejwoo/centralreachPR-automation)
**Technologies:** Python, Playwright, Chromium, Logging

Developing a modular browser automation foundation for patient responsibility workflows in CentralReach. The published release (v0.2.0) implements a persistent browser profile for CentralReach and Outlook sessions, startup screenshots, daily logs, and diagnostic bundles that capture screenshots, HTML, traceback details, and browser state on failures. The current public release focuses on browser and login persistence rather than automated payment posting.

### [CentralReach Billing & Claims Automation](https://github.com/kylejwoo/CentralReach-Billing-Automation)
**Technologies:** Python, Playwright, Chromium, JSON

Developed a billing and claim-setup workflow for Kaiser and ESSC billing in CentralReach. The automation separates provider groups and Office/Telehealth workflows, verifies appointment counts, checks claim fields and payer-specific modifier rules, and prepares bulk-merge values for provider, facility, and billing details. Includes configurable provider mappings, a separate manual-work browser window, confirmation steps, and safeguards that pause processing when data requires review. Final claims generation remains a manual action.

## Skills
- **PCB Design Tools:** Altium Designer, KiCad  
- **Programming:** C, C++, Python, Embedded Systems (nRF, Teensy)  
- **Automation & Software:** Playwright, Chromium Browser Automation, JSON, CSV, Logging, Workflow Validation  
- **Electrical Engineering:** Circuit Design, Signal Integrity, Impedance Matching  
