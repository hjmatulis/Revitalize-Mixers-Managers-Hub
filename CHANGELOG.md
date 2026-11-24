# Manager Resource Hub: Changelog

Add a new entry at the top each time you publish. Keep entries short: date, what changed, who did it.

## Nov 24 (home, discipline and safety wording)
- Home quick actions: "Log an attendance event" is now "Log a shop attendance event". "Start a review or check-in" is now "Start a 30/60/90-day or quarterly review", with a fuller description (which review, who meets, the form, and how to complete it). "Someone reported a concern" is now "Someone reported a concern to me: what do I do?", with a line saying it covers harassment, discrimination, retaliation, and threats.
- "Not sure which track?" is now "Not sure which discipline process to use?" and explains the two processes (Shop Attendance and Standard Discipline) in plain words. Button reads "Find my process". Discipline Center intro, "Which discipline process?" helper tag, and "Choose the discipline process" heading reworded to match.
- Track A is labeled SHOP ONLY (home card, Discipline Center card, and the Shop Attendance page). Track B is labeled ALL EMPLOYEES.
- Safety page: new note at the top. Questions go to revsafety@revitalizemixers.com, and someone from the Safety Committee will reach out.
- Footer "Last updated" changed to Nov 24, 2026.

## Nov 24 (documentation and backups)
- No change to the hub (index.html is unchanged; footer still reads Nov 23). Notes and instructions refreshed: PROJECT-NOTES.md now shows the current GitHub repo and live address and the black and gold brand; HOW-TO-UPDATE.md has the start-to-finish update routine, backup routine and restore steps; NEW-CHAT-STARTER.md updated. Added SharePoint/Teams embed troubleshooting (HOW-TO-UPDATE.md section F) and the actual embed code to PROJECT-NOTES.md. New backup zip RM-Hub-Backup-2026-11-24.zip.

## 2026-11-17: Visual refresh and tiles
- Removed the "Welcome back, [First Name]" greeting. The headline now reads "Manager Resource Hub".
- Added a brighter blue accent (tile icons, links, hover states, hero glow), slightly bigger text, and more space between sections.
- Quick-access tiles: removed HRIS, Scheduling, and Production. Added a Safety tile that jumps to the Safety policies. Tiles now come from one editable list (see HOW-TO-UPDATE.md).
- Added a Safety group to Policies & Procedures.
- Added info tooltips on: protected leave, rolling 12 months, attendance probation, PIP, new hire.
- External links open in a new tab.
- 30/60/90-day check-in guides now say the employee types their own answers.

## 2026-11-13 and earlier
- 30/60/90-day check-ins rebuilt from HR's check-in sheets, with a supervisor section.
- PIP, Suspension, and Termination request forms and HR document fields added to the Forms guide.
- Verbal Warning form link added.
- Discipline Center split into Shop Attendance (Track A) and Standard Discipline (Track B) pages.
- Reviews, Report a Concern, and Forms pages added. HR contact button on every page.
- First version: Home and Discipline Center with the points calculator.

## Nov 17 (Safety update)
- Removed: Safety Report tile, home alert banner, Recognition section, "Draft for approval" footer text.
- Added: SOPs tile (add address in TILES, `u:''`), "Report a near miss" quick action, Safety tab with full Safety page (near miss form, Safety Handbook link, stop-work authority, rules summary, manager routine, links list, contacts).
- Safety links are set in the SAFE_LINKS list (`u:''`). Near miss form address goes in FORMS.nm `url:""`.

## Nov 17 (Safety update 2)
- Safety page: two tracks side by side (Near miss form; Safety incident = printed template, turn in immediately to Nate Bennett). Removed 911/HR box and HR contact. Moved "What counts as a near miss" above the handbook; added "What counts as a safety incident" (OSHA notice timing marked for Safety to confirm). Added Safety training presentation button. Safety representative = Nate Bennett.
- New links in SAFE_LINKS: 0 handbook, 1 incident template, 2 training presentation.
- Reviews page: removed "HR to confirm" notes; added shop hourly vs office tracks (office has no points) on 30/60/90 steps and form guides.

## Nov 17 (links)
- Documents list: add a 4th item (web address) to make a row a link. Policies: add "Policy name":"address" to POLURL. Tiles `u:''`, SAFE_LINKS `u:''`, FORMS `url:""` unchanged.

## Nov 17 (search)
- Home search is now a real search across hub pages, form guides, policies, documents, and safety links (no Copilot needed). Removed the "Draft preview" Copilot message.

