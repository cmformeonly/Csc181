# Product Backlog

## Team Information

- Team name: JC Systems  
- Project title: AyoNa  
- Primary user group for the first release: Tenant  
- Format: User stories with one use case

| Member | GitHub username | Personal CSC181 repository |
| :---- | :---- | :---- |
| Azur, Kurt Renzo H. | Draeze83 | https\://github.com/Draeze83/CSC181 |
| James Ralf P. Canonigo | cmformeonly | https\://github.com/cmformeonly/Csc181 |
| Calvyn Kent L. Adeva | calvynddb | https\://github.com/calvynddb/csc181 |
| Obrenah Z. Mendoza | aubi-zami | https\://github.com/aub-zami/CSC181 |

## 1\. Interview Summary

We spoke to two stakeholder groups: caretakers (C) and tenants (T). We did not interview the owner or the repairman, the other two groups in our proposal's stakeholder list. Everything we know about them comes from what the caretakers told us (see A1 and A6). People named in our raw notes are referred to here by role only. 

| Code | Stakeholder role | Date | Method | Interviewer(s) |
| :---- | :---- | :---- | :---- | :---- |
| C1 | Caretaker | 2026-10-23  | In person | Obrenah Z. Mendoza |
| C2 | Caretaker | 2026-10-24 | In person | Obrenah Z. Mendoza |
| T1 | Tenant | 2026-10-25  | Online Survey (written answers) | Azur, Kurt Renzo H. |
| T2 | Tenant | 2026-10-25  | Online Survey (written answers) | Obrenah Z. Mendoza |

## 2\. From Interview Notes to Needs

