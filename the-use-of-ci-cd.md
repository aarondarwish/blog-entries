# The Use of CI/CD

## The Problems of Integrating New Code

Software development is a dynamic process that involves constant 
experimentation and feedback, and the test-driven development (TDD) methodology is a pronounced example of that. In the past, team members worked on software projects separately.

It was often the case that they only sought to merge their code bases after a period that stretched to weeks at times. There were no standardized protocols for melding the various contributions.

This led to a multitude of issues related to difficulties in integration, compatibility, functionality as well as error-proofing. The engineers would work on the same segment of the product and override each other’s toil.

There was no coherence to an overarching architecture as each developer designed the system their way without the oversight of the division as a whole. 

Testing was conventionally performed by a separate team that only examined the quality assurance of the product after the development process has 
already reached a significant milestone.


## Continuous Integration and Delivery

Continuous Integration is the set of practices that steer the development process into pushing small code changes into a version control repository consistently. These small-scale snapshots get tested automatically through a well-defined pipeline.

The pipeline could utilise a scanning stage that runs the gamut from linting and static analysis to monitoring and auditing potential vulnerabilities and weaknesses.

Perhaps an API key was pushed to the repository, or an older version of a library is known to possess a bug. The monitoring system would immediately alert the developer about such a mishap. This would morph the CI/CD process from being part of DevOps into the more 
encompassing DevSecOps.

Eventually, the Continuous Delivery process entails releasing the product into a staging environment or pre-production build. Which is also done at a frequent rate that exactly matches the integration throughput.

Finally, after a series of comprehensive tests the software product is ready to be launched at the production level. The full chain of testing and packaging is entirely automated, which altogether forms the core of the agile release train.


## Upsides of CI/CD

CI/CD comes with a plethora of advantageous business and software development perks.

The quality of the code will upsurge. Since a more thorough examination approach is undertaken for distinctly small changes.

The testing cycles are shorter since the complexity and volume of 
the code that needs to be tested are smaller. A full-fledged 
investigation of the functionality of the program is not necessary when each segment of the code has been evaluated already.

A more responsive development environment. As the development 
operation of your organization takes a real-time approach where the business needs are rapidly catered for.

It is easier to pinpoint the source of an error when each change that could cause breakage during rollout is monitored. By the same token, it is easier to roll back to a previous state if a specific alteration caused an issue.


## Downsides of CI/CD

There are disadvantages to the CI/CD approach that one must be aware of.

Continuous change can displease the end-user especially if the UX changes suddenly and without prior communication. An example of that is a reshaped menu bar and the renaming of its items. Or deprecating a feature that a user was still dependent on.

Your customer support team might struggle to keep up with the pace 
of changes that occur with your product development. Thereby impeding their capacity to assist your clients with their inquiries, as they are yet to familiarize themselves with the new sudden changes.

Technical problems could arise if your infrastructure is modularized. As in the case with microservices. A new change in a particular software process might not interoperate effectively with the rest of the services chain.

Managing resources astutely is a must. A sudden change might demand significantly more resources than was originally anticipated. 
Perhaps more processing power, memory capacity or network bandwidth is required.

A noteworthy level of monitoring is essential throughout the CI/CD process. As you need to address potential problems promptly and keep close tabs on customer feedback.
