# Security

Nova is designed to run safely in a private home network.

## How Nova protects you
- **Local by default.** The main screen (HUD) listens only on this computer
  (127.0.0.1). The phone dashboard is reachable on the home network only with
  a password (token) that you set.
- **Asks before acting.** Any physical action (heating, devices) needs a clear
  yes/no confirmation, and "no" is the default. Every change can be undone.
- **Children.** Study-time limits, quiet hours and content filters apply to
  child profiles.
- **No secrets in logs.** API keys and tokens are masked in the logs.
- **Offline-safe.** With a local AI model, Nova works with no internet at all.

## Downloading safely
- Only download Nova from the official release page:
  https://github.com/BOND-V-Technology/NOVA-Home-Offline-Assistent/releases
- Check your download against the published checksums:
  ```
  sha256sum -c SHA256SUMS
  ```

## Reporting a problem
Found a security issue? Please report it privately:

- Open a **GitHub security advisory** on this repository, or
- contact the author through the GitHub profile **BOND-V-Technology**.

Please do not post security issues as public issues before they are fixed.

© 2026 v98881
