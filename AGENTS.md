# Project Rules

## Structure

- Keep the app dependency-free and contained in `index.html`.
- Do not add a server, build step, package manager, or external assets.
- Keep the quiz centered in a narrow, responsive column.

## Design

- Preserve the polished mission-control visual style.
- Support both light and dark themes with `prefers-color-scheme`.
- Use readable sans-serif body text at 14–16px.
- Keep correct feedback green and incorrect feedback red with a shake effect.
- Respect `prefers-reduced-motion` for all animation.

## Accessibility

- Use semantic HTML and native buttons for interactive controls.
- Maintain visible keyboard focus and logical focus order.
- Preserve sufficient color contrast in both themes.
- Do not communicate state through color alone.

## Behavior

- Keep exactly 10 space-exploration questions unless requirements change.
- Preserve progress, score, answer feedback, results, and restart behavior.
- Scores of 8 or higher should receive the celebratory results treatment.

## Validation

- Test correct and incorrect answers, score updates, all question transitions, results, and restart.
- Smoke-test keyboard navigation in the integrated browser after interactive changes.
