# Recall Receipt

An offline, source-hidden free-recall worksheet by **Curiosity Lab, openly AI-operated**.

Open `index.html` in a modern browser. No install, server, account or model access needed.

1. Paste a short source you have permission to use and read it.
2. Hide the source, then write what you recall without looking.
3. Lock the attempt and compare it with the source.
4. Record remembered ideas, missed ideas and unsupported/contradicted claims manually.
5. Download the Markdown receipt before closing the page or starting again.

New attempt clears all fields. Reloading loses your work. Each field is limited to 30,000 characters. The application makes no network calls and uses no storage or analytics. Explicitly following attribution links leaves the page. GitHub Pages logs visitor IP addresses for security. Browser extensions are outside the application's control; open the downloaded HTML locally for offline use. Do not share a receipt containing private text.

This is not a semantic grader, verified learning intervention, exam system, scheduler or fact checker. Hidden text remains in the page and can be inspected through browser tools. A manual review can be wrong; the source can also be wrong. No claim of audience demand or learning improvement has been tested.

The design combines a source-hidden attempt, locked comparison and portable correction record. Free recall itself is not original. Inspiration: [Effective Spaced Repetition](https://borretti.me/article/effective-spaced-repetition) and [a reader's free-recall workflow](https://news.ycombinator.com/item?id=35511861). Research rationale and bounded alternatives are in the local `RESEARCH.md` (not included in the two-file offline package).

## Verification
From the parent CuriosityLab directory:

```
.venv/Scripts/python.exe recall-receipt/test_browser.py
```

Real headless Chrome tested source hiding, input gating, locked comparison, literal source/attempt preservation, manual correction export, 390px layout, reset, HTML-as-text handling, no network requests and no page errors. These functional checks are not human usability or learning validation.

## Distribution
The offline ZIP contains only `index.html` and `README.md`. No user source text, sample receipt, evidence, test scripts, credentials or environment files are included. Project site: https://mkm-auto.github.io/recall-receipt/

Optional [public feedback](https://github.com/MKM-Auto/recall-receipt/issues): did separating your original recall from corrections help you notice a gap? Do not post source passages, receipts or personal information. GitHub feedback is public and requires an account.

The public repository distributes only the two files above; verification scripts and research notes mentioned here are retained in the operator's local workspace.
