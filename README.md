# JITENDAR KEWAT website

A responsive static cybersecurity dashboard prototype with welcome screen and browser speech voice.

## Included
- Dashboard layout and navigation
- Welcome overlay with Hindi welcome speech (browser/device voice; tap Enter because browsers require user interaction)
- URL pattern checker (not live reputation)
- SHA-256 hashing of text and local files
- Pattern-based log analyzer
- Browser-local notes
- PCAP file metadata inspector (not packet decoding)
- Offline rule-based security assistant
- JSON report export
- Quick defensive security tips

## Publish on GitHub Pages
1. Create a repository on GitHub.
2. Upload `index.html` and `README.md` into the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Open the Pages URL GitHub provides after deployment.

## Honest limitations
This is a static browser demo. Dashboard statistics are illustrative; URL checks are basic heuristics; logs use simple pattern matching; PCAP is not decoded; assistant is rule-based. Real live scans, threat intelligence, authentication, server database and advanced analysis require separate backend services and integrations. Use only on systems you own or have permission to test.
