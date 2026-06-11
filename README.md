# Healthy Blood — Cholesterol Quiz

Live: **https://healthyblood-quiz.netlify.app/**

A Dr. Gundry cholesterol/statin assessment quiz (8 questions → personalized
results → "Get Healthy Blood Now" offer).

## Analytics
Every screen view, answer, branch, completion, and CTA click is tracked to the
quiz analytics dashboard:

**https://healthyblood-quiz-analytics.netlify.app/** (repo: `healthyblood-quiz-analytics`)

Tracking lives in the `__HB_TRACK__` module at the top of the `<script>` in
`index.html`. To point the quiz at a different dashboard, change the `BASE` URL there.

## Deploy
Hosted on Netlify (account: xxclaude1):

```bash
netlify deploy --prod --dir .
```