## Nov 17 (discipline forms)
- Replaced Attendance Discipline Form / Standard Discipline Form with the real form set. Shop Attendance (Track A): Coaching, Verbal, Written, Suspension Request (linked), Termination Request (no link yet). Employee Discipline (Track B): Coaching, Verbal, Written (no link yet), PIP Request, Shop non-attendance PIP Request, Suspension Request, Termination Request (no link yet).
- Guides filled in for PIP, Suspension (both), Termination, Verbal. Others say "Instructions coming soon" until question lists are provided.

## Nov 17 (forms page)
- Forms page now groups every form under its category heading (Shop attendance, Conduct and performance, Safety, Reviews).

## Nov 17 (narrow windows)
- Fixed two-column layouts that did not collapse in narrow windows (inline grid styles overrode the media query). Added layouts for Teams tabs (up to 1000px wide) and phones (up to 560px). Tables scroll sideways instead of overflowing.
- Recommended embed: style="width:100%;height:85vh;border:0" so the hub fits the window.

## Nov 17 (SOPs and Manuals)
- SOPs tile linked to the SOP folder; new Manuals tile linked to the Manuals and SOP's folder (SharePoint, RevitalizeMixersTeam site).

## Nov 17 (process + handbook)
- Removed "Recent policy updates". All policies and the Employee Handbook document now open the Current Handbook folder (HANDBOOK constant); Corrective Action & Discipline opens its own policy (CAD constant). Added "Open the Current Handbook" button on Policies.
- Track B process rewritten: coaching/verbal/written forms are filled out but submitted only after the employee acknowledges; PIP/suspension/termination requests submitted right away; HR consulted first only for harassment, serious safety, protected situations, or when unsure. Step 2 links the Corrective Action policy. Track A steps and both ladders updated to match.

## Nov 17 (points in Track A)
- Shop Attendance: added "Point thresholds" (standard and new-hire tables) with a "Check Paycom first" reminder, step 1 reworded to Check Paycom first, and a "Protected exceptions: no points" list. Removed the old ladder (replaced by the tables).
- Points table matched to the handbook wording; early leave 16-59 min is now 2 points (was 3), which resolves the overlap with 1-2 hours.

## Nov 17 (IT Helpdesk)
- IT Helpdesk tile now opens a popup: "email IT for any IT request", Helpdesk@ozinga.com, an "Open an email in Outlook" button (Outlook on the web, pre-filled subject and prompts), and a "Copy the address" button. Address is set in the tile's m:'' value in TILES. Removed the stale "field list is a guide" note from form guides.

## Nov 17 (form guides)
- "How to fill it out" guides rewritten from the real form PDFs: Shop Attendance Coaching/Verbal/Written, Employee Discipline Coaching, Shop and Employee Suspension Requests, Shop PIP Request (same guide used for Employee PIP Request until its PDF is checked). Each guide now has a numbered "Step by step" list (fill out, do not submit, meeting, employee acknowledges, submit) before the field-by-field list.
- Still unchecked: Employee Verbal Warning, Employee PIP Request (guide copied from Shop PIP), Employee Written Warning and both Termination Requests (not built).

## Nov 17 (form guides 2)
- Employee Verbal Warning guide rewritten from its PDF (19 questions, employee response comes before the facts). Employee Written Warning guide written from its PDF (18 questions). Employee Written Warning still needs its form link.
- Employee Written Warning linked.
- Employee PIP Request guide rewritten from its PDF (35 questions, Manager is question 7, office-style examples, no final notice question).
- Employee PIP Request guide: Manager is now question 6, measurable performance is question 7 (matches the Shop PIP order; form must be reordered to match). Marked for office and other non-shop employees.
- Excused Absence form renamed "Shop Attendance - Excused Absence", linked, and guide written from its PDF (7 questions).

## Nov 19
- New logo (no LLC) in header and footer; removed "LLC" from the footer text and logo alt text.
- Earbuds: "no earbuds" changed to one earbud only (Safety rules summary, manager routine, near miss example). Hazard follow-up set to "Within 7 days".
- Reviews: 30-day = manager + employee, then manager reviews with the employee's supervisor, then schedules the follow-up. 60/90-day = direct supervisor + employee. Added "Who meets with whom" note.
- Added President's direct reports section: Annual Goal Setting and Quarterly Check-In Notes (forms pg and pn, no links yet).
- Popups (guides, IT Helpdesk, notices) now open where the user tapped and scroll into view, so they show in the Teams phone app.
- President - Direct Report Annual Goal Setting linked; guide and steps written from its PDF (5 work goals + 1 personal goal, submitted before the goal-setting meeting). Quarterly Check-In Notes still needs its form.

