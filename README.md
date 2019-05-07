# Aragon Association Security Review Pipeline

See [Github project](https://github.com/aragon/security-review/projects/1) for up-to-date information regarding any potential security requests by Flock / Nest teams from external auditors.

## The Request for Security Review (RFSR) Process

### Step 1: Flock teams submit Security Executive Summaries (SES)

Flock teams will communicate their security needs for a given quarter, by submitting issues with the SES to this repo.

The main things specified in an SES:

  - The components to be audited (contracts, apps…)
  - Some documentation and links to the different components for auditors to evaluate the workload
  - An estimation of the priority of each component with a quick explanation of the stakes

### Step 2: Aragon Association Prioritization

At this step, the Aragon Association will review SESs and ask questions in order to establish a prioritized pipeline of all components to be audited.

Requests will be moved from the ["New Requests"](https://github.com/aragon/security-review/projects/1#column-5283994) column to the ["AA Prioritization / Review"](https://github.com/aragon/security-review/projects/1#column-5283999) column.

Before proceeding to the next step, the Aragon Association may request an intra-Network audit of an request to gain better clarity over the request's readiness and maturity for (more costly) external review.

### Step 3: Flock Security DAO (TBD: medium term)

An idea was brought up to create a 1-person, 1-vote DAO including team leaders and lead developers from each Flock team (members TBD).

This DAO could be supplied with funds, corresponding to the Network's security budget for a given quarter, and only grant the Aragon Association (or a delegate) the permission to create votes for transferring these funds.

At this stage, requests will move from the ["AA Prioritization / Review"](https://github.com/aragon/security-review/projects/1#column-5283999) column to the ["Security DAO Voting"](https://github.com/aragon/security-review/projects/1#column-5284002) column and have a corresponding vote posted to the security DAO.

### Step 4: External Review

Finally, if the voting passes, funds will be used by the Aragon Association to procure an external review for the desired request.

Requests will move from the ["Security DAO Voting"](https://github.com/aragon/security-review/projects/1#column-5284002) column to the ["External Review"](https://github.com/aragon/security-review/projects/1#column-5284006) column.

Following the external security review, requests are considered complete and will have their issues closed.

### Holding: Deprioritized

At any time, the Aragon Association may move a request to the ["Deprioritized"](https://github.com/aragon/security-review/projects/1#column-5284000) column to signal that the request has been deprioritized in its eyes.

### Misc.

Any time a request's status changes or more information is required, the Aragon Association will provide feedback in the form of comments in the issue specifying the request's SES.
