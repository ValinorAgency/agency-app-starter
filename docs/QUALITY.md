# Quality

This document is the canonical source for project quality gates and their real commands. Add a command only after the corresponding tooling exists.

## Status definitions

- **Required:** must pass for the stated change or delivery boundary.
- **Applicable:** relevant when the described surface or risk is affected.
- **Not configured:** no executable project gate currently exists.

## Quality gates

| Gate | Status | Real command | When to run | Notes |
| --- | --- | --- | --- | --- |
| Lint | Not configured | Not configured | After relevant source or configuration changes | Record the real project command when configured. |
| Type checking | Not configured | Not configured | After changes to typed code or contracts | Record the real project command when configured. |
| Tests | Not configured | Not configured | After behavior changes | Define the relevant test levels when configured. |
| Build | Not configured | Not configured | Before a releasable delivery | Record the real project command when configured. |
| Browser QA | Not configured | Not configured | When browser-facing behavior is affected | Mark `Applicable` or `Required` only for a relevant surface. |
| Accessibility | Not configured | Not configured | When user-facing interaction or content is affected | Document manual and automated evidence when configured. |
| Security | Not configured | Not configured | For changes affecting trust boundaries, data, dependencies, or access | State the checks appropriate to the identified risk. |
| SEO | Not configured | Not configured | When publicly discoverable content is affected | If no discoverable surface exists, record that circumstance in the notes and keep the gate status within the defined vocabulary. |
| Performance | Not configured | Not configured | When performance-sensitive behavior is affected | Record targets only when they are agreed and measurable. |
| Deploy validation | Not configured | Not configured | Before or after deployment, as the project defines | Do not deploy without explicit authorization. |

## Expected evidence and reporting

For every change, report:

- gates executed and their results;
- applicable manual checks and observations;
- gates not executed, with the reason;
- unresolved failures, risks, or limitations.

Do not claim a gate passed without executing its documented command or completing its documented manual procedure.

## Known exceptions

None confirmed.
