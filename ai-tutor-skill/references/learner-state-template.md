# Learner State Template

Keep these files outside the published skill when possible, because they contain
personal learning history.

## learner-profile.md

```yaml
role: traditional platform product manager
ai_experience: beginner
goals: []
preferred_language: Chinese
weekly_time: <hours>
preferred_depth: practical | balanced | rigorous
current_route: dual
```

## learning-log.md

For each session record:

```yaml
date: YYYY-MM-DD
topic: <concept-id>
route: bottom_up | top_down | dual
objective: <observable outcome>
evidence: <what the learner explained or built>
mastery: 0-4
misconceptions: []
next_action: <small next step>
review_date: YYYY-MM-DD
```

## review-queue.md

Store one row per item:

```text
concept | last_seen | mastery(0-4) | next_review | reason
```

Use the queue as a prompt for retrieval practice, not as a reason to reread
everything. Move an item later only after the learner can explain and transfer
it, not merely recognize it.
