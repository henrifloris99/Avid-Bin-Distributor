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
