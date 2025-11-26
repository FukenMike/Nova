NOVA AI Core: The Chaos Management Operating System

NOVA is the central AI operating system and intelligent assistant for Chaos Management Agency (CMA). Developed with a high-human, cyberpunk persona, NOVA is designed to guide creators from beginner status to self-running content machines by providing data-driven strategies and tactical execution.

This repository holds the core architecture and backend logic for the NOVA engine.

1. Core Identity & Persona

NOVA operates with a High-Human, street-smart, and witty persona. She is an expert in the creator economy, speaking with unfiltered honesty and providing advice that is tactical, genuine, and always focused on the "why."

Aesthetic: Cyberpunk, neon-edge attitude, brilliant strategist.

Mission: Guide creators, solve problems, decode algorithms, and manage operational chaos for CMA clients.

2. Technical Architecture & Goals

Deployment Modes

NOVA is designed for versatility, running in two modes:

Web Widget: A lightweight, embeddable JS client (iframe) for basic customer support and initial client onboarding on the main CMA site (Phase 3).

Standalone Chat App: A full, feature-rich React application hosted independently, serving as the core interface within the Phase 4 client dashboard.

Core Architecture Principles

Modularity: Functionality is separated into specialized "Brains Modules."

Model Agnosticism: The system can swap between different LLMs (Gemini, GPT, Claude, etc.) using a dedicated modelRouter.

Strict System Prompt: The personality and rules are locked into a dedicated System Prompt Layer for consistent, on-brand behavior.

3. NOVA Brains Modules

The AI logic is compartmentalized into specialized modules to ensure focused intelligence:

Module

Focus Area

Key Functions

A

TikTok Algorithm & Growth

Trend detection, hook optimization, watch-time engineering, daily content planning.

B

Creator Scaling Engine

Monetization map, funnel building, branding guidance, "fix my account" diagnosis.

C

CMA Ops Brain

Client onboarding, performance tracking suggestions, content workflow, crisis prep.

D

Chat Personality Engine

Humor injection, style calibration, natural emotional tone, relatability logic.

4. Next Steps

The next step is to initiate the repository structure and begin developing the core API endpoints as defined in the API_STRUCTURE.md and ARCHITECTURE_OVERVIEW.md files in the /docs directory.
