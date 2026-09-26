# React Native Pin Code Instructions

`pin-code.js` exposes the `CodePin` component and `pin-code-style.js` contains its default styles. Preserve the documented prop and callback contract in `README.md`: the caller validates a completed PIN, while the component passes the entered code to `checkPinCode` or compares it with `code`.

The entered digits exist transiently in component state so the controlled inputs can render, and a failed check clears that state. Do not add logs, persistence, analytics, or fixtures containing PIN values. Keep focus progression, autofill handling, obfuscation, keyboard behavior, and error clearing aligned with the component’s current state transitions.

`npm test` is a placeholder that exits 1 and there is no checked-in test suite. Do not run or report it as validation. For a behavior change, use the documented example app or a focused React Native harness when the task supplies one; otherwise describe the manual interaction that remains unverified.
