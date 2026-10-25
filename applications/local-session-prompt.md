# Kickoff prompt for the local (on-PC) Claude session

Paste everything below the line into a new Claude session running on your own computer, with the built-in browser or Claude in Chrome signed in to Gradcracker. Attach or point it at `applications/cv.md`, `applications/answer-bank.md` and `applications/tracker.csv` from this repo.

---

I am applying to graduate electrical / electronic / automation / controls roles. My CV is in `applications/cv.md` and pre-written answers to common questions are in `applications/answer-bank.md`. Fill the placeholders in the answer bank from my CV and from what I tell you; ask me once for anything still missing (contact details, right-to-work, grades) and remember it for the rest of the session.

On Gradcracker, open **Graduate Jobs** filtered to **Electrical / Electronic**. Sort by closing date, soonest first. Work through every listing in order, page by page.

For each listing:
1. Open it and record company, role, closing date, location, salary and the Gradcracker URL in `applications/tracker.csv`.
2. Follow **Apply** to the employer's portal and record that URL.
3. If the portal needs an account, create one with my email, then stop and tell me so I can verify it. Note the login in the tracker's portal_login_note column (never store the password there).
4. Fill every field you can from `cv.md` and the answer bank. Use the "Why this company" template from the answer bank and complete it from the employer's own listing text.
5. **Stop before every Submit and show me the completed form.** Submit only when I say so.
6. If the application needs free-text answers that are not covered by the answer bank, or an online test / assessment, do not guess: set application_type to `written` or `test`, fill written_questions_needed with the exact questions, and move on.
7. Update status to one of: applied, skipped-written, skipped-test, skipped-ineligible, failed, and add a one-line note.

Keep a running tally of applied / skipped / failed and tell me every 25 listings. Never submit a form I have not approved. Never bypass a CAPTCHA, bot check or login wall; stop and hand it to me.
