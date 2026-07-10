# ADR-0001: Semantic Design Tokens

- Status: Accepted
- Date: 2026-07-11

## Context
Hard-coded colors, spacing values and typography lead to inconsistency and make themes difficult to evolve.

## Decision
Arki will expose only semantic design tokens to components. Components must not reference literal visual values directly.

Examples:
- Surface.Background.Primary
- Text.Primary
- Border.Subtle
- Accent.Default
- Spacing.Medium
- Radius.Large
- Motion.Standard.Duration

## Consequences
### Positive
- Centralized theming
- Easier light/dark themes
- Better maintainability
- Consistent visual language
- Simplified accessibility adjustments

### Trade-offs
- Additional abstraction layer
- Initial token design requires careful planning

## Implementation Guidance
Literal values belong only in theme definitions. All reusable controls consume semantic tokens exclusively.
