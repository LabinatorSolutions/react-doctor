---
"oxlint-plugin-react-doctor": patch
"react-doctor": patch
"@react-doctor/api": patch
"@react-doctor/core": patch
---

Recognize every detected framework and library capability as a supported scan target, including plain Three.js projects and React-backed frameworks without direct React declarations. The legacy `reactDetected` JSON and API signal now reflects that broader supported-project detection, and remote-installer diagnostics anchor on the executable download command.
