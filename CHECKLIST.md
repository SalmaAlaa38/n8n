# Progress Checklist

Tick an exercise after I have tried it, brought back the result, and reviewed it with the mentor. Tick a milestone review after I show the working result and explain the concept in my own words. The instructions and progress log are in [PROJECT.md](PROJECT.md).

## Milestone 0 — Set up the project myself

- [x] **0.1** Explain workflows, triggers, and nodes and identify the event that starts the quote workflow.
- [x] **0.2** Compare Cloud and local setup and costs. Review my choice before signing up or installing.
- [x] **0.3** Verify the project path in PowerShell, create one fake request, verify Docker is running, open n8n, and name my practice workflow.
- [x] **0.4** Predict and run the manual workflow. Compare my prediction with the execution output.
- [x] **0.5** Rename a field, find the mismatch, repair it, and show the successful rerun.
- [ ] **0.6** Set up Git, review the staged project documents and `.gitignore`, and create the first commit.
  - [x] Rename `master` to `main` and verify `On branch main` in `git status` before pushing to GitHub.
- [ ] **0.7** Choose GitHub repository visibility, push the commit, and verify the documents in GitHub.
- [x] **Optional activation** — Enter the local key under Settings → Plan & usage.
- [ ] **Optional activation check** — Verify that n8n confirms Registered Community activation.
- [ ] **Milestone 0 review** — Demo the practice workflow, explain how I found the mismatch, and show the GitHub repository with the project documents.

## Milestone 1 — Form to Google Sheets

- [ ] **1.1** Build and submit the form and inspect the output for a blank optional field.
- [ ] **1.2** Create the test sheet and verify that n8n can access it.
- [ ] **1.3** Map the fields and verify that one submission adds the expected row.
- [ ] **1.4** Check the form URL mode and trace a second submission with a different field left blank.
- [ ] **Milestone 1 review** — Show one fresh submission and one matching row. Explain the field mapping.

## Milestone 2 — Google Sheets to Gmail draft

- [ ] **2.1** Define the details needed for a quote and write complete and incomplete test cases.
- [ ] **2.2** Verify the missing-details rule for complete, blank, and whitespace-only values.
- [ ] **2.3** Connect my test inbox, inspect the follow-up draft, and check Sent.
- [ ] **2.4** Run the complete and incomplete cases end to end and compare both outcomes.
- [ ] **Milestone 2 review** — Show the two branches and explain the owner's decisions.

## Milestone 3 — Add AI and test failures

- [ ] **3.1** Extract structured details from fictional notes and compare them with expectations.
- [ ] **3.2** Verify that ambiguity, conflicts, and extraction failures reach owner review.
- [ ] **3.3** Replay the same request ID and verify one row and one draft. Test overlap or demonstrate the single-operator recovery path.
- [ ] **3.4** Recover from a draft failure after saving the row, including the case where a draft may already exist.
- [ ] **Milestone 3 review** — Show review and recovery outcomes and explain when to check Gmail before retrying.

## Milestone 4 — Prepare a paid pilot

- [ ] **4.1** Export, sanitize, and re-import the workflow.
- [ ] **4.2** Write and follow the setup instructions from a fresh import.
- [ ] **4.3** Test a written, try-it-yourself demo with fictional data.
- [ ] **4.4** Interview five cleaning business owners and summarize what I learned.
- [ ] **4.5** Write a fixed-scope $100 USD pilot offer and check the deployment terms.
- [ ] **4.6** Rehearse the time measurement and define the pilot target.
- [ ] **Milestone 4 review** — Demo to a potential customer, explain the flow, fix a common failure, and set it up again myself. Show the interview findings, the offer, and the measurement plan.
