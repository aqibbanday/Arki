# ADR-0002: Desktop-First Design

- Status: Accepted
- Date: 2026-07-11

## Context
Arki targets professional Windows desktop software built with WPF. Designing for multiple platforms would introduce compromises that reduce quality and increase complexity.

## Decision
Arki is desktop-first. APIs, layouts, interactions and components are optimized for keyboard, mouse, high-resolution displays and resizable windows.

## Implications
- Rich desktop interactions over touch-first patterns.
- Multi-window support.
- Keyboard-first accessibility.
- High-DPI rendering.
- Flexible layouts for large screens.

## Non-goals
- Mobile-first layouts.
- Responsive web design patterns.
- Cross-platform UI compromises.

## Rationale
Specialization allows Arki to provide a superior Windows experience rather than a generic cross-platform abstraction.
