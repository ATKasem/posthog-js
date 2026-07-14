---
'@posthog/next': patch
---

Remove the Pages Router `PostHogProvider.bootstrap` prop; move its value to `clientOptions.bootstrap`. For App Router server-evaluated bootstrap, merge values into `clientOptions.bootstrap` while preserving user-provided fields.
