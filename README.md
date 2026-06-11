# Regex Tester

A single-file browser tool that tests a JavaScript regular expression against sample text with live match highlighting, capture groups, match positions, and a common-pattern reference.

**Live demo:** https://0xelitesystem.github.io/regex-tester/

## What it does

Type a pattern, toggle the global, ignore-case, multiline, and dotall flags, and paste sample text. The tool highlights every match in the text, lists each match with its index and capture groups, and shows a running count. Invalid patterns report the error instead of breaking. Quick chips insert common patterns for email, URL, digits, hex color, IPv4, dates, and more.

## How to use it

Open `index.html` in any browser, or use the hosted GitHub Pages version. Edit the pattern and test string, or tap a common-pattern chip to start from a known one. Matches update live. The matching engine is your browser's own JavaScript regular expression engine, so behavior matches what your code will see.

## Privacy

Runs entirely in your browser. No network calls, no analytics, no data stored. Your patterns and test text never leave the page.

## License

MIT. Copyright 0xelitesystem 2026.
