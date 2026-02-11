# Compliance Manager User Journey

**Document Type**: User Journey  
**Persona**: Compliance Manager  
**System**: Regulatory Tracker  
**Last Updated**: February 2025

---

## Overview

This document outlines the complete user journey for a **Compliance Manager** using the Regulatory Tracker system. As a manager overseeing the compliance process and reviewing team work, you are responsible for ensuring regulatory changes are identified, analyzed, and addressed in a timely manner.

The Regulatory Tracker helps you stay ahead of regulatory changes from sources like FinCEN, OCC, and the Federal Reserve by automatically scanning for updates, analyzing their impact using AI, and generating professional documentation for your records.

---

## Persona Profile

**Role**: Compliance Manager  
**Responsibilities**:
- Oversee the regulatory compliance monitoring process
- Review and approve team members' work on compliance items
- Ensure timely response to regulatory changes
- Maintain audit-ready documentation
- Report compliance status to leadership

**Goals**:
- Stay informed of all regulatory changes affecting the organization
- Efficiently review AI-generated analysis and team assessments
- Ensure no regulatory changes fall through the cracks
- Maintain a clear audit trail of compliance activities

**Pain Points Addressed**:
- Manual monitoring of multiple regulatory sources is time-consuming
- Difficulty assessing which changes require immediate attention
- Inconsistent documentation across team members
- Lack of visibility into team progress on compliance items

---

## Journey Map

### Phase 1: Daily Dashboard Review

#### Entry Point
The manager logs into the Regulatory Tracker and lands on the **Dashboard**.

#### What You See
- **Recent Scan Activity**: Overview of the latest regulatory scans and their status
- **Pending Items**: Compliance items awaiting review or action
- **Status Summary**: Visual breakdown of items by workflow status (New, In Review, Approved, Archived)
- **Source Coverage**: Confirmation that all regulatory sources are being monitored

#### Actions Available
| Action | Purpose |
|--------|---------|
| View scan history | See all past scans and their outcomes |
| Filter by status | Focus on items needing attention |
| Drill into results | Examine individual regulatory changes |

#### Manager Mindset
> "What happened overnight? Are there any urgent regulatory changes I need to know about? Is my team making progress on open items?"

---

### Phase 2: Initiating a Regulatory Scan

#### When This Happens
- On a scheduled basis (daily/weekly)
- When notified of potential regulatory activity
- Ad-hoc when preparing for audits or reviews

#### Step-by-Step Flow

1. **Navigate to Scans Section**
   - Select "Scans" from the main navigation

2. **Initiate New Scan**
   - Click "Start New Scan" button
   - System begins scanning all configured regulatory sources

3. **Monitor Scan Progress**
   - View real-time status updates as the scan progresses through stages:
     - *Initializing* → Setting up the scan
     - *Retrieving Sources* → Pulling latest documents from regulatory agencies
     - *Detecting Changes* → Comparing against previous versions
     - *Analyzing* → AI review of detected changes
     - *Scoring* → Calculating impact and confidence levels
     - *Generating Artifacts* → Creating documentation
     - *Finalizing* → Completing the scan

4. **Review Scan Summary**
   - See total sources scanned
   - View number of changes detected
   - Access list of new results requiring review

#### What Happens Behind the Scenes
The system uses intelligent change detection to identify meaningful regulatory updates, filtering out minor formatting changes and focusing on material modifications that require compliance attention.

---

### Phase 3: Reviewing AI Analysis Results

#### Accessing Results
From the dashboard or scan summary, navigate to the **Results** section to see all detected regulatory changes.

#### Understanding the Analysis

Each result includes AI-generated analysis with the following components:

| Component | Description | How Managers Use It |
|-----------|-------------|---------------------|
| **Impact Assessment** | Plain-language summary of how the change affects your organization | Quickly understand the "so what" of each change |
| **Confidence Score** | AI's confidence level in its analysis (percentage) | Prioritize review of lower-confidence items |
| **Recommended Actions** | Suggested next steps for addressing the change | Guide team assignments and timelines |
| **Source Details** | Original regulatory source and document reference | Verify and cross-reference as needed |

#### Reviewing Individual Results

1. **Select a Result** from the list
2. **Read the Impact Summary** - Start with the high-level assessment
3. **Check the Confidence Score**:
   - *High confidence (80%+)*: AI analysis is likely accurate; quick review may suffice
   - *Medium confidence (50-79%)*: Warrants closer examination
   - *Low confidence (<50%)*: Requires thorough manual review
4. **Review Recommended Actions** - Consider whether they align with your compliance approach
5. **Update Workflow Status** - Move the item through your review process

#### Filtering and Prioritization

Use filters to focus your review:
- **By Source**: FinCEN, OCC, Federal Reserve, etc.
- **By Status**: New, In Review, Approved, Archived
- **By Impact Level**: High, Medium, Low
- **By Confidence**: Focus on items needing more scrutiny

---

### Phase 4: Managing Workflow Status

#### Workflow Stages

