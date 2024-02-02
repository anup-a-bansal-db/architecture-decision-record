# Architecture Decision Record (ADR) template <!-- Replace with ADR title -->

This is a template for CSP  ADR.

### Submitters

List ADR submitters.

Format:

- Name (Organization)

## Status

What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?

## Change Log

List the changes to the document, incl. state, date, and PR URL.

Date is an ISO 8601 (YYYY-MM-DD) string.

PR is the pull request that submitted the change, including information such as the diff, contributors, and reviewers.

Format:

- \[Status of ADR e.g. approved, amended, etc.\]\(URL of pull request\) YYYY-MM-DD


## Referenced Use Case(s)

List all relevant use case / requirements documents.

ADR requires at least one relevant, approved use case.

Format:

- \[Use Case Name\]\(URL\)

Add explanations if the ADR is not addressing all the requirements of a use case.


## Context

Describe:

- how the design is architecturally significant - warranting an ADR (versus simple issue and PR to fix a problem)

- the high level design approach (details described in the proposed design below)


## Proposed Design

Details of the design (without getting into implementation where possible).

Outline:

- services/modules to be impacted (changed)

- new services/modules to be added

- model and DTO impact (changes/additions/removals)

- API impact (changes/additions/removals)

- general configuration impact (establishment of new sections, changes/additions/removals)

- devops impact


## Considerations

Document alternatives, concerns, ancillary or related issues, questions that arose in debate of the ADR. 

Indicate if/how they were resolved or mollified.
* [option 1]
* [option 2]
* [option 3]
* … <!-- numbers of options can vary -->


## Decision

What is the change that we're proposing and/or doing?
Document any agreed upon important implementation detail, caveats, future considerations, remaining or deferred design issues.

Document any part of the requirements not satisfied by the proposed design.
Following can also be answered:-
    * Who else provided the feedback opinion?

    * What are other candidates options you considered?

    * What are you creating? 

      * Examples

        * B2B or B2C

        * external-facing or employee-only

        * desktop or mobile

        * pilot or production
        * monolith or microservices

    * How did you evaluate the candidates?

    * Why did you choose the winner?

    * What is happening since then?

      * Examples

        * How is the winner performing?

        * What % of real-world production user traffic is flowing through the winner?

        * What kinds of integrations are involved, such as with continuous delivery pipelines, content management systems, analytics and metrics, etc.?

        * Knowing what you know now, what would you advise people to do differently?


## Consequences

What becomes easier or more difficult to do because of this change?

## Other Related ADRs

List any relevant ADRs - such as a design decision for a sub-component of a feature, a design deprecated as a result of this design, etc.. 

Format:

- \[ADR Title\]\(URL\) - Relevance


## References

List additional references.

Format:

- \[Title\]\(URL\)

