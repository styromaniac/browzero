<img src="https://user-images.githubusercontent.com/43807387/228894570-63b96c84-1a84-4fa5-a0f3-f5a7a023f4e5.svg" width="200" />

# browzero
Browser for the dark web

Don't treat this browser as secure for privacy yet. It's still a work in progress.

Missing features:
1. Private browsing mode where cookies and cache are only stored in physical memory, so then closing/quitting browzero clears everything.
2. Dynamic blocking of other networks than the one currently browsed. I've attempted to make it work by changing blocking rules while hovering or unhovering hyperlinks and navigating forward or back and had it halfway working.

This script requires PyQt5 and PyQtWebEngine packages. You can install these packages using the following command:

```
pip install PyQt5 PyQtWebEngine
```
Make sure you have Python 3 and pip installed on your system before running the command. Never use sudo nor root to install Python external dependencies.
