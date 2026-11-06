Smart Waste System

Project Overview

The Smart Waste System is a simple Flowgorithm program prototype
designed to collect basic reports from residents about waste that needs
attention. It asks a resident for their name, location, and a
description of the waste, then checks that the required information has
been entered before proceeding.

Current Features

• Displays a welcome message.
• Collects the resident’s name.
• Collects the location of the waste.
• Collects a description of the waste.
• Checks that the name, location, and description are not empty.
• If the entries are valid, asks the user to enter a report ID.
• Sets the report status to pending.
• Displays a success message for a valid report.
• Displays an invalid-entry message if any required field is empty.

Program Workflow

1. Start the program.
2. Display the welcome message.
3. Request the resident’s name, waste location, and waste description.
4. Validate the three required entries.
5. If all entries are provided:
  • Ask the user to enter a report ID.
  • Set the report status to pending.
  • Display a report-saved confirmation and the report ID label.
6. If one or more entries are missing, display an invalid-entry
message.
7. End the program.

Variables Used

────────

Variable                Type                    Purpose

────────

residentName          String                  Stores the resident’s
name.

location              String                  Stores where the waste
is located.

wasteDescription      String                  Stores the resident’s
description of the
waste.

reportStatus          String                  Stores the report
status; currently set
to pending.

assignedTeam          String                  Stores the
collection-team
placeholder value.

collectionTeam        String                  Declared for
collection-team
information.

reportID              Integer                 Stores the report ID
entered by the user.

reportCount           Integer                 Declared for
report-count
functionality.

maxlenght             Integer                 Declared integer
variable; not currently
used.

i                     Integer                 Declared integer
variable; not currently
used.

isValid               Boolean                 Indicates whether the required text fields are non-empty.

Requirements

• A computer with Flowgorithm 4.2 or a compatible version
installed.
• The project file: PROG ASS !.fprg.

How to Run

1. Install and open Flowgorithm.
2. Open PROG ASS !.fprg.
3. Run the flowchart using Flowgorithm’s Run command.
4. Enter a resident name, location, and waste description when
prompted.
5. If all three fields contain values, enter a report ID when
requested.

Current Scope and Limitations

This file represents the current implementation in the supplied
Flowgorithm project. It is an initial prototype rather than a complete
waste-management platform.

• It processes one report during a run.
• The report ID is entered by the user; automatic ID generation is not
implemented.
• The report is not saved to a database or permanent file.
• Checking an existing report’s status and updating a report’s status
are not implemented.
• Collection-team assignment is not implemented; the current
assignment is a placeholder string.
• The declared report-count and other unused variables are reserved or
currently unused.
• The program checks for empty fields but does not currently enforce a
maximum description length.

Possible Future Improvements

• Generate unique report IDs automatically.
• Save reports so they remain available after the program closes.
• Add options to submit a report, check report status, update report
status, and exit.
• Add validation for description length and other input errors.
• Implement collection-team assignment and report tracking.
• Add a report counter and summary of submitted reports.
