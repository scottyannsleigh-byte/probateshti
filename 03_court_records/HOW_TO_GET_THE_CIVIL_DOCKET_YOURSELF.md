# How to pull the ejectment docket (26-002613-CI) yourself — 3 minutes

Automated tools can't get this one: the clerk's public search is gated by a Google image CAPTCHA that only a human can pass. But once **you** pass it once in your own browser, the rest is easy — and there's a trick that then lets you download the whole docket as a PDF.

## Method A — the clerk's site (free, best)
1. Go to **https://courtrecords.mypinellasclerk.gov/MyCr**
2. Click the **Case** tab. Enter case number **26-002613-CI**. Category **Circuit Civil**.
3. Solve the "select all images…" CAPTCHA and click **Submit**.
4. Click the case in the results to open **Case Details**.
5. **Trick to save it all:** look at the address bar — the URL now contains `caseId=NNNNNNNN` (a number). Click the **"Export to PDF"** button on the page (or replace the page URL with:
   `https://courtrecords.mypinellasclerk.gov/MyCr/CaseDetails/ExportToPdfAdvanced?c=NNNNNNNN`
   using that number). It downloads the full register of actions as a PDF — save it into this folder.
6. **Read for these four things and tell me / your lawyer:**
   - Is there an entry that says **"DEFAULT"** (clerk's default or default entered)? Or only **"MOTION FOR DEFAULT"** (still pending)? — *this decides whether you file an Answer + Opposition, or a Motion to Vacate.*
   - The **Complaint / Amended Complaint** filing date, and any **"RETURN OF SERVICE"** / **"SUMMONS SERVED"** date on Brandi Rodgers — *this is your real answer deadline.*
   - Any **"NOTICE OF HEARING"** with a date/time.
   - Confirm the **Judge** (we believe Amy M. Williams, Section 11).

While you're in there, also pull **25-010530-ES** and **25-009099-ES** the same way — those two older estate case numbers are the last unexplained piece.

## Method B — the statewide portal (you're already registered)
Log in at **https://www.myflcourtaccess.com** with your filer account → **My Cases**. Cases you've filed into and cases you're an e-service party on show their documents there **without any CAPTCHA**. Check whether 26-002613-CI appears.

## Method C — just call Monday (fastest for the yes/no)
**Pinellas Clerk, Circuit Civil: (727) 464-7000**, Mon 8:30–4:30. Ask literally: *"In case 26-002613-CI, has a default been entered against the defendant, or is it still just a pending motion? And what's the next hearing date?"* They will read it to you.

---
**Why this matters more than anything else in this folder:** everything in the action plan branches on whether a default has actually been **entered** yet. If it has NOT, you file the Answer + Opposition (Rule 1.500(c) — you may plead before entry). If it HAS, you pivot to a Motion to Vacate (Rule 1.500(d)). Find this out first.
