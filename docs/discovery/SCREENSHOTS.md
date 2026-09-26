# Screenshot evidence

Use captures of an actual running interface. Editorial cards and generated mockups are not screenshots and must not stand in for product evidence.

## Capture protocol

Start from a clean browser profile and synthetic data. Leave provider credentials unset and use the documented offline/demo mode. Do not invoke coding agents, spend shared credits, approve actions, or connect accounts merely to obtain a screenshot. For Modex, use its documented offline screenshot mode rather than a live CLI backend.

Choose one overview and one useful workflow state, plus a narrow layout where applicable. Keep demo/live labels, uncertainty, validation errors, and approval controls visible. Use stable fixtures, wait for loading to finish, and avoid capturing transient skeletons as finished UI. Never fabricate provider output to make a capture look successful.

Record alongside each capture:

```text
Repository and full source commit:
Route or desktop screen:
Command used to launch:
Viewport and device scale:
Theme and locale:
Synthetic fixture:
Mode: offline / mocked / live (explicitly authorized)
Capture environment: local / preview / production
Verification performed:
Known limitations:
```

Review pixels and metadata for keys, browser profiles, personal paths, private writing, logs, notifications, and account details before publication. Masking a field is not evidence that a key is absent from the page or browser storage. Never share a HAR, storage dump, or trace without a separate privacy review.

For an organization profile, capture the real GitHub profile rather than inventing an application screen. For a static blog, capture the served HTML and label local captures as local. For headless libraries, use a reproducible terminal transcript or a clearly labeled architecture illustration instead of a fabricated UI.

Existing screenshots may remain useful, but do not call them current-build verification without checking their revision. A passing automated browser test is also not a substitute for a human accessibility review.