## Nov 22 (Reviews page rewrite)
- Reviews page rebuilt: "Which review is it?" cards (30/60/90, quarterly, annual) showing when, who meets, and who fills out the form; one "before you press Submit" rule; shop vs office note; then step-by-step accordions.
- Annual review for all managers: employee self-review (online form, or printable copy for employees without email who turn it in to their manager, who forwards it to HR) plus a manager review. Quarterly check-in: manager completes and reviews with employee, plus an employee feedback form. New forms (no links yet): ar, am, qf. "Printable copy" button added (set print:"" in FORMS.ar).
- Removed the President's direct reports section and its forms (the Annual Goal Setting link is kept here in case it is needed again: https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=kglVhz1O10GyItWMb32UC4ErlUIjau9AsMnZnS0lHYZUQjBBMUYxTEVCN1dXOTlHNjk4TkdZTzlQWiQlQCN0PWcu).
- Forms page: groups ordered Shop attendance, Conduct and performance, New-hire check-ins (30/60/90 day), Quarterly and annual reviews, Safety.

## Nov 22 (audit)
- Show Up & Earn quarterly bonus updated to gross amounts: $500 (0 points), $475 (1 point), $450 (2 points).
- New "Manager Checklist" tab (every shift, weekly, when something happens, new hires, quarterly, annual) with a Print button and a home Quick action. Edit it in the CHK list.
- Removed leftover placeholders ("[updated date]", "[X] working days"). Added "Last updated" to the footer (edit the date in the footer line each time you publish). Print styles added.

## Nov 22 (annual goal setting)
- "Annual Review" corrected to "Annual Goal Setting": done at the start of each year (employee writes goals online or on paper, manager agrees them in a meeting) and reviewed at every quarterly check-in. Removed the separate manager annual form. Updated the Reviews cards, steps, Manager Checklist, form entry (ar), and Forms page group name ("Reviews and goal setting").

## Nov 22 (check-in forms)
- Linked and wrote guides for 30-Day (Manager and Employee), 60-Day and 90-Day (Supervisor and Employee) check-ins and the Quarterly Performance Check-In, from the form PDFs. The manager or supervisor completes these forms during the conversation (not the employee), so the Reviews page wording was corrected.
- Removed the Core Values tile.

## Nov 22 (shop termination + printable goal form)
- Linked Shop (non-Attendance) - Termination Request (guide from its PDF); added to the Employee Discipline page. Shop Attendance and Employee Discipline termination requests still have no links.
- Created Annual-Goal-Setting-Form.docx, a branded printable version of the Annual Goal Setting form for employees without email. Upload it to SharePoint and send the link so the "Printable copy" button can open it (FORMS.ar print:"").

## Nov 22 (black and gold)
- Brand colors changed to black and gold across the hub (navy and blue removed): backgrounds, headings, tags, tiles, and links. Header logo is now black. The Annual Goal Setting Word form was rebuilt in black and gold. Fixed header padding and table widths on narrow screens.

## Nov 22 (Opus design pass)
- Visual and interaction redesign by Opus, checked against the previous version: all content, form links, guides, and edit lists unchanged. New: animated hero, live search as you type with highlighted matches and arrow-key navigation, sticky nav, Manager Checklist with tick boxes, progress bar, and a Shop/Office filter, smoother page and popup motion.
- Checklist rows have an optional 5th value: 'shop' or 'office' to show a row only for that group (CHK list). Shop-only tags stay on the hazard walk, safety talk, attendance, and excused absence rows (office employees do not do these). Checklist ticks are not saved after you leave the page.

## Nov 23 (safety incident report)
- Safety incident report template linked (Word file in the RMSafety Forms and SOPs site). The Safety Incident Report guide now holds the Workplace Incident Reporting and Response SOP (steps, who does what, medical care rules, follow-up). The guide button reads "Download the template" (FORMS.si lbl). Guides can now set a custom button label (lbl) and section heading (fh).

## Nov 23 (training links)
- New Hire - Safety Training folder linked: new home tile ("New Hire Safety Training") and a card on the Safety page. Forklift Operator Handbook folder linked as a card on the Safety page. Both are also in SAFE_LINKS (Safety links list, searchable).
- Safety Handbook linked (RMSafety Handbook folder). Removed the general "Training" tile (New Hire Safety Training replaces it).

## Nov 23 – Safety tip of the day
- New "Safety tip of the day" card on Home and at the top of the Safety page. One tip per day (rotates by date), "Another tip" button shows the next one.
- To edit: change the `SAFETY_TIPS` list near the bottom of index.html (format `['Topic','Tip text']`).
