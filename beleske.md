What is CI?

Strictly speaking, CI refers to merging developer changes to the main branch often, Wikipedia even helpfully suggests: "several times a day". This is usually true but when we refer to CI in industry, we're usually talking about what happens after the actual merge happens.

Koraci na koje se racuna u CI: Lint, Build, Test, Package i Deploy.

The terms Continuous Delivery and Continuous Deployment (both of which have the acronym CD) are often used when one talks about CI that also takes care of deployments. We won't bore you with the exact definition (you can use e.g. Wikipedia or another Martin Fowler blog post) but in general, we refer to CD as the practice where the main branch is kept deployable at all times. In general, this is also frequently coupled with automated deployments triggered from merges into the main branch.

workflow - je ukupni proces, sve komande, koje okidaju automatske taskove kao sto su bilding, testing, linting, releasing deploying.

Workflow ima job-ove, jobovi imaju step-sove.

svaki workflow mora da ima bar jedan job.
