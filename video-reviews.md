# Peer video reviews

The videos are on Moodle: DATA2007 > Week 7 > "TAG assignment videos".

## Group 10

Group 10 built a Streamlit dashboard. It opens on a summary of each user's headline numbers, then has pages for weekday versus weekend behaviour, wellness goal rings, a leaderboard with streaks, walking analysis and an estimated VO2 max. Their process stood out: they used Crazy 8s to generate requirements, prioritised them with MoSCoW, and gave each person ownership of a feature, so it was clear who built what. The video was well structured, with each member presenting their own part. Their retrospective was honest and specific: they wished they had transcribed meetings from the start and had more time to review pull requests.

## Group 9 (Dashboard video and retrospective)

Group 9 built their dashboard in Power BI, with Overview, Activity, Sleep and Weight pages, and filters by user and date on every page. The hourly steps heatmap and the sleep efficiency measure (time asleep divided by time in bed) were good choices, and pointing out the drop in sleep around the 1 May bank holiday was an interesting finding. They were also upfront about data quality: only 8 of the 33 users had weight data, and most of it came from two people. The retrospective was a bit unstructured, with each person adding thoughts off the cuff, and at about 8 minutes the video ran over the 6 minutes asked for.

## Group 3

Group 3's dashboard has a consistent set of filters (user, date range and weekday) across its Overview, Steps, Calories, Sleep and Health pages. Using correlation analysis was a good step beyond plain summaries: they found that very active minutes were linked to calories burned, but not to sleep or weight loss. The video was short and clear, and each person explained their own page. The retrospective was the most honest in the class: they admitted tasks weren't assigned clearly early on and that members' commitments didn't line up, and they set out how they'd fix that for the group project.

## Group 7

Group 7 started their analysis by running k-means clustering on heart rate data, which picked out when a person was asleep. It was a creative idea, and I liked that they explained how the team scaled it back to an achievable MVP. Their R Shiny dashboard turns the data into "BitFit Awards", with text summaries and trophy images that update for each award, which was a fun and memorable way to present it. The video also explained clearly how Shiny's UI and server parts work together. On the other hand, it was mostly one person talking, and it said little about how the team worked together or what they'd do differently.

## Tag_Task_Fitbit_Dashboard (group name not given)

This team built an R Shiny dashboard with Activity, Calories, Heart Rate, Weight and Sleep tabs, one per team member. Sharing reusable components across the tabs, such as the KPI cards and the leaderboard, was a sensible way to keep the tabs consistent. Standout features were comparing each person against the group average and a BMI chart with colour bands for each weight category. The video never said which group it was, and it ended suddenly on the Sleep tab with no key findings or team retrospective. That was a missed chance, since the brief asked for both.

## JLs team (Video Submission)

The JLs team gave the clearest account of project management in the class: recurring meetings, a team channel, and a GitHub board with backlog, in-progress, review and done columns, plus a weekly agenda card. Their data exploration was well explained, including that the dates were being read in as text and that the minute-level data was too granular, so they kept to the daily and hourly data for their MVP. Each member wrote 10 requirements, which they cut down to an agreed 40 kept as a checklist in Teams Planner. The live Streamlit demo of the Steps, Intensity, Heart Rate and Sleep tabs was a bit rushed at the end, and there was no reflection on what didn't go well.

## Group 8

Group 8 were the most rigorous with their data. They removed 79 days with no steps as "not worn" days, and cut the data off on 9 May so they had four whole weeks to compare. They wrote 35 requirements in EARS format, including some for failure cases like failed data loads and filters that match nothing. Their pipeline converted the data to Parquet files to help meet a two-second update target. The dashboard had useful touches, such as an adjustable step target, CSV downloads under each chart and a short-term forecast. Their findings section was the strongest in the class, because they warned that with only 33 users and no statistical tests, their results were descriptive patterns rather than proof of cause.

## Class findings

- **Planning and visible tracking worked.** The strongest teams (JLs, Group 10, Group 8) agreed their ways of working in the first meeting and tracked tasks somewhere everyone could see, such as a GitHub board, Teams Planner or rotating chairs with written-up actions.
- **Clear ownership mattered.** Most teams gave each person one data area or feature, and the videos where each person presented their own part made individual contributions easy to see.
- **Data quality decisions set teams apart.** The best videos explained what they removed and why, such as non-wear days and incomplete final days, and were honest about the limits of 33 users over a month.
- **Retrospectives were often the weakest part.** Several videos ran out of time or skipped the reflection, even though the brief asked for one.
- **The same problems came up in several teams:** unclear task allocation early on, members' commitments not lining up, and not enough time to review pull requests. These are the same issues our team had.

## How I'll improve for the AGP

- Agree ways of working and a task board in the first meeting, and keep my own tasks visible on it.
- Push work to a branch early and often, instead of all at the end, so it can be reviewed in time.
- Present my own part of the final video, so my contribution is clear.
- Keep a short weekly log as I go, rather than writing it up afterwards.
