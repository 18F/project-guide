---
permalink: /starting-a-new-project/communication-and-rituals/
title: Communication and rituals
parent: Starting a New Project
---
## Leading a build

- It's most important to set up a process that allows the team to work iteratively and measure results in the direction of a clear vision. To this end, we practice agile, but we don't specify an instantiation — many teams use scrum or kanban (or a version of them). To coordinate across multiple teams, some projects use [Scaled Agile Framework (SAFe)](http://www.scaledagileframework.com/guidance-essential-safe/). You can reach out to the agile guild for advice on #g-agile. 
- You should take time with your team in the beginning to define standards for creating backlog issues. Many teams like to follow a system by which each issue/card contains a title, user story, some background or context, and completion or acceptance criteria. For example, [this is the FEC team's guide for writing a good](https://github.com/18F/FEC/wiki/1.-FEC-team-task-board#issues) [issue](https://github.com/18F/FEC/wiki/1.-FEC-team-task-board#issues), or the [Gherkin style of writing software requirements](http://docs.behat.org/en/v2.5/guides/1.gherkin.html).
- You should ensure that a product roadmap exists at all times, containing high-level 'customer promises' in prioritized order. Your backlog should map to these customer promises. Some examples are here: [Alaska product roadmap](https://app.mural.ly/t/gsa6/m/gsa6/1493828126408/2c1fd30717381a20f4bf251e57a1c344f9e2c3ba), [CMS product roadmap](https://app.mural.ly/t/gsa6/m/gsa6/1513038917977/bc5ed885fa24db23ee957d217bec6c17993d7d70)
() - Some teams keep a running notes doc for each sprint for their goals, meeting agendas, and notes. This can also be used to inform your [release notes, which are a great way to share updates with your users and document your progress.](https://18f.gsa.gov/2017/01/17/life-changing-magic-writing-release-notes/)
- For additional team practices, see next steps.

## Dev team processes

- This [development guide](https://github.com/18F/development-guide) includes many of the technical tools, processes, standards, and documentation that we include in our projects. Consider reviewing it with your engineers (or encourage your engineers to review it).
- The engineering team is also building a command line tool that creates all of the engineering components and documents that our projects need in their GitHub repo (see #eng-scaffolding for questions).
- Develop policies for pull requests (submitting, reviewing, and merging them) and for testing (unit, integration, and feature). Here is an example of [the FOIA team's team practices](https://github.com/18F/foia-recommendations/blob/master/team-practices.md).
- Onboarding new team members can be a great way to test if your documentation is sufficiently thorough, clear, and accurate for a good open source project. Also, check out 18F's [pen source guide](https://open-source-guide.18f.gov/).
- We also have guides for certain standards of quality. Some of them include the [API standards](https://github.com/18F/api-standards), [front end style guide](https://pages.18f.gov/frontend/), [accessibility](https://pages.18f.gov/accessibility/), and more in the [18F Guides](https://pages.18f.gov/guides/).

## Communication

Clear communication is central to every team's success.

- We are spread across the country, and we use a "distributed-first" model for our teams. This means primarily using distributed tools for interacting. For example, even if some members of your team are physically co-located, you should hold your meetings from your separate desks over video chat so that everyone can see and hear folks. These 18F blog posts offer more guidance:
  - [18F's best practices for making distributed teams work](https://18f.gsa.gov/2015/10/15/best-practices-for-distributed-teams/)
  - [Making a distributed design team work](https://18f.gsa.gov/2016/04/27/making-a-distributed-design-team-work/)
- We communicate primarily via Slack. The 18F handbook has an extensive [guide to Slack](https://handbook.18f.gov/slack/), including [channel naming conventions](https://handbook.18f.gov/slack/#channel-naming-conventions).
- For video chats, Google Hangouts is integrated into our calendar meeting invites and effective for meetings up to 25 people. For larger meetings, we use Zoom. The 18F handbook has guides for [Google Hangouts](https://handbook.18f.gov/google-hangouts/) and [Zoom](https://handbook.18f.gov/zoom/).
- Make sure you are considering your partner's needs and restrictions here. Before deciding, discuss with your partner:
  - Are they facing any significant restrictions on their access to our tech?
  - Discuss Slack, GitHub, and video chat. Offer training. If you can get your partner to use these tools, your life will be much easier (and your teams' relationship better). (The 18F Handbook has guidance on [inviting partners to Slack](https://handbook.18f.gov/slack/#external-collaborators).)
  - What are their normal hours of availability? Share yours and your team's.
  - Let them know the best way to reach you if it's urgent.

## Rituals and meetings

Decide on the time of day, day of the week, and format for major meetings. The [18F agile guide](https://agile.18f.gov/practices.html) has a summary of agile rituals. This guide assumes that you are familiar with these basic practices; here are some tips for what to expect at 18F:

### Stand up:

- Share what was done yesterday, what you plant to do today, and any blockers. Some teams share this on slack prior to a video stand up.
- Most teams prefer video stand ups, but some use Slack. Either way, some teams find it helpful to set an automatic @channel reminder at the start time.
- Resolving the blockers -- which are often raised in stand up -- is one of your primary roles as a project lead.
- Before starting, check for open pull requests that need a reviewer.
- Keeping a running notes doc for all your meetings can be very useful later. Make sure you share the task of taking notes across the team.

### Sprint planning

- Many project leads prefer to groom issues prior to sprint planning.
- Ping your team before sprint planning to make sure the issues are all up to date before starting.
- Teams can differ greatly on point estimation. Some teams simply use small/medium/large and others use the traditional fibonacci sequence. For example, the FEC team estimates 1, 2, or 3 (analogous to small/medium/large) and then after all of the issues for the sprint have been assigned but before the end of sprint planning, team members individually review the work assigned to them. They then discuss as a team if the workload is reasonable and realistic, and adjust and prioritize as necessary.

### Backlog refinement:

- This involves reviewing and updating your backlog, and then prioritizing the issues with your partner agency.
- It can be easier to prepare points of discussion, take notes during the meeting, and then update the issues later, instead of juggling video chat and GitHub during the meeting.

### End-of-sprint ceremonies:

- Sprint review: If your team is in the habit of writing release notes, these notes can be a useful guide for items to demo.
- Retros are crucial to a cohesive, effective team. You should do them every sprint. Some teams occasionally include their partner in retros. Some project leads prefer to lead retro; some teams rotate the leader of the retro throughout the team.
- Release sync: Most teams aim to publicly launch updates at least every other sprint. A regular launch timeline and a pre-launch sync with the team can be useful. This is an example of [the FEC team's release checklist](https://github.com/18F/FEC/wiki/Release-checklist).

### Product iteration planning (usually every 3 months)

- Review your goals, vision, and strategy in this meeting. Are you still on track? Does your vision still make sense? Do you need to pivot?
- This is also a good time to onboard new team members and hold a larger retro with your team and your partner agency.
- You might want to fly your team in town for this if you will be taking on a large new chunk of work or starting work with a new part of the partner agency. Periodic in-person meetings like this can pay off significantly in the future for team cohesion, collaboration, and trust. Coordinate travel with your business unit.

The 18F Handbook has an overview of [meetings and related meeting tools](https://handbook.18f.gov/meetings-and-meeting-tools/), written for a broader audience.
