# get-swe

A pack of [Claude Code](https://claude.com/claude-code) skills for college
students trying to land a software engineering internship — resume help,
interview practice, portfolio review, job discovery, and project ideation,
all usable directly inside Claude Code.

## Install

**Option A — via [skills.sh](https://skills.sh):**

```bash
npx skills add TheMuffinMan1320/get-swe
```

**Option B — one-line installer** (no dependency on the skills.sh CLI):

```bash
curl -fsSL https://raw.githubusercontent.com/TheMuffinMan1320/get-swe/main/install.sh | bash
```

Both install the skills into `~/.claude/skills/`. Restart Claude Code (or
start a new session) afterward.

## What's included

| Skill | What it does |
|---|---|
| `resume-review` | General audit of a resume for SWE internship applications — structure, ATS-compatibility, bullet quality — with rewrites. |
| `resume-adapter` | Tailors an existing resume to a specific job posting: reorders content and mirrors the posting's language without fabricating experience. |
| `internship-posting-searcher` | Searches the web for currently open SWE internship postings matching your criteria. |
| `project-idea-generator` | Generates resume-worthy project ideas scoped to a realistic timeframe, based on skills you want to showcase. |
| `leetcode-coach` | Socratic DSA practice partner — hints and pattern nudges instead of handing over solutions. |
| `behavioral-interview-prep` | Coaches STAR-format answers and runs live mock behavioral Q&A. |
| `mock-technical-interview` | Simulates a full live coding interview, playing interviewer, with a rubric-style debrief. |
| `github-portfolio-polish` | Audits your GitHub profile/repos for recruiter-readiness. |

## Usage

Once installed, just ask naturally in Claude Code — e.g. "review my resume,"
"help me tailor my resume to this job posting," "quiz me on a LeetCode
problem," "run a mock technical interview," or "find SWE internships at
mid-size companies in NYC." Claude Code picks the relevant skill
automatically based on what you ask.

## Contributing

PRs adding new internship-prep skills or improving existing ones are
welcome — keep each skill in its own top-level directory with a `SKILL.md`
following the existing format.

## License

MIT — see [LICENSE](./LICENSE).
