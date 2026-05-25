# Troubleshooting

## skills command not found

Error:

Command 'skills' not found

Solution:

Skills are stored locally:

ls ~/.agents/skills

Do not use:

skills list

---

## HyperFrames preview stuck

Try:

npm run dev -- --no-open

If preview fails with:

EPERM
listen 0.0.0.0

The issue is usually environment permissions, not HyperFrames.

---

## HyperFrames render validation

Run:

npm run check

Then:

npm run render -- --quality draft

---

## Verify installed skills

ls ~/.agents/skills