| ID | Source | What we heard or saw | Underlying need | Requirement idea | Type |
| :---- | :---- | :---- | :---- | :---- | :---- |
| F1 | C1 | "Kung kinsa tong niduol sa ako, mao ra gyud akong mabaw an." (The only complaints I know about are from the people who come to me.) The tenant's broken ceiling fan, reported to the other caretaker before a vacation, never reached her and was still broken when the tenants came back. | Every caretaker knows about every open complaint, no matter which caretaker received it | Every caretaker sees the same room screen: each room is a box listing that room's complaints and their status, and rooms with open complaints are marked red | F |
| F2 | C1, C2 | C1: a note she left for the other caretaker went missing, and the other caretaker said she never saw it. C2: "Dapat ibutang gyud niya dira. Pabal on pud ko niya dili kay mag note note rapud siya." (She should put it there, and she should also tell me, not just leave notes.) | Complaints are not lost when one shift hands over to the next | A saved complaint stays in its room's box, with who logged it and when, until the tenant marks it resolved | Q |
| F3 | C1 | "I expected yours was already okay because the part had been bought." The part had been bought but not installed, and the owner scolded her when she asked whether it was fixed. | Tell "part bought" apart from "repair done" | The tracker keeps buying materials, reaching the repairman, the visit date, "Ongoing", and "Repair complete" as separate steps, and only the tenant's "Mark resolved" closes the complaint | F |
| F4 | C1 | "Kung wala ka ninaog adto ga expect kung natauran naka." (If you hadn't come down to complain, I would have assumed you were already attended to.) The complaint had slipped her mind after some time. | See which complaints have waited longest without relying on memory | Rooms with open complaints appear first, and the caretaker can sort complaints by date reported, oldest first | F |
| F5 | C1, C2 | C1: the owner asks whether things are already fixed, and that is how they track complaints. C2: "Kinahanglan musulti jud ko kay masuko biya pud na si madam 'nganong karon paman ka nagsulti'." (I have to tell her, because \[the owner\] gets angry and asks why I only told her now.) | The owner knows the state of every repair without asking the caretakers  | The owner can view the status of every complaint | F |
| F6 | C2 | "Wala ko nakalimot pero akong amo nakalimot... nalista nako pero akong amo makalimot ba unya dugay pa makabalik kay naay lakaw." (I didn't forget, my boss did. I had it listed, but she forgets, and it takes a long time for her to come back because she is out running errands.) | The owner keeps track of complaints that wait on her purchase, even while away | The owner can see, from her phone, the complaints that are waiting for a part to be bought | F |
| F7 | C2, T2 | C2: the caretakers set the repair date themselves when their regular repairman is available, and the longest he takes to arrive is about two days. T2: "Tagad lang daw mi." (They told us to just wait.) T2 was not given a date. | Tenants know when the repair will happen | The caretaker asks the repairman for an exact visit date and time and assigns it to the room; the tenant's tracker shows it as the estimated repair date and time | F |
| F8 | T1 | "We did not receive any updates, so we had to ask for updates ourselves." T1 said they would stop using the app if they still had to keep following up with the caretaker. | Know the progress of a report without asking anyone | A tenant has a report history listing previous and ongoing complaints, each with its current status | F |
| F9 | T1 | "We did not receive any updates, so we had to ask for updates ourselves." T1 said they would stop using the app if they still had to keep following up with the caretaker. | Know the progress of a report without asking anyone | A tenant has a report history listing previous and ongoing complaints, each with its current status | F |
| F10 | T1 | The broken light took one week to fix, partly because the caretaker was unavailable. The light affected T1's studies, so T1 used a lamp and studied somewhere else. | Report a problem when no caretaker is around | A tenant can use the Report button at any time, and the complaint appears in that room's box on the caretakers' screen | F |
| F11 | T2 | The ceiling fan took a few days to fix because a replacement fan had to be bought first. The caretaker told T2 it might only be fixed the next day and to wait. | Understand why a repair is waiting | The tenant's tracker shows "Waiting for materials" while the parts for the repair are being bought | F |
| F12 | C2, C1, T1, T2 | C2 said ceiling fans are what usually break. C1 and T2 both described broken ceiling fans. T1 described a broken sink and a broken light. | Report the common problems quickly and clearly | The report form offers a list of complaint types (light, ceiling fan, faucet, sink, wiring, shared Wi-Fi, other) | F |
| F13 | C2 | "Dapat ibutang gyud niya dira." (She should put it there \[where it can be seen\].) | Open complaints are visible at a glance | Rooms with open complaints are marked red on the caretaker's room screen, which is the first screen after signing in | Q |
| F14 | C2 | A second parts buyer buys lights and faucets, and the owner buys ceiling fans. On what to buy: "Akoy muingon. Ako pud mucontact sa amo." (I decide, and I also contact the boss.) | Know which part is needed and who is responsible for buying it | The caretaker's first step on a complaint is "Buy materials". Recording which part is needed and who buys it stays out of scope for the pilot (proposal out-of-scope item 3\) | F |
| F15 | C1 | "Akong isulat ang reklamo ug ang ipapalit..." (I write down the complaint and what needs to be bought.) | The caretaker knows what is broken and what to buy before going to the room | A tenant can add a comment and attach an image to a report | F |
| F16 | C1 | "I had assumed the repairman had already been told. After some time it slipped my mind." | Know whether the repairman has been contacted | The caretaker gets the repairman's number from the contact list (no in-app messaging) and marks the complaint "Repairman reached"; the tenant's tracker shows this step | F |

### Assumption log

| ID | Assumption | Risk if wrong (High/Medium/Low) | How we will check it |
| :---- | :---- | :---- | :---- |
| A1 | The owner will use the app to check repair status and purchases. We did not interview her; F5 and F6 come from the caretakers. | High | Interview the owner, or show her the story map and a paper prototype, before Sprint 1 ends |
| A2 | Both caretakers and the owner have a smartphone with mobile data or Wi-Fi they can use at the boarding house. | High | Ask C1, C2, and the owner during the stakeholder walk-through |
| A3 | Caretakers will update a complaint's status (parts purchased, scheduled, fixed) soon after it happens. The tenant view is only useful if they do. | High | Ask C1 and C2 how and when they could update it; check during the walk-through |
| A4 | Tenants will submit complaints through the app instead of going down to the caretaker. Only two tenants answered our survey. | Medium | Survey more tenants, or ask tenants to try a prototype |
| A5 | Caretakers can read an English interface. Both caretakers answered mostly in Cebuano. | Medium | Show C1 and C2 the prototype screens and ask which labels are unclear |
| A6 | The repairman does not need to use the app. The caretakers will keep calling or texting him and will enter the agreed schedule themselves. | Low | Confirm with C1 and C2; ask the repairman if possible |
| A7 | Tenants will confirm a completed repair and leave a rating, as planned in our meeting's draft tenant screen and proposal capability 3\. No one we interviewed asked for a rating. | Medium | Ask T1 and T2 during the walk-through whether they would confirm and rate a repair |
| A8 | Materials are bought before the repairman is contacted, as in our meeting's draft caretaker steps. Some repairs may need the repairman to check the fault first, or may need no materials at all. | Medium | Ask C1 and C2 how often the repairman has to check a fault before they know what to buy |
| A9 | The owner will agree to host the pilot in her boarding house. Our proposal names this as the biggest remaining risk. | High | Request permission through a letter or meeting with the owner before Sprint 1 |

## 

## 3\. User Stories

| ID | User story | Source finding(s) | Epic | INVEST check |
| :---- | :---- | :---- | :---- | ----- |
| US-01 | As a tenant, I want to report a broken item in my room from my device, so that I can report it even when no caretaker is downstairs. | F10, F1 | Report a problem | Yes |
| US-02 | As a tenant, I want to choose the complaint type from a list (light, ceiling fan, faucet, sink, wiring, shared Wi-Fi, other), so that the caretaker knows which part may be needed. | F12 | Report a problem | Yes |
| US-03 | As a tenant, I want to add a comment and attach an image to my report, so that the caretaker can see what is broken and what to buy before coming to my room. | F15 | Report a problem | Yes |
| US-04 | As a tenant, I want a report history of my previous and ongoing complaints, each with its current status, so that I don't have to go down and ask the caretaker. | F8, F9 | Track my complaint | Yes |
| US-05 | As a tenant, I want a step-by-step tracker that shows each step my repair has reached and when, including the estimated repair date and time, so that I know where my repair stands without asking anyone. | F9, F11, F17, F10 | Track my complaint | Yes |
| US-06 | As a tenant, I want to mark my repair resolved after I check it, so that my complaint is not closed while the item is still broken. | F3, F1 | Track my complaint | Yes |
| US-07 | As a caretaker, I want to see every room as a box listing its complaints and their status, with rooms that have open complaints marked red, so that I know about complaints the other caretaker received. | F1, F2, F13 | Manage complaints | Yes |
| US-08 | As a caretaker, I want to sort complaints by date reported, oldest first, so that I handle the longest-waiting complaint first without relying on memory. | F4 | Manage complaints | Yes |
| US-09 | As a caretaker, I want to log a complaint that a tenant tells me in person, so that it goes into the room's box instead of a paper note. | F2, F1 | Report a problem | Yes |
| US-10 | As a caretaker, I want to set a complaint to "Buy materials" when the repair needs parts, so that the tenant sees "Waiting for materials" instead of thinking the complaint was forgotten. | F11, F14 | Manage complaints | Yes |
| US-11 | As a caretaker, I want to get the repairman's number from a contact list and mark the complaint "Repairman reached", so that the other caretaker and the tenant know the repairman has been told. | F16, F7 | Manage complaints | Yes |
| US-12 | As a caretaker, I want to assign the visit date and time I agreed with the repairman to the room, so that the tenant sees when to expect the repair. | F7 | Manage complaints | Yes |
| US-13 | As a caretaker, I want to mark a repair "Ongoing" when the repairman arrives, so that the tenant knows the repair has started. | F9, F8 | Manage complaints | Yes |
| US-14 | As a caretaker, I want to mark a repair complete, so that the tenant is asked to verify it and the other caretaker can see it is done. | F1, F3 | Manage complaints | Yes |
| US-15 | As the owner, I want to see the status of every complaint from my phone, so that I know which repairs are waiting on me without asking the caretakers. | F5, F6 | None | Yes |

### Epics and how we split them

| Epic | Split into | How we split it |
| :---- | :---- | :---- |
| Report a problem: "As a tenant, I want to report a broken item, so that it gets fixed." | US-01, US-02, US-03, US-09 | By role (the tenant reports in the app, or the caretaker logs a complaint a tenant made in person), then simple first (US-01 submits a plain report; US-02 adds the complaint type; US-03 adds a comment and image). |
| Track my complaint: "As a tenant, I want to follow my repair, so that I don't have to keep asking." | US-04, US-05, US-06 | By workflow step, from the tenant's side: see the report history, follow the tracker, mark the repair resolved. |
| Manage complaints: "As a caretaker, I want to manage all repair complaints, so that none are forgotten." | US-07, US-08, US-10, US-11, US-12, US-13, US-14 | By workflow step, following the caretaker steps from our meeting: see the room boxes, pick the oldest complaint, buy materials, reach the repairman, assign the visit date and time, mark ongoing, mark complete. |

### Stories we rewrote

1. **Before:** "As a tenant, I want to report problems easily, check the status of my repair request anytime, and receive updates on when the repair will be completed." (taken almost word for word from T1's survey answer)   
   **After:** US-01 (report a broken item), US-04 (report history with status), and US-05 (step-by-step tracker with the estimated repair date and time).   
   **Reason:** not small or singular, since it bundled three goals joined by "and"; "easily" is a weak word that cannot be tested.  
2. **Before:** "As a caretaker, I want to update a complaint's status, so that tenants are informed."   
   **After:** US-10 (buy materials), US-11 (repairman reached), US-12 (visit date and time), US-13 (ongoing), and US-14 (repair complete).   
   **Reason:** not testable as written, because "update the status" did not say which statuses exist or what the tenant sees; it was also too big to size (not estimable). We split it along the caretaker steps from our meeting notes.  
3. **Before:** "As a user, I want a shared complaint list."   
   **After:** US-07.   
   **Reason:** not valuable as written. "User" hid who needs the list, and there was no benefit. The rewrite names the caretaker and ties the benefit to F1, complaints given to the other caretaker.

## 4\. Acceptance Criteria

### US-01: Report Broken Item from Device 

Acceptance criteria:

- [ ] Allows a logged-in tenant to submit a broken item report with a room number and text description at any time.   
- [ ] Displays a confirmation message with a timestamp upon successful submission.   
- [ ] Prevents submission and displays an error message "Description cannot be empty" if the tenant submits a blank form (unhappy). 

Scenario 1: Successful report submission 

```
Given Tenant in "Room 44" is logged into the AyoNa app 
When the tenant enters "Ceiling fan making loud rattling noise" in the description and clicks "Submit Report" 
Then the system creates a new complaint ticket for Room 44 with status "Reported" and displays "Report submitted successfully" 
```

Scenario 2: Empty description submitted 

```
Given Tenant in "Room 44" opens the broken item report form
When the tenant clicks "Submit Report" without typing a description
Then the system blocks submission and displays an error banner reading "Description cannot be empty"

```

### US-02: Select Complaint Type 

Acceptance criteria:

- [ ] Displays a predefined drop-down selection of complaint categories: Light, Ceiling Fan, Faucet, Sink, Wiring, Shared Wi-Fi, Other.  
- [ ] Automatically categorizes the submitted complaint card on the caretaker view under the selected category.  
- [ ] Defaults to "Other" and prompts the user for text clarification if no specific category is selected (unhappy).

### US-03: Add Comment and Image to Report 

Acceptance criteria:

- [ ] Provides an optional text box for additional comments and a photo upload button accepting PNG/JPEG image files.  
- [ ] Displays an image preview thumbnail before submission.  
- [ ] Rejects image attachments larger than 5 MB and displays an error message "Image file exceeds 5 MB limit" (unhappy).

Scenario 1: Valid photo attached 

```
Given Tenant in "Room 3" is reporting a leaking sink
When the tenant selects a 2 MB JPEG photo of the broken pipe and submits
Then the system saves the image and attaches it to the complaint card for the caretaker to view
```

Scenario 2: Oversized image attachment 

```
Given Tenant in "Room 3" selects a high-resolution photo file of size 8 MB
When the tenant attaches the image to the report form
Then the system rejects the file upload and displays an alert "Image file exceeds 5 MB limit"
```

### 

### US-04: View Tenant Report History

Acceptance criteria:

- [ ] Displays a list of all active and past repair requests submitted by the logged-in tenant, ordered from newest to oldest.  
- [ ] Shows the room number, reported date, fixture category, and current status label for each entry.  
- [ ] Displays the message "No previous repair complaints found" when a tenant with no report history views the screen (unhappy).


Scenario 1: Non-empty report history 

```
Given Tenant in "Room 29" has submitted 2 complaints in the past month
When the tenant opens the "My Complaints" history page
Then both complaint cards appear with their respective date reported and current status labels ("Completed" and "Waiting for materials")
```

Scenario 2: No report history available 

```
Given a newly registered tenant in "Room 15" has never submitted a repair report
When the tenant opens the "My Complaints" history page
Then the system displays an empty state banner reading "No previous repair complaints found"
```

### US-05: Track Step-by-Step Status 

Acceptance criteria:

- [ ] Displays a dynamic stepper showing progress through states: "Reported", "Waiting for materials", "Repairman reached", "Scheduled", "Ongoing", "Repair complete".  
- [ ] Displays the assigned estimated repair date and time once set by the caretaker.  
- [ ] Displays a warning banner "Connection lost.Showing cached status" when internet access is unavailable (unhappy).


Scenario 1: Scheduled repair date displayed

```
Given a complaint for "Room 204 Ceiling Fan" has been assigned a visit date of "Nov 14, 2:00 PM"
When the tenant opens the step-by-step status tracker for this complaint
Then the stepper highlights "Scheduled" as active and displays "Estimated Repair Date/Time: Nov 14, 2:00 PM"
```

Scenario 2: Offline status connection lost 

```
Given the tenant's device loses internet connection while browsing AyoNa
When the tenant opens the status tracker page
Then the system displays the last known status step with a warning banner "Connection lost — showing cached status"
```

### 

### US-06: Mark ‘Repair Resolved’ by Tenant 

Acceptance criteria:

- [ ] Displays a "Mark Resolved" button on complaints marked "Repair complete" by the caretaker.  
- [ ] Moves the complaint to the tenant's resolved archive and removes it from the caretaker's active room screen upon confirmation.  
- [ ] Prevents tenants from marking a complaint as resolved if its current status is not "Repair complete" (unhappy).


Scenario 1: Tenant resolves completed repair 

```
Given a complaint for "Room 20 Light" has status "Repair complete"
When the tenant clicks "Mark Resolved" and confirms
Then the complaint status changes to "Resolved", archiving the ticket and removing the red highlight from Room 204 on the caretaker screen

```

Scenario 2: Attempted resolution on incomplete repair 

```
Given a complaint for "Room 20 Light" is currently at status "Ongoing"
When the tenant views the complaint detail page
Then the "Mark Resolved" button is disabled with a hint reading "Can only resolve after caretaker marks repair complete"
```

### 

### US-07: View Shared Room Queue 

Acceptance criteria:

- [ ] Displays all boarding house rooms as a grid of boxes visible to all logged-in caretakers.  
- [ ] Automatically highlights room boxes in red if they contain one or more open complaints.  
- [ ] Displays the status indicator "No open complaints" and a green border for rooms with zero pending issues (unhappy).


Scenario 1: Pending complaint highlighted red 

```
Given Room 102 has 1 open complaint reported to Shift A caretaker
When Shift B caretaker logs into the system screen
Then Room 102 appears as a highlighted red box listing the open complaint and its date reported
```

Scenario 2: All room complaints resolved 

```
Given all reported room complaints for the boarding house have been marked resolved
When any caretaker opens the room queue screen
Then all room boxes display with green borders and state "No open complaints"
```

### 

### US-08: Sort Complaints Oldest First 

Acceptance criteria:

- [ ] Provides a sort toggle on the caretaker dashboard allowing sorting by "Oldest Reported First" and "Newest Reported First".  
- [ ]  Defaults the sorting order to "Oldest Reported First" upon page load.  
- [ ] Maintains the current sort selection when the caretaker refreshes the page or switches tabs (unhappy).


### US-09: Log In-Person Complaint  

Acceptance criteria:

- [ ]  Allows a caretaker to select a room number and log a verbal complaint on behalf of a tenant.  
- [ ]  Adds the complaint directly into the designated room's box marked with tag "Logged by Caretaker".  
- [ ] Blocks creation and displays an alert "Select a valid room number" if no room is selected (unhappy).


### US-10:Set Status to 'Buy Materials' 

Acceptance criteria:

- [ ]  Allows caretakers to update a complaint status to "Buy Materials".  
- [ ]  Automatically updates the corresponding tenant's tracker status to "Waiting for materials".  
- [ ]  Prevents setting status to "Buy Materials" without selecting at least one fixture category (unhappy).


Scenario 1: Status updated to buy materials 

```
Given Caretaker receives a ceiling fan complaint for Room 301 needing a capacitor
When the caretaker selects "Buy Materials" on the ticket action menu
Then the complaint status updates to "Buy Materials" and the tenant's tracker displays "Waiting for materials"
```

Scenario 2: Missing fixture category on material status update 

```
Given a complaint ticket has an uncategorized fixture type
When the caretaker attempts to select "Buy Materials"
Then the system prompts "Please specify fixture type before setting status to Buy Materials"
```

### 

### US-11: Access Repairman Contact List and Mark ‘Repairman reached’’

Acceptance criteria:

- [ ] Displays a technician directory with contact phone numbers and repair specialties (Plumbing, Electrical, General Maintenance).  
- [ ] Includes a "Repairman reached" status update button on each open complaint card.  
- [ ]  Displays an alert "No repairman contact selected" if marked reached without picking a contact (unhappy).

### US-12: Assign Visit Date and Time to Complaint 

Acceptance criteria:

- [ ] Provides date picker and time input fields on the complaint management card for caretakers.  
- [ ] Updates the tenant's tracker to display the exact assigned visit date and time window.  
- [ ] Prevents selecting past dates/times and displays an error "Visit date cannot be in the past" (unhappy).


Scenario 1: Valid visit schedule assigned 

```
Given Caretaker agrees with Uncle Teteng on a visit for Nov 15 at 10:00 AM
When the caretaker enters "2026-11-15" and "10:00 AM" into the Room 102 ticket and saves
Then the complaint status updates to "Scheduled" and shows "Estimated Repair: Nov 15 at 10:00 AM" to the tenant
```

Scenario 2: Past visit date assigned

```
Given current date is Nov 11, 2026 
When the caretaker enters "2026-11-09" as the visit date for a complaint 
Then the system blocks saving and displays "Visit date cannot be in the past" 
```

### US-13: Mark Repair ‘Ongoing’

Acceptance criteria:

- [ ] Provides a one-click "Mark Ongoing" button visible when a ticket is in "Scheduled" state.  
- [ ] Changes ticket status to "Ongoing" and updates the tenant's tracker in real time.  
- [ ] Displays a confirmation modal if clicked before the scheduled date/time window (unhappy).

### US-14: Mark ‘Repair Complete’’

Acceptance criteria:

- [ ] Allows the caretaker to update ticket status to "Repair complete".  
- [ ] Prompts the tenant screen to show "Please verify and mark resolved".  
- [ ] Retains the complaint in the caretaker's list as "Pending Verification" until the tenant resolves it (unhappy).

Scenario 1: Repair marked complete 

```
Given the repairman has finished installing the ceiling fan in Room 301
When the caretaker selects "Mark Repair Complete"
Then the status updates to "Repair complete" and prompts the tenant to verify
```

Scenario 2: Complete repair pending tenant verification 

```
Given the caretaker marked Room 301 as "Repair complete"
When the caretaker views the room list before the tenant responds
Then the card shows status "Pending Verification" and prevents archiving 
```

### US-15: Owner View Complaint Statuses 

Acceptance criteria:

- [ ] Provides a read-only landlord dashboard displaying overall summary statistics (Total Open, Waiting for Materials, Completed).  
- [ ] Displays complaints specifically flagged as "Waiting for materials" with duration counter.  
- [ ] Restricts landlord view from modifying or deleting complaint entries directly (unhappy).

### 

## 5\. Quality Requirements and Constraints (EARS)

| ID | Requirement | EARS pattern | Type | Source | Number agreed with |
| :---- | :---- | :---- | :---- | :---- | :---- |
| NFR-01 | While the mobile device is offline, the AyoNa app shall display the last-loaded room complaint list and show a visible "Offline Mode" status banner.  | \[State-driven\] | Quality | \[F8,F9, A2\]  | \[C1, C2\] |
| NFR-02 | When a caretaker updates a repair status (e.g., "Repairman reached"), the system shall update the tenant's status tracker within 2.0 seconds over a 3G mobile network connection.  | \[Event-driven\] | Quality | \[F8, F9\] | \[T1\] |
| NFR-03 | The system shall display all room status boxes, complaint forms, and progress steppers responsively on mobile browsers with screen widths from 360px to 430px without horizontal scrolling.  | \[Ubiquitous\] | Quality | \[F1,F13, A2\] | Team Consensus   |
| NFR-04 | If an image attachment exceeds 5 MB during report submission, then the system shall reject the upload and notify the user to select a smaller image.  | Unwanted behavior  | Quality  | \[F15\] | System Constraint |

## 6\. Use Case

### Use-case diagram : 

### \!\[Use-case diagram\](backlog-images/use-case-diagram.png) 

### UC-01: Processing and Updating a Repair Request

| Field | Description |
| :---- | :---- |
| Primary actor | Caretaker |
| Precondition | Caretaker is signed in and at least one active room complaint is active in the shared queue. |
| Main success scenario | 1\. Caretaker views the shared room screen (US-07) and selects the oldest open room complaint (US-08). 2\. Caretaker reviews the fault details and attached image (US-03). 3\. If parts are required, Caretaker updates status to "Buy Materials" (US-10). 4\. Caretaker selects a technician from the contact directory and contacts them via phone (US-11). 5\. Caretaker updates status to "Repairman reached" and inputs the agreed visit date and time (US-12). 6\. Caretaker marks ticket "Ongoing" when technician arrives (US-13). 7\. Caretaker marks ticket "Repair complete" upon finish (US-14), sending verification prompt to tenant. |
| Extensions | 3a. Material purchase is delayed by owner:  1\. Complaint remains in "Waiting for materials" status. 2\. Owner views the pending purchase on the landlord dashboard (US-15) and buys parts. 5a. Repairman cancels visit time: 1\. Caretaker re-opens visit schedule dialog. 2\. Caretaker enters updated date/time window (US-12), which updates tenant tracker. |
| Postcondition | Ticket status becomes "Repair complete", room box changes state, and tenant is prompted to mark resolved (US-06).  |
| Stories covered | \[US-07, US-08, US-10, US-11, US-12, US-13, US-14\]  |

## 7\. Story Map

|  | 1\. Report a problem  | 2\. Notice the complaint  | 3\. Arrange the repair  | 4\. Do the repair  | 5\. Follow and close  |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Release 1 (MVP)** | US-01 Report a broken item; US-03 Comment and image | US-07 Room boxes, open ones red | US-10 Buy materials; US-12 Visit date and time | US-14 Mark complete | US-05 Step tracker; US-04 Report history; US-06 Mark resolved |
| **Release 2** | US-02 Complaint type | US-08 Sort oldest first | US-11 Repairman reached | US-13 Mark ongoing |  |
| **Later** | US-09 Log in-person complaint |  |  |  | US-15 Owner view |

## 8\. The Ordered Backlog

| Rank | Story | MoSCoW | Size (S/M/L) | Value / effort quadrant | Sprint |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | US-01 Report Broken Item from Device | Must  | M | Big bet  | Sprint 1 |
| 2 | US-07 View Shared Room Queue | Must  | M  | Big bet  | Sprint 1 |
| 3 | US-10 Set Status to 'Buy Materials'  | Must  | S | Quick win | Sprint 1 |
| 4 | US-12 Assign Visit Date and Time to Complaint | Must | S | Quick win | Sprint 1 |
| 5 | US-14 Mark ‘Repair Complete’’ | Must | S | Quick win | Sprint 1 |
| 6 | US-05 Track Step-by-Step Status | Must | M | Big bet | Sprint 2 |
| 7 | US-04 View Tenant Report History | Must | S | Quick win | Sprint 2 |
| 8 | US-06 Mark ‘Repair Resolved’ by Tenant | Must | S | Quick win | Sprint 2 |
| 9 | US-03 Add Comment and Image to Report | Must | M | Big bet | Sprint 2 |
| 10 | US-13 Mark Repair ‘Ongoing’ | Should | S | Filler | Sprint 2 |
| 11 | US-11 Access Repairman Contact List and Mark ‘Repairman reached’’ | Should | M | Filler | Sprint 2 |
| 12 | US-02 Select Complaint Type | Should | S | Filler | Later |
| 13 | US-08 Sort Complaints Oldest First | Should | S | Filler | Later |
| 14 | US-09 Log In-Person Complaint | Could | S | Filler | Later |
| 15 | US-15 Owner View Complaint Statuses | Won’t | M | Big bet | Not this time |

### How we ordered it

The top eight stories form one complete path: a tenant reports (US-01), the caretaker sees it in the room boxes (US-07), moves it through the buy, schedule, and complete steps (US-10, US-12, US-14), and the tenant finds the report in their history, follows its tracker, and closes it (US-04, US-05, US-06). These answer what we heard most: complaints lost between caretakers (F1, F2) and tenants getting no updates (F8, F11). US-01 and US-07 come first because everything else depends on complaints existing and being visible. US-10, US-12, and US-14 come before US-05 because the tracker has nothing to show until caretakers can set statuses, and they also let us test early our biggest risk, whether caretakers will keep statuses updated (A3). US-15 is Won't this time because it is outside our five proposal capabilities and we have not yet interviewed the owner (A1), so it is kept in the backlog to revisit after that interview. 

### Capacity check

| Question | Answer |
| :---- | :---- |
| How many Must-have stories, and their total size? | 8 stories: 3 M and 5 S. |
| Do the Must-haves fit in about 60% of our time for two sprints? | Yes. Most Musts are S, and the 3 M stories are split across the two sprints. |
| Do the Release 1 stories form one complete path through the core workflow? | Yes. Release 1 has a story under all five journey steps. |
| Are all L-sized Must-have stories split? | Not applicable. None of our Must-have stories is sized L. |

## 9\. Definition of Done

- [ ] The code is reviewed by at least one other team member in a pull request, then merged into the main branch.  
- [ ] The tests pass.  
- [ ] The feature works on a phone-sized screen in a mobile browser.  
- [ ] The README is updated if the story changes how the app is set up or used.

## 10\. Traceability Table

| Story | Problem or goal it addresses | Source finding(s) | Test cases (Week 9\) |
| :---- | :---- | :---- | :---- |
| US-01 (Report Broken Item from Device )  | Tenants need to report problems even when no caretaker is available.  | F10 |  |
| US-07 (View Shared Room Queue)  | Both caretakers need to see the same open complaints when shifts change.  | F1, F2, F13  |  |
| US-10 (Set Status to 'Buy Materials')  | Tenants need to know when a repair is waiting for parts.  | F11, F14  |  |
| US-12 (Assign Visit Date and Time to Complaint)  | Tenants need to know when to expect the repair visit.  | F7  |  |
| US-14 (Mark ‘Repair Complete’’)  | Caretakers need to record that the work is finished so the tenant can check it.  | F1, F3  |  |
| US-05 (Track Step-by-Step Status)  | Tenants need to see what has happened so far and when a visit is expected.  | F3, F7, F8, F11  |  |
| US-04 (View Tenant Report History)  | Tenants need to find their past and current complaints without asking a caretaker.  | F8  |  |
| US-06 (Mark ‘Repair Resolved’ by Tenant)  | Tenants need to check that the fixture works before closing the complaint.  | F2, F3  |  |
| US-03 (Add Comment and Image to Report)  | Caretakers need to know what is broken and what to buy before going to the room.  | F15  |  |

Gaps found: Caretakers still have to pass on verbal complaints outside the app until US-09 is built. US-05 also cites F17, which has no entry in Section 2\. The table lists the existing findings that support the tracker.

## 11\. Validation

### Team review

| Problem found | Story or requirement | How we fixed it |
| :---- | :---- | :---- |
| **A valid report can get stuck at “Buy materials.”**  US-01 accepts a report with just a description, but US-10 requires a fixture type before the caretaker can update it. Section 8 schedules the fixture type picker for later.  | US-01, US-02, US-10  | Let the caretaker select “Buy materials” without a fixture type. Test that the tenant sees “Waiting for materials” after the update.  |
| **The example clears the highlight for the wrong room.**  US-06 closes a complaint in Room 20 but clears the highlight for Room 204\. US-07 also says a room stays red while it has any open complaint.  | US-06, US-07  | Test with two open complaints in Room 20\. Closing the first should keep Room 20 red. Closing the last should clear its highlight. Both actions should leave Room 204’s highlight as it was.  |
| **The room list has no rule for a failed first load.**  NFR-01 says to show the last saved list when offline, but the draft leaves out what caretakers see if they have never loaded the list before.  | US-07, NFR-01  | If the app is offline and has no saved list, show “Couldn’t load complaints” and a Retry button. Test this by opening the room list for the first time while offline.  |

### Stakeholder walk-through

\[Show the story map and the top of the backlog to at least one stakeholder you interviewed. See Week 4, slide 31.\]

| Stakeholder | Date | What they said | What we changed |
| :---- | :---- | :---- | :---- |
| T1, Tenant (3rd-year student) | 2026-11-11 | "Nindot kung apil sa una nga release ang pwede maka comment and send ug image." (It would be nice if the feature where we can comment and send an image is included in the first release.) | Moved US-03 (comment and image) from Release 2 to Release 1 in Section 7, and from Should to Must in Section 8 (rank 11 to rank 9, still Sprint 2). Updated the Section 8 capacity check to 9 Must-have stories (4 M, 5 S) and added US-03 to the Section 10 traceability table. |

## 12\. Open Questions for Sprint 1

1. If a repair visit is canceled and there is no new date yet, what should the tenant see?   
2. If the caretaker marks a repair complete but the fixture still does not work, how should the tenant send the complaint back?  
3. If one caretaker changes the visit time while another has the same complaint open, what should happen when the second caretaker tries to save an update?

## 13\. Member Contribution Record

| Member | Interviews or analysis | Stories, criteria, or use case | Review or validation |
| :---- | :---- | :---- | :---- |
| Adeva, Calvyn Kent | Led the Section 11 validation review: analyzed the backlog for problems that could be synthesized across stories and requirements, and analyzed the Section 10 traceability table for the problem or goal each story addresses. | Drafted Sections 10, 11, and 12: the traceability table and its gaps; the team review of three problems with fixes and tests, plus the T1 walk-through; and three open questions for Sprint 1\. | Reviewed the story map and ordered backlog (Sections 7 and 8), and the interview summary, needs table, and user stories (Sections 1, 2, and 3). |
| Mendoza, Obrenah Z. | Conducted interviews with Caretakers C1, C2 and Tenant T2.  | Drafted acceptance criteria and Given–When–Then scenarios for must-have stories  (US-01,US-03,US-04,US-05,US-06,US-07, US–10,US-10,US-12,US-14)) in Section 4 and drafted Use Case for Section 6.. | Refined Given-When-Then scenarios and Story map  (Sections 4 and 7\) to align strictly with Must-have priorities and changes after stakeholder walk through (Section 11).  |
| Canonigo, James Ralf P. | Did not conduct interviews. Analyzed the findings and assumptions to decide the backlog order: MoSCoW labels, S/M/L sizes, value/effort quadrants, and sprints, and checked the Must-haves against the 60% rule. | Drafted Section 7 (Story Map), Section 8 (Ordered Backlog, including how we ordered it and the capacity check), and Section 9 (Definition of Done). | Checked my drafts of Sections 7, 8, and 9 against the Week 4 slides (MoSCoW, value versus effort, acceptance criteria versus Definition of Done) and revised them: used the slides' quadrant names, added a Won't story, and rewrote the Definition of Done so it did not repeat acceptance criteria. |
| Azur, Kurt Renzo H. | Analyzed the interview log to draft Section 1 (interview summary with role codes) and Section 2 (findings F1–F16 and the assumption log). Matched the findings and stories to the project proposal’s scope and the screen designs from the last team meeting. | Drafted the Team Information table and Section 3: user stories US-01 to US-15, the epics and how they were split, and the “Stories we rewrote” examples. | Checked the drafts of Sections 1–3 against the team’s meeting notes, the project proposal, and the interview log, and corrected the errors found. |

## 14\. References

None

## 15\. Team AI Use Declaration

Select one option:

- [ ] No generative AI tools were used by any member in preparing this submission.  
- [x] One or more members used generative AI tools. Details are provided below.

| Member who used AI | Tool | Purpose and sections assisted | How output was checked or revised |
| :---- | :---- | :---- | :---- |
| Adeva, Calvyn Kent | ChatGPT 6.1 Sol (High) | Checked whether the problems found in the Section 11 validation were prevalent and among the most pressing or largest. Seven were found and narrowed to three. | Compared Sol's answers against the story and criteria text (Sections 3, 4, 5, 8\) and the findings in Section 2 and the interview log. Kept only problems the text showed. AI was not used to decide how to fix them. |
| Mendoza,Obrenah Z. | Gemini | Used to structure acceptance criteria with scenarios (Section 4), and writing quality requirements (Section 5). | Manually reviewed all generated scenarios against actual interview findings (C1, C2, T1, T2), formatted scenario titles and confirmed non-functional requirements aligned with our system limits.   |
| Canonigo, James Ralf P. | Claude Sonnet 5.5 (Medium) | Used Claude as an assisting tool to help organize ideas, improve wording, and clarify some concepts while drafting Sections 7 (Story Map), 8 (Ordered Backlog), and 9 (Definition of Done). The actual analysis, prioritization, backlog ordering, story sizing, value/effort assessment, and sprint planning were done manually based on the group's findings and assumptions. | Reviewed and revised the AI-assisted suggestions manually by comparing them with the Week 4 slides. Checked the MoSCoW prioritization, S/M/L sizes, value/effort quadrants, and the 60% capacity rule. Also made corrections by using the proper quadrant names, adding a Won't story, and revising the Definition of Done to avoid repeating the acceptance criteria. |
| Azur, Kurt Renzo H. | Claude Opus 5.5 (High) | Used Claude as an assisting tool to draft the Team Information table and Sections 1 (Interview Summary), 2 (From Interview Notes to Needs and the Assumption log), and 3 (User Stories, Epics, and Stories we rewrote). Claude worked from the team’s interview log, the Week 3 and Week 4 slides, the project proposal, and the notes from the last team meeting. It coded the interviews by role, replaced names with roles, drafted the findings (F1–F16) and assumptions, and drafted the user stories, epics, and rewrite examples. The interviews themselves and the screen designs in the meeting notes came from the team. | Reviewed the drafts manually by comparing them with the team’s meeting notes and earlier project submissions (the project proposal and the interview log). Errors found were corrected b personally. |

### Main prompts or interaction summary

Calvyn Kent L. Adeva: Used ChatGPT 6.1 Sol on High to check whether the problems found in the Section 11 validation were truly prevalent and among the most pressing or largest to address. Calvyn found seven candidate problems and narrowed them to three (the "Buy materials" dead end, the wrong-room highlight, and the failed first load). Sol's answers were compared against the story and criteria text in Sections 3, 4, 5, and 8 and traced to the findings in Section 2 and the interview log, and a problem was kept only if the text showed it. No AI was used to identify how to fix the problems.

Obrenah Z. Mendoza: Used Gemini to convert interview findings into testable Given–When–Then scenarios (happy and unhappy paths) for Must-have stories. The tool was also used to structure EARS pattern quality requirements. Outputs were checked to ensure no fabricated findings were introduced and that all test criteria remained concrete. 

James Ralf P. Canonigo: to help clarify concepts, organize ideas, and review the drafts of Sections 7 (Story Map), 8 (Ordered Backlog), and 9 (Definition of Done). I provided the group's findings, assumptions, and initial analysis as the basis for the work. AI assistance was mainly used to check the clarity and structure of the sections and to help verify whether the prioritization approach was consistent with the Week 4 lecture slides.

Kurt Renzo H. Azur: Used Claude Opus 5.5 to draft the Team Information table and Sections 1–3. He gave it the team’s interview log, the Week 3 and Week 4 lecture slides, the project proposal, and the notes from the team’s last meeting. Kurt coded the interviews by role (C1, C2, T1, T2) and replaced the names in the notes with roles. Claude turned the interview answers into the needs table drafts (F1–F16) and the assumption log, then also drafted 15 user stories, the epics, and the “Stories we rewrote” examples, then revised the stories and requirement ideas to match the proposal’s scope and the draft screens in the meeting notes. Kurt checked the output against the team’s meeting notes and earlier project submissions, and corrected the errors he found himself. Every finding in Section 2 and 3 traces back to an answer in the interview log.

We acknowledge that AI-generated suggestions are not evidence of actual stakeholder interviews, feedback, or verified user needs. Every finding in Section 2 and every walk-through in Section 11 comes from a real person we spoke to or observed. We remain responsible for the accuracy and explainability of this submission.

## 16\. Team Confirmation

We confirm that this document reflects our team's agreed-upon product backlog. All members listed below reviewed the final version, and each member will upload the same Markdown file to their personal CSC181 repository.

| Member | Reviewed final version |
| :---- | :---- |
| Calvyn Kent L. Adeva | Yes |
| James Ralf P. Canonigo | Yes |
| Obrenah Z. Mendoza | Yes |
| Kurt Renzo H. Azur | Yes |

## Submission Checklist

- [x] Interviews cover at least two stakeholder groups, with sources coded and no personal information.  
- [x] The needs table has at least 8 findings, each labelled F, Q, or C.  
- [x] Assumptions are recorded separately from evidence.  
- [x] There are 10 to 15 user stories, each with a real role, a "so that", and at least one finding.  
- [x] Epics are split, and at least two rewrites are recorded.  
- [x] Every story has at least 3 acceptance criteria, including an unhappy path, with no weak words.  
- [x] Every Must-have story has at least 2 Given–When–Then scenarios.  
- [x] At least 3 quality requirements or constraints use EARS patterns.  
- [x] One use case has a diagram, a main success scenario, and at least 2 extensions.  
- [x] The story map has a Release 1 line that crosses every journey step.  
- [x] Every story has a MoSCoW label and a size, and the backlog is in one order with no ties.  
- [x] Must-haves fit in about 60% of capacity. Won't-have stories are kept, not deleted.  
- [x] A Definition of Done is included.  
- [x] The traceability table covers every Must-have story.  
- [x] The team review and the stakeholder walk-through are recorded.  
- [x] Contributions, references, and AI use are declared.  
- [x] All members reviewed the same final document.  
- [x] Each member saved the file as `activities/product-backlog.md`, with images in `activities/backlog-images/`.  
- [x] Each member committed and pushed their copy to their personal repository.  
- [x] Each member submitted their own GitHub file link through MOLE before November 9, 2026 23:59:59.