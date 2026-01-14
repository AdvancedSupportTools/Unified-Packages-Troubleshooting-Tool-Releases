**🔔 Unified Package Troubleshooting Tool — Quick Overview**

⚠️ IMPORTANT: COMMUNITY TOOL - NOT AN OFFICIAL DISTECH CONTROLS PRODUCT

This application is a special project developed by the Distech Controls Advanced Support Team and is NOT a sanctioned or official release by Distech Controls. Please read the DISCLAIMER.txt before using this tool.

⚠️ Important Notice
THIS IS A COMMUNITY TOOL - READ BEFORE USE

This application is:

✅ Freely available for use and redistribution
✅ Built using only publicly available RESTful API endpoints
✅ Supported by Advanced Support at their discretion, primarily for Distech SI's, Distributors, OEMs, and partners
❌ NOT an official Distech Controls product
❌ NOT covered by Distech Controls warranties or support agreements
❌ NOT subject to standard Distech Controls release procedures
📋 READ THE FULL DISCLAIMER - Contains important legal information about warranty, liability, and support.

By using this tool, you acknowledge and accept these terms.

🔄 Semantic Versioning Adoption
Version Numbering: v6.17.399b → v1.0.1 → v1.0.7 → v1.0.8 → v1.0.9 → v1.0.10

We've transitioned from development versioning (6.x.x) to semantic versioning for clearer release communication:

MAJOR (1.x.x): Breaking changes requiring user action
MINOR (x.1.x): New features, backward compatible
PATCH (x.x.1): Bug fixes and improvements

⚠️ v1.0.2 Users: v1.0.2 is a recommended upgrade - fixes critical task creation bug affecting multi-controller operations.

**⚠️ Internal Advanced Support Utility**
Not an official Distech Controls product.
Designed for Advanced Support Specialists to rapidly validate Unified Package installations across EC‑Net 4 revisions.

**🎯 What This Tool Does**
The Distech Controls Unified Package Troubleshooting Tool (v1.0.2) verifies the presence of all required modules, folders, and assets used by:

**Unified Packages**
Productivity Enhancing Tools
EC‑Net 4 / EC‑Net Facilities revisions

It ensures that support staff can quickly identify missing components, confirm installation integrity, and export results for documentation.

**✨ Key Capabilities**
✅ Automated File Presence Validation

Scans all expected modules for selected pack or All Packs
Highlights Present (green) / Missing (red) items
Status bar reports: All files are present or Some files are missing

**🎛️ Simple UI Workflow**

Select Root Drive, Revision, and Pack
Live Modules Path Preview
Buttons: Check, Clear Results, Export CSV

**📄 Results Grid
**
Columns: Status, Pack, Name, Full Path
Right‑click: Copy Selected Rows or Copy Full Path

**📤 Exporting**

Saves findings to UTF‑8 CSV
Default name: FilePresenceResults.csv


**🛠️ System Requirements**

Windows 10 or later
EC‑Net 4 / Facilities installed (any supported revision)
Read access to installation directory (e.g., C:\Niagara)
.NET Framework with WPF support


**🚀 How to Use**

Launch Distech Controls Unified Package Troubleshooting Tool.exe
Choose drive → revision → pack
Click Check
Review present/missing results
Export if needed


**🧰 Troubleshooting**

Access Denied → Run as Administrator (ProgramData often protected)
Verify correct drive + revision
Confirm selected pack is installed
Use “Copy Full Path(s)” to quickly inspect locations


📝 v1.0.2 Release Notes
This release includes:

Fixed scriptblock invocation for path preview
Replaced invalid event wiring with proper CommandBinding
Added functional context‑menu copy handlers


🤝 Support
For assistance, contact Advanced Support or refer to internal documentation.
© 2026 Distech Controls – Internal Use (Advanced Support)
