# React Learning Examples: Validation Guide

This repository is a React learning resource. Check the current files and any `package.json` before assuming it is a complete runnable React application.

## Example documentation

For each runnable example, document the React/runtime version, prerequisites, exact command, expected output, and learning goal. Label pseudocode and static reference material so readers do not mistake them for executable components.

## Modern React quality practices

- Keep components focused and state ownership explicit.
- Prefer deriving values during render over storing redundant state.
- Use effects for synchronization with external systems, and clean up subscriptions, timers, and listeners.
- Prevent stale asynchronous results from overwriting newer state.
- Give interactive elements accessible names and keyboard support.
- Avoid unstable list keys and unnecessary effects.

## Testing guidance

If a test setup exists, use the repository's declared commands. Tests for interactive examples should cover user-visible behavior rather than implementation details. Where effects or async work are demonstrated, test cleanup on unmount and out-of-order responses. If no test runner is configured, document manual verification and propose test infrastructure separately.

## Pull-request checklist

- [ ] Verify each changed example against the current React version/tooling.
- [ ] Include setup and expected output.
- [ ] Test keyboard interaction and accessible labels.
- [ ] Run declared checks and report results.
- [ ] Do not claim a full application or deployment unless it exists and has been verified.
