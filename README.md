# TaskManager Privacy Policy

This repository hosts the human-readable privacy policy for the TaskManager Android application. It is a small static website, separate from the application's source code, APK and user data.

The published policy is maintained in [`index.html`](index.html). This README explains how the repository is organised and how to preview or maintain that page; it does not replace or amend the policy itself.

## What the page contains

- Who maintains TaskManager and how to contact the publisher.
- The policy's statements about collected information and data stored on the device.
- Explanations of app permissions, sharing, retention and deletion.
- Children's privacy, future policy updates and contact information.

Read the policy page for the actual wording. A documentation summary is not an independent audit of every version of the Android app. When app behaviour changes, review the policy against the corresponding app release.

## Repository layout

```text
index.html      Published, styled privacy-policy page
privacy policy  Existing auxiliary placeholder; not the published policy
README.md       Repository and maintenance guide
```

The `privacy policy` file currently contains only a placeholder. It should not be treated as a second complete policy or an alternative copy of `index.html`.

## Preview locally

No Node.js packages, backend service, database or build pipeline are required. Open `index.html` in a browser, or serve the folder locally with Python 3:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`. The example binds to the local computer. Stop the preview server with Ctrl+C when finished.

## Maintain the page

1. Edit `index.html`, preserving readable headings and the contact section.
2. Check the wording against the app's actual permissions, storage and network behaviour.
3. Preview the page on a narrow mobile viewport and on a desktop browser.
4. Check links and contact information, then commit the change.

Repository hosting and GitHub Pages configuration are managed separately in repository settings. This README update does not enable or change website publishing. The Android application itself is maintained in the separate TaskManagerApp repository.

## Scope and licensing

This repository contains documentation, not a login system, data processor or application distribution. Do not add user databases, signing keys, private logs or account credentials to maintain the policy. No new license or privacy terms are introduced by this README.
