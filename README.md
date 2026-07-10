# Avid Bin Distributor

A utility designed to safely distribute Avid Media Composer bins across multiple editorial projects while preserving folder structure.

## Purpose

Assistant editors frequently need to copy updated Avid bins from an Assist project into multiple editor and episode projects. This process is often performed manually through Finder, which can lead to missed projects, incorrect folder placement, or accidental overwrites.

Avid Bin Distributor aims to automate this workflow while prioritizing safety, transparency, and reversibility.

---

# Project Goals

## Primary Goals

- Safely copy Avid `.avb` bins between projects
- Preserve existing project folder structures
- Support shared storage environments such as Avid NEXIS
- Provide clear previews before changes occur
- Generate detailed operation logs
- Minimize risk when working with live editorial projects

## Non-Goals

The first versions will NOT:

- Modify Avid databases
- Open or edit `.avb` files
- Communicate with Media Composer
- Manage media files
- Replace Avid project management software

The tool operates only at the file system level.

---

# Current Workflow Example

Source:



---

# Development Philosophy

This project will follow a safety-first development process.

No testing will occur on live editorial projects until the tool has been extensively tested using a sandbox environment containing copied project folders and bins.

---

# Development Roadmap

## Phase 1 — Core File Engine

Goals:

- Copy one bin from one project to another
- Calculate relative paths
- Create missing folders
- Generate logs

## Phase 2 — Multiple Destinations

Add:

- Multiple episode/project destinations
- Batch distribution
- Preview mode
- Backup handling

## Phase 3 — User Interface

Create a simple application interface:

- Select source project
- Select bin
- Select destination projects
- Review changes
- Execute distribution

## Phase 4 — Automation

Add:

- Project structure detection
- Assist project detection
- Episode scanning
- User editable settings

## Phase 5 — Production Release

Prepare for coworker use:

- Package as Mac application
- Test on multiple systems
- Create documentation
- Establish safe usage guidelines

---

# Testing Environment

Development testing will use a sandbox copy of an actual editorial project structure.

The sandbox will include:

- Avid project folders
- Bin folders
- Folder hierarchy

The sandbox will not include:

- Media
- MXF files
- Render files
- Cache files

---

# Future Features

Possible future additions:

- Assist-to-episode synchronization
- Missing bin detection
- Version comparison
- Show profiles
- Distribution history
- Batch publishing workflows

---

# Status

Project initialized.

Current milestone:

Build the first safe file distribution engine.
