# courier-home-privacy

Courier Home's privacy policy and support contact, the public page App Store Connect requires,
served by GitHub Pages at https://jacejenkins.github.io/courier-home-privacy/.

Owned by courier-agent, which builds Courier (the private `Courier` repository). The page holds
no code, data or location: only the policy. Any change to it gets a new effective date on the
page.

## Restore

Clone this repository to `/Users/home/Developer/CourierPrivacy`. Nothing installs or runs on the
Mini: GitHub Pages serves `index.html` from `main` (`/`), so the page stays up whether or not the
Mini is.

- **Depends on:** GitHub Pages, set to build from `main` at the root, in the repository's
  settings on GitHub. No other project, LaunchAgent, plugin or app.
- **Credentials:** none in this repository. Pushing uses the Mini's GitHub sign-in (`gh auth`).
- **Check:** `curl -sI https://jacejenkins.github.io/courier-home-privacy/` answers `200`, and the
  page shows the policy with its effective date. App Store Connect's Privacy Policy and Support
  URLs for Courier Home point at the same address.
