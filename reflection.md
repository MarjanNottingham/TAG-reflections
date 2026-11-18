# Reflection on teamwork

## How we worked
We met weekly on Microsoft Teams, and the meeting transcripts let anyone who missed a meeting catch up. We split the requirements into work packages, one data area per person. Code went through feature branches and pull requests into `dev`, and from there into `main`. Everyone built on Muhammad's shared UI template, so all the pages looked and behaved the same.

## Tuckman's model
- **Forming:** the first meetings set the roles and the plan quickly. I took the Intensity work package and was clear about what it involved.
- **Storming:** several members fell behind, me included, and with only weekly meetings nobody noticed until late. Not everyone was clear on the git workflow either. My work stayed on my laptop instead of going on a branch, so the team couldn't see how far I'd got.
- **Norming:** a few members picked up work that had been dropped. Muhammad's template set a common standard, which made it easier for me to build a page that matched the others.
- **Performing:** most of the dashboard came together on the last day. My Intensity page came too late to be part of it.

The model assumes a team moves through the stages in order. Ours was still storming when it should have been performing, and my late contribution was one of the reasons.

## My role
In Belbin's terms I was mostly a **Specialist**: I owned one data area and built that page. I didn't show the **Completer Finisher** habits that would have got it reviewed and merged on time, and I wasn't there enough to act as a **Team Worker**.

## Retrospective

| Went well | Didn't go well | What I'll change for the AGP |
|---|---|---|
| The shared template made my page quick to build and consistent with the others | I started too late and opened my PR minutes before the deadline | Set myself a deadline a few days before the team's |
| I wrote tests for my calculations from the start | My page was never run on the real data | Test with the real data as soon as the code works |
| Meeting transcripts let me catch up on meetings I missed | My code was only on my machine, so nobody could see my progress | Push a draft branch early and update it often |
| Brainstorming requirements together was quick | I didn't record my video section, so the team had to cover for me | Tell the team early if I'm falling behind, not on the day |
| | I didn't keep a weekly log as I went | Write the log at the end of every week |

## What I learned
- How R Shiny modules and a shared UI template let several people work on one app
- That a pull request opened on the deadline counts for very little, because it needs time for review
- That being present and visible matters as much as the code: the team can only plan around work it can see
