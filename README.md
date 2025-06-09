# Task 8: Identify and Remove Suspicious Browser Extensions

## 🔍 Before Cleanup
| Extension Name            | Status             | Risk Level | Action Taken     |
|---------------------------|--------------------|------------|------------------|
| daily.dev                 | Enabled            | Low        | Kept             |
| Google Docs Offline       | Enabled (inactive) | Low        | Kept             |
| Office - Enable Copy and Paste | Disabled (unsupported) | Medium | Removed          |
| Torrent Scanner           | Disabled (untrusted) | High     | Removed          |

## 🧪 Analysis Summary
- **Torrent Scanner**: Flagged by Enhanced Safe Browsing, indicating suspicious behavior or unsafe code. Removed immediately.
- **Office - Enable Copy and Paste**: Marked as unsupported. Unmaintained extensions may have unpatched vulnerabilities.
- **daily.dev** and **Google Docs Offline** are safe, from trusted sources, and do not require concerning permissions.

## 🧹 Actions Taken
- Removed `Torrent Scanner` and `Office - Enable Copy and Paste` extensions.
- Retained useful, verified extensions only.

## 🧠 Learnings
- Regularly reviewing browser extensions is crucial to avoid malicious or unmaintained add-ons.
- Disabled/untrusted extensions can compromise security and privacy even when not actively used.
- Use Chrome's "Enhanced Safe Browsing" warnings as an early alert system.