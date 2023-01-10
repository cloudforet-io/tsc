# I. Overview

This policy describes the Cloudforet project life cycle process, from core services to plugins.
It describes the stages a project may be admitted under and what the criteria and expectations are for a given stage,
as well as the acceptance criteria for a project to move from one stage to another.
It also describes the Annual Review Process through which those changes will be evaluated and made.


Project progression, movement form one stage to another, allows projects to participate at the level
that is most appropriate fro them given where they are in their lifecycle.

# II. Stages - Definitions & Expectations

Cloudforet projects have a maturity level of sandbox, incubating, or graduated. Archived is for projects no longer in active development. The maturity level is a signal by Cloudforet as to what sorts of enterprises should be adopting different projects. Projects increase their maturity by demonstrating their sustainability to Cloudforet’s Technical Steering Committee: that they have adoption, a healthy rate of changes, committers from multiple organizations, have adopted the Cloudforet Code of Conduct.

![Project Stages](https://github.com/cncf/toc/blob/main/process/project-stages.png)

## Sandbox:

The Cloudforet Sandbox is the entry point for early stage projects and has four goals:

* Encourage public visibility of experiments or other early work that can add value to the Cloudforet mission and build the ingredients of a successful Incubation level project
* Facilitate alignment with existing projects if (and only if) this is desired
* Nurture projects (e.g. via Cloudforet Community Issue requests)
* Remove possible legal and governance obstacles to adoption and contribution by ensuring all projects adhere to Cloudforet legal, code of conduct and IP Policy requirements


## Incubating:
Incubating projects have access to all resources listed at https://cloudforet.io/projects/, and have a presence at Public Market Place.


## Graduated:
Graduated projects signal the highest level of maturity for a Cloudforet project.


## Archived:
Archived projects are no longer in active development and are only archived after a TOC vote.


# III. Project Proposal Process

Introduction:
This governance policy sets forth the proposal process for projects to be accepted into the Cloudforet.
The process is the same for both existing projects which seek to move into the Foundation, and new projects to be formed within the Cloudforet.

## Project Proposal Requirements:

## Sandbox Projects:

Projects being submitted to the Cloudforet at the sandbox level are intended to be the entry point for early stage projects and are not required to undergo due diligence.

Sandbox projects should be early-stage projects that the Cloudforet TOC believes warrant experimentation.

* New projects that are designed to extend one or more Cloudforet projects with functionality or interoperability libraries.
* Independent projects that fit the Cloudforet mission and provide potential for a novel approach to existing functional areas (or are an attempt to meet an unfulfilled need)
* Any project that realistically intends to join Cloudforet Incubation in future and wishes to lay the foundations for that

To apply for inclusion into the Sandbox, projects should create issue at TSC repository.
The TOC will review on a rotating basis, currently every months as of January 2023.

## Project Graduation Process: Sandbox to Incubating

Incubating projects are required to undergo due diligence as a part of the process to move from Sandbox to Incubation. Due Diligence is driven by a TOC sponsor, with two weeks for public comment before a vote is called.

Criteria:
To be accepted to incubating stage, a project must meet the sandbox stage requirements plus:

* Document that it is being used successfully in production by at least three independent adopters which, in the TOC’s judgement, are of adequate quality and scope.
* Have a healthy number of committers. A committer is defined as someone with the commit bit; i.e., someone who can accept contributions to some or all of the project.
* Demonstrate a substantial ongoing flow of commits and merged contributions.
* Since these metrics can vary significantly depending on the type, scope and size of a project, the TOC has final judgement over the level of activity that is adequate to meet these criteria
* A clear versioning scheme.
* Specifications must have at least one public reference implementation.

## (3) Project Graduation Process: Incubating to Graduation 
Projects that wish to move from Incubating to Graduation should open a PR confirming the following criteria: 
* Have committers from at least two organizations.
* Have completed an independent and third party security audit with results published of similar scope and quality as [this example](https://github.com/envoyproxy/envoy#security-audit) which includes all critical vulnerabilities and all critical vulnerabilities need to be addressed before graduation.
* Explicitly define a project governance and committer process. The committer process should cover the full committer lifecycle including onboarding and offboarding or emeritus criteria. This preferably is laid out in a GOVERNANCE.md file and references an OWNERS.md file showing the current and emeritus committers.
* Explicitly define the criteria, process and offboarding or emeritus conditions for project maintainers; or those who may interact with the Cloudforet on behalf of the project. The list of maintainers should be preferably be stored in a MAINTAINERS.md file and audited at a minimum of an annual cadence.
* Have a public list of project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the project website). For a specification, have a list of adopters for the implementation(s) of the spec.
* Please include a short one-page narrative based off the Graduation template, no more than 500 words.

## (4) Archiving Projects

Open source projects have a lifecycle and there are times that projects become inactive due to a variety of reasons. There are also cases where a project may no longer want to be supported by the TOC, or the TOC may no longer wish to recommend the use of a project.
Archiving Criteria
When voting on a proposal to archive a project, TOC members may wish to consider whether the project continues to meet the criteria for Cloudforet acceptance. The TOC may also look at activity levels in the project (https://all.devstats.cncf.io/d/53/projects-health-table?orgId=1), although it is important to note that there is a difference between a mature project that doesn't get much attention any more but is stable, versus a project that is inactive.

