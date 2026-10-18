# robofinemani2026.github.io

CoRL 2026 Workshop — *Beyond Binary Success: Diagnosing Fine-Grained Capabilities in Robot Manipulation*.

Static multi-page site (one page per section): About (index), Open Competition, Call for Papers, Invited Speakers, Program, Organizers.

Leaderboard updates are maintained in `leaderboard.html`. Whenever adding a team or updating its scores, record the actual submission time in `submittedAt` as an ISO 8601 UTC timestamp (for example, `2026-09-20T03:51:00Z`) and update `LB_UPDATED` to the publication date. The Overall table displays submission times in UTC; legacy entries remain `-` until their next score update. Do not substitute the evaluation or publication time for the submission time.

When a result provides task totals without dimension scores, record the supplied totals in `taskScores` and set the unavailable current dimensions to `null`. Missing dimensions and incomplete dimension averages display an em dash; Overall is the mean of the five task totals. Retain dimension scores only for unchanged or explicitly restored task versions. When detailed results arrive, fill in the dimensions and remove the corresponding `taskScores` overrides so that totals are computed from the detailed scores again.
