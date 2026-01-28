# ai-code-review

Get a code review before you even push. It reads your staged changes and gives you feedback with colored output right in the terminal.

## Install

```bash
npm install -g ai-code-review
```

## Setup

```bash
export OPENAI_API_KEY=sk-your-key-here
```

## Usage

```bash
# Stage your changes first
git add .

# Run the review
npx ai-code-review
```

You'll get color-coded feedback:
- 🔴 **CRITICAL** - Bugs, security issues. Fix these.
- 🟡 **WARNING** - Code smells, things that might bite you later.
- 🔵 **SUGGESTION** - Style and readability stuff.
- 🟢 **GOOD** - Things you did right. Everyone needs a pat on the back.

## Why bother?

Catches dumb mistakes before your teammates do. Way less embarrassing than getting "you left a console.log in here" on your PR.
