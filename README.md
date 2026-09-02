# caselog-autofiller
Logging cases is one of the most tedious parts of anesthesia residency. You already
wrote the plan. This fills the form from it.

Paste one plan — or a whole month of them — and the extension reads out the fields
your case log needs, builds a reviewable queue, and fills the form for you.

WHAT IT DOES

- Paste plans, get a queue. Drop in a single case or an entire document; it splits
  multi-case notes into separate entries automatically.
- Reads the fields for you: patient age band, ASA class, anesthesia type, airway
  technique (including direct vs. video laryngoscopy), vascular access, monitoring,
  nerve block sites, and procedure category.
- Review before you submit. Every case shows what was extracted, with anything the
  tool guessed clearly flagged.
- Fill one at a time, or run the whole queue.
- Manual mode. Build a case by clicking, no note required.
- Program templates. Import your own sites and attendings straight off your case
  log form — no typing 100+ names. Export a template and share it with a colleague.

PRIVACY — READ THIS

All parsing happens locally, inside the extension, on your own computer. Nothing is
sent to any server. No AI service is called. No analytics, no tracking, no account.

Your note text is never written to disk — only the extracted fields are stored, and
any medical record number is stripped before anything is saved.

Your notes may contain protected health information. Check your institution's policy
before using this or any tool with patient data.

IMPORTANT

You are responsible for the accuracy of your own case log. This tool reads your notes
and makes its best guess. It can misread a procedure, pick the wrong attending, or
misclassify an anesthetic. Review every case before submitting. Your case log affects
board eligibility and program reporting.

This is an independent tool. It is not affiliated with, endorsed by, or supported by
the ACGME or any residency program. Provided as-is, with no warranty. If the case log
website changes, the extension may fill fields incorrectly or stop working.

SETUP

On first run you'll be walked through a short setup: pick or import your program's
sites and attendings, then test the extraction against a few of your own notes so you
can see how well it reads your writing style before you trust it.
