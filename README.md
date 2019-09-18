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

### Step 3: Flock "Securitas" (WIP)

The [Flock Securitas Organization](https://mainnet.aragon.org/#/securitas) is a [Membership](https://help.aragon.org/article/34-create-a-new-membership-organization) Aragon Organization.

Members are the Aragon Association and Flock teams.

At any time, the Aragon Association makes sure that the Securitas Org is funded with enough DAI to pay for a sizable audit (approx. DAI30K).

Decisions in the Securitas Org are consent based. Any member can object against a decision and block it.

When under review by the Securitas Org, audit requests will move from the ["AA Prioritization / Review"](https://github.com/aragon/security-review/projects/1#column-5283999) column to the ["Security DAO Voting"](https://github.com/aragon/security-review/projects/1#column-5284002) column and have a corresponding vote posted to the security DAO.

### Step 4: External Review

If an audit request is approved by the Securitas Org, it is moved from the ["Security DAO Voting"](https://github.com/aragon/security-review/projects/1#column-5284002) column to the ["External Review"](https://github.com/aragon/security-review/projects/1#column-5284006) column.

Following the external security review, requests are considered complete and will have their issues closed.

### Holding: Deprioritized

At any time, the Aragon Association may move a request to the ["Deprioritized"](https://github.com/aragon/security-review/projects/1#column-5284000) column to signal that the request has been deprioritized in its eyes.

### Misc.

Any time a request's status changes or more information is required, the Aragon Association will provide feedback in the form of comments in the issue specifying the request's SES.