The Regulatory Tracker uses a clear workflow to track each compliance item:

```
┌─────────┐    ┌───────────┐    ┌──────────┐    ┌──────────┐
│   New   │ →  │ In Review │ →  │ Approved │ →  │ Archived │
└─────────┘    └───────────┘    └──────────┘    └──────────┘
```

| Status | Meaning | Manager Action |
|--------|---------|----------------|
| **New** | Freshly detected change, not yet reviewed | Assign for review or begin review |
| **In Review** | Currently being assessed by team | Monitor progress, provide guidance |
| **Approved** | Analysis verified, actions determined | Ensure actions are being executed |
| **Archived** | Completed and documented for records | Available for audit reference |

#### Updating Status

1. Open the result you want to update
2. Select the new status from the workflow dropdown
3. Add any notes or comments for your team
4. Save changes

#### Team Oversight View

As a manager, you can see:
- Who is working on which items
- How long items have been in each status
- Items that may be stuck or overdue
- Overall team velocity on compliance work

---

### Phase 5: Reviewing Generated Documentation

#### Available Artifacts

For each analyzed regulatory change, the system generates professional documentation:

**1. Markdown Summary**
- Stored in the system for quick reference
- Easy to read and search
- Includes all analysis details

**2. Word Document (.docx)**
- Professional formatting with cover page
- Table of contents for easy navigation
- Suitable for sharing with leadership or auditors
- Includes:
  - Executive summary
  - Detailed analysis
  - Recommended actions
  - Source references

#### Accessing Documents

1. Navigate to the result you want to document
2. Click "View Artifacts" or "Download Report"
3. Choose format (view in browser or download Word doc)

#### Using Documents for Reporting

These generated documents are designed to be audit-ready and can be used for:
- Board and leadership reporting
- Regulatory examination preparation
- Internal audit documentation
- Compliance committee meetings

---

### Phase 6: Ongoing Monitoring and Reporting

#### Regular Cadence (Suggested)

| Frequency | Activity |
|-----------|----------|
| **Daily** | Quick dashboard check for new items |
| **Weekly** | Review all pending items, update statuses, clear backlog |
| **Monthly** | Generate summary reports, review team performance |
| **Quarterly** | Comprehensive review, audit preparation, source coverage check |

#### Key Metrics to Track

- **Time to Review**: How quickly are new items being assessed?
- **Items by Status**: Is work flowing smoothly or getting stuck?
- **Source Coverage**: Are all required regulatory sources being monitored?
- **Confidence Trends**: Are AI assessments meeting quality standards?

#### Escalation Triggers

Consider escalating when:
- High-impact change detected with tight compliance deadline
- AI confidence is low on a potentially significant change
- Multiple changes from the same source indicate major regulatory shift
- Items are stuck in "In Review" beyond expected timeframes

---

## Quick Reference: Manager Workflows at a Glance

### Morning Check-in (5-10 minutes)
1. Open Dashboard
2. Review any overnight scan results
3. Check for new high-priority items
4. Verify no items are overdue

### Weekly Review (30-45 minutes)
1. Review all items in "New" status
2. Check progress on "In Review" items
3. Approve completed analyses
4. Archive resolved items
5. Generate status report if needed

### New Scan Review (15-30 minutes)
1. Initiate scan (if not automated)
2. Review scan completion summary
3. Triage new results by impact and confidence
4. Assign items to team or self-review
5. Update workflow statuses

### Audit Preparation (1-2 hours)
1. Filter to relevant date range
2. Export documentation for all completed items
3. Review archived items for completeness
4. Generate summary report
5. Verify all sources were covered

---

## Tips for Success

**Leverage the AI Confidence Scores**  
Use confidence scores to allocate your review time wisely. High-confidence analyses may need just a quick verification, while lower-confidence items deserve more thorough examination.

**Keep Workflow Statuses Current**  
Accurate status tracking helps you maintain visibility across your team and ensures nothing falls through the cracks. Encourage team members to update statuses promptly.

**Use Generated Documents**  
The auto-generated Word documents save significant time when preparing for audits or leadership reporting. They maintain consistent formatting and include all required details.

**Set Up a Regular Rhythm**  
Regulatory monitoring is most effective when it's consistent. Establish a daily, weekly, and monthly cadence that works for your team.

**Trust but Verify**  
The AI analysis is a powerful starting point, but your expertise and judgment remain essential. Use the AI insights to accelerate your work, not replace your review.

---

## Summary

As a Compliance Manager using the Regulatory Tracker, your journey spans six key phases:

1. **Dashboard Review** - Stay informed of overall compliance status
2. **Scan Management** - Initiate and monitor regulatory source scans
3. **Analysis Review** - Examine AI-generated impact assessments
4. **Workflow Management** - Track items through the compliance process
5. **Documentation** - Access and share professional reports
6. **Ongoing Monitoring** - Maintain a consistent review cadence

The system is designed to surface the most important information quickly, automate documentation, and give you clear visibility into your team's compliance work—so you can focus on what matters most: keeping your organization compliant.