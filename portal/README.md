# Portal manifest notes

- `candidate.yml` is the live enrolment manifest for the Q4 sync batch.
- When the sync job builds the candidate card it reads the `profile` block.
- The manifest list header uses the top-level `candidate` label.
- `data/registrants.yml` is an archived snapshot from the previous portal and is
  not read by the current sync job.
