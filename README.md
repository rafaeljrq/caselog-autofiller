# Case Log Autofiller for Anesthesia Residents

A Chrome extension that reads your written anesthesia plans and fills in your
residency case log form.

Paste one plan or a whole month of them. The extension pulls out the fields your
case log needs, builds a reviewable queue, and fills the form for you.

## What it does

- Paste plans, get a queue. Notes with several cases split into separate entries automatically.
- Reads the fields for you: age band, ASA class, anesthesia type, airway (including direct vs. video laryngoscopy), access, monitoring, nerve blocks, and procedure category.
- Review before you submit. Anything the tool guessed is flagged.
- Fill one at a time or run a batch of any size you choose.
- Manual mode: build a case by clicking, no note needed.
- Program templates: import your sites and attendings from your case log form, then export to share with a coresident.
- Custom vocabulary: teach it your own shorthand, one line each.

## Do not paste patient identifiers

Before pasting a note, remove names, medical record numbers, dates of birth, and
anything else that identifies a patient. The fields this tool reads do not
require identifiers. This tool does not look for or extract medical record
numbers, and it warns you if a paste appears to contain one.

## Privacy

All parsing happens locally on your computer. Nothing is sent to any server, no
AI service, no analytics, no account. Your note text is never saved to disk;
only the extracted fields are.

Full policy: [PRIVACY.md](PRIVACY.md)

## Important

You are responsible for the accuracy of your case log. This tool makes its best
guess and can misread a procedure, attending, or anesthetic, so review every case
before submitting.

## Not affiliated with any institution

This is an independent tool built by an individual. It is not made, endorsed,
sponsored, or supported by the ACGME, by any university, hospital, health system,
or residency program, or by any medical board. The included sample preset lists
one program's hospitals purely as an example configuration; it does not imply
that institution reviewed, approved, or has any connection to this tool. Provided
as is, with no warranty.

## Support

Found a bug or have a request? [Open an issue](../../issues).
