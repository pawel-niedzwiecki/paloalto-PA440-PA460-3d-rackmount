# 🛠️ Cost-Effective 3D Printed 19" Rack Mount for Palo Alto PA-440 / PA-460

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CAD: FreeCAD](https://img.shields.io/badge/CAD-FreeCAD-blue.svg)](https://www.freecad.org/)

**Open Source Hardware | Cost Optimization | Ready for Production**

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Repository Structure](#️-repository-structure)
- [Technical Specifications](#-technical-specifications)
- [Installation Guide](#-installation-guide)
- [Printing Guidelines](#-printing-guidelines)
- [Gallery](#-gallery)
- [License](#-license)
- [Author](#-author)
- [Acknowledgment](#-acknowledgment)

---

## 💡 Overview

This repository provides complete design files for a **custom 3D-printable 1U 19" rack mount** solution for **Palo Alto Networks PA-440 and PA-460** next-generation firewalls.

### The Problem
Commercial rack mount kits for these devices cost **$170+ USD (700+ PLN)**, creating an unnecessary budget burden for SMB deployments and home labs.

### The Solution
This open-source design reduces the cost to just the price of filament (~$5-10 USD), demonstrating practical engineering and cost optimization skills valuable in modern IT infrastructure management.

---

## 🎯 Key Features

- **💰 95%+ Cost Reduction** - From $170+ to under $10 in materials
- **📐 Precision Engineering** - Custom-fitted dimensions for PA-440/PA-460
- **🔓 Commercial Use Permitted** - MIT License allows selling printed units
- **📁 Complete File Set** - Editable FreeCAD sources (.FCStd) + print-ready STL files
- **🏭 Production Ready** - Tested design with installation instructions
- **🌍 Open Source** - Contribute improvements back to the community

---

## 🗂️ Repository Structure

```
.
├── LICENSE                 # MIT License
├── README.md              # This file
├── src/                   # FreeCAD source files (.FCStd)
│   └── PA440_rack_mount.FCStd
├── stl/                   # Print-ready STL files
│   ├── left_ear.stl
│   └── right_ear.stl
└── images/                # Documentation photos
    ├── installed_unit.jpg
    ├── freecad_preview.png
    └── screw_recess_detail.jpg
```

---

## ⚙️ Technical Specifications

### Compatibility
- **Supported Models:** Palo Alto Networks PA-440, PA-460
- **Rack Standard:** 19" (482.6mm) standard rack
- **Rack Units:** 1U height

### Design Details
- **CAD Software:** FreeCAD v0.21+ (fully parametric design)
- **File Formats:**
    - Source: `.FCStd` (editable)
    - Export: `.STL` (print-ready mesh)

### Hardware Requirements
- **Mounting Screws:** M4×16mm (4 pieces required)
- **Rack Screws:** M6 or 12-24 cage nuts (standard rack hardware)

### Recommended Print Settings
- **Material:** PETG (recommended) or ABS
    - ❌ **Not recommended:** PLA (insufficient heat resistance)
- **Layer Height:** 0.2mm - 0.3mm
- **Infill:** 30-50%
- **Supports:** Not required
- **Print Time:** ~6-8 hours total (both ears)

---

## 🚀 Installation Guide

### Step 1: Print the Components
1. Slice both STL files with recommended settings above
2. Print both left and right ear pieces
3. Remove any support material if used

### Step 2: ⚠️ **CRITICAL - Create Screw Head Recesses**

This step is **mandatory** to prevent installation issues:

**Why this is necessary:**  
Standard M4 screw heads protrude above the mounting surface, blocking the firewall from sliding into the rack frame.

**Process:**
1. **Materials needed:**
    - 1× spare M4 screw
    - Heat source (lighter or heat gun)
    - Pliers or tweezers
    - Fire-safe surface

2. **Procedure:**
    - Hold the spare M4 screw with pliers
    - Heat the screw head for 5-10 seconds
    - Press the hot screw head into each mounting hole
    - The plastic will melt slightly, creating a perfect recess
    - Repeat for all 4 mounting holes (2 per ear)
    - Allow to cool completely

3. **Quality check:**
    - Screw head must be **flush or recessed** below surface
    - Test fit with actual M4×16 screw before mounting device

**⚠️ Warning:** Skipping this step will prevent proper installation.

### Step 3: Mount the Firewall
1. Attach 3D-printed ears to PA-440/PA-460 using M4×16 screws
2. Ensure all screws are securely tightened
3. Verify screw heads are fully recessed

### Step 4: Rack Installation
1. Slide the mounted unit into your 19" rack
2. Secure with standard M6 or 12-24 rack screws
3. Verify proper alignment and stability

---

## 🖨️ Printing Guidelines

### Material Selection

| Material | Heat Resistance | Durability | Recommended |
|----------|----------------|------------|-------------|
| **PETG** | Excellent (80°C+) | Very Good | ✅ **Yes** |
| **ABS** | Excellent (100°C+) | Excellent | ✅ Yes |
| **PLA** | Poor (50-60°C) | Good | ❌ **No** |

**Recommendation:** Use **PETG** for optimal balance of strength, heat resistance, and ease of printing.

### Troubleshooting

**Issue:** Screw heads still protruding after recessing  
**Solution:** Reheat and press deeper, or use a countersink bit

**Issue:** Parts warping during print  
**Solution:** Use enclosure, increase bed adhesion, switch to PETG

**Issue:** Weak layer adhesion  
**Solution:** Increase nozzle temperature by 5-10°C, reduce fan speed

---

## 📸 Gallery

*Images showing the design, printing process, and final installation*

| Preview | Description |
|---------|-------------|
| ![Installed Unit](./images/installed_unit.jpg) | PA-440 mounted in production rack |
| ![FreeCAD Design](./images/freecad_preview.png) | Parametric design in FreeCAD |
| ![Screw Detail](./images/screw_recess_detail.jpg) | Proper screw head recess detail |

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means:
- ✅ **Commercial use allowed** - You can sell printed units
- ✅ **Modification allowed** - Adapt the design to your needs
- ✅ **Distribution allowed** - Share with others freely
- ✅ **Private use allowed** - Use in your infrastructure
- ℹ️ **Liability** - No warranty provided (use at your own risk)

---

## 👨‍💻 Author

**Paweł Niedźwiecki**  
*Server Administrator | SysOps Engineer | Developer*

This project demonstrates the intersection of **Systems Administration, Engineering Design, and Cost Optimization** - core competencies for modern infrastructure management.

### Connect
- 💼 **LinkedIn:** [linkedin.com/in/pawel-niedzwiecki](https://www.linkedin.com/in/pawel-niedzwiecki/)
- 🌐 **Portfolio:** [uxu.pl](https://uxu.pl)

---

## 🙏 Acknowledgment

If this design saves you time and money (especially in commercial deployments), please consider:

- ⭐ **Starring this repository** on GitHub
- 🔗 **Linking back to [uxu.pl](https://uxu.pl)** in your documentation
- 💬 **Sharing your build** - Submit photos via Issues/PR
- 🤝 **Contributing improvements** - Fork and enhance the design

---

## 🔧 Contributing

Contributions are welcome! Please feel free to:
- Report issues or improvements
- Submit pull requests with design enhancements
- Share your successful builds

---

**Built with 🛠️ by infrastructure professionals, for infrastructure professionals.**