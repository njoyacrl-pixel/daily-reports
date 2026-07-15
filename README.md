# Daily Reports

Every intern submits a short report at the end of every session — **via Pull Request**. A merged PR is your attendance for the day. No PR, no attendance.

## How to submit (every day)

```bash
git checkout main
git pull
git checkout -b week01-day02-yourname
# copy TEMPLATE.md to: reports/week-01/day-02/yourname.md
# fill it in, then:
git add .
git commit -m "Daily report: week 1 day 2 - yourname"
git push -u origin week01-day02-yourname
```

Then open a Pull Request on GitHub **before midnight the same day**. The lead (or an assigned peer) reviews and merges it.

## Rules

- File goes in `reports/week-XX/day-XX/yourname.md` (lowercase, no spaces).
- Use [TEMPLATE.md](./TEMPLATE.md) — copy it, do not edit the template itself.
- Honest reports beat impressive reports. "I got stuck on X for 2 hours" is a *good* report.
- Review a peer's PR when asked — reading other people's reports is learning too.

## Why we do this

It builds the exact Git workflow professional teams use (branch → commit → push → PR → review → merge), it creates a public record of your growth you can show any employer, and it lets leads spot who is stuck before it becomes a crisis.
