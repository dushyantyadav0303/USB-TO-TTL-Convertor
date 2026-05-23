# Contributing to Watermelon USBHUB 

Thank you for your interest in contributing to Watermelon USBHUB! We welcome hardware enthusiasts, electronics engineers, and hobbyists to help improve our PCB designs, schematics, and documentation. 

This document outlines the guidelines for contributing to our hardware project.

---

## Table of Contents

1. [Prerequisites & Tools](#prerequisites--tools)
2. [Reporting Hardware Issues](#reporting-hardware-issues)
3. [Making Design Changes](#making-design-changes)
4. [Design Rules & Guidelines](#design-rules--guidelines)
5. [Pull Request Process](#pull-request-process)
6. [Bill of Materials (BOM) Updates](#bill-of-materials-bom-updates)

---

## Prerequisites & Tools

To view and modify the source files for this PCB, you will need the following Electronic Design Automation (EDA) software:

* **EDA Tool:** [e.g., KiCad v7.0.0 or later / Altium Designer / EasyEDA] Recommended: Easyeda
* **Libraries:** Make sure you have the required component libraries installed. [Link to custom libraries or specify if they are included in the repo].
* **Mechanical CAD (Optional):** [e.g., blender, Fusion360] if you are modifying the 3D models or enclosure.

---

## Reporting Hardware Issues

If you spot a problem with the design, please open an Issue on GitHub. Great hardware bug reports help us prevent costly manufacturing errors. 

When reporting an issue, please use the appropriate label and include:
* **Type of Issue:** (e.g., Schematic error, footprint mismatch, trace routing issue, component out-of-stock).
* **Reference Designator:** (e.g., "Resistor R12 footprint is too small").
* **Description:** What is wrong and what the expected result should be.
* **Screenshots:** Attach screenshots of the schematic, 2D PCB layout, or 3D viewer highlighting the problem.

---

## Making Design Changes

We follow a standard Git workflow for hardware files, but please be aware that merging binary EDA files can be difficult. 

1. **Fork the repository** and clone it locally.
2. **Create a new branch** for your specific fix or feature:
   ```bash
   git checkout -b hw-fix/update-usb-connector
