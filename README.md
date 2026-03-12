# Multi-Agent Brand Studio

Multi-Agent Brand Studio is an OpenClaw skill for setting up a full social media operations team around one or more brands.

Instead of acting like a single general assistant, it creates a structured team with shared knowledge, approval checkpoints, brand isolation, and clear role boundaries.

## What It Does

When this skill is installed and triggered, it sets up:

- A leader agent that coordinates the whole workflow
- Specialist agents for creation, research, engineering, execution, and review
- Shared brand knowledge, operating guides, and workspace files
- Approval-first publishing flow so nothing goes live without owner approval
- Per-brand organization for channels, guidelines, and assets
- Automation support for memory cleanup and recurring maintenance

## Best Fit

Use this skill if you want OpenClaw to help run:

- A single brand with a serious content workflow
- Multiple brands with separate voice, rules, and channels
- A small social team that needs repeatable processes
- An approval-gated content operation instead of ad hoc prompting

## How To Trigger It

After installing the skill, trigger it with a request like:

- `Set up Multi-Agent Brand Studio`
- `Set up my brand studio team`
- `Help me build a multi-brand social media workflow`

## What Happens During Setup

The first run walks through onboarding and helps you:

1. Check OpenClaw prerequisites
2. Scaffold the team workspaces and shared files
3. Patch your `openclaw.json` with the required agent configuration
4. Configure Telegram delivery and channel routing
5. Set instance-wide settings such as owner name, timezone, and language
6. Add your first brand

## What Gets Created

The setup creates a working system, not just one prompt file.

That includes:

- Agent workspaces with role-specific instructions
- Shared memory and knowledge documents
- Brand profiles and content guidelines
- Operations docs for approvals, schedules, and channel routing
- Scripts for scaffolding and config patching

## Included Helper Skills

This package already includes helper skills used during setup, including:

- `instance-setup`
- `brand-manager`
- `qmd-setup`

You do not need to install those separately for the main skill to work.

## Prerequisites

Before using this skill, make sure:

- OpenClaw is installed
- `openclaw onboard` has been completed
- At least one model/auth profile is configured
- Your `~/.openclaw/` directory exists

## Quick Start

1. Install this skill into OpenClaw
2. Trigger: `Set up Multi-Agent Brand Studio`
3. Follow the guided onboarding
4. Add your first brand and start operating
