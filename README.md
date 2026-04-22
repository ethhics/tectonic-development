# Tectonic Development

**The bootstrapping is still underway. *Everything* is subject to change!**

We are uncovering better ways of building software by doing it and helping others do it. Through this work we have come to value:

- **Context over code**
- **Specification over implementation**
- **Verification over generation**
- **Taste over throughput**

That is, while there is value in the items on the right, we value the items on the left more.

## Overview

Tectonic is a spec-driven development framework designed for a world
where code generators are confident liars and code reviewers are rate-limited humans.
When the Agile Manifesto was written in 2001,
the binding constraint for software development was the ability to coordinate humans.
Now, it is something akin to the product of *context quality*, *agent capability*, and *human review bandwidth*.

We believe that this approach may be irrelevant soon, and that it will certainly be irrelevant two years from now.

We believe other things, too, but we haven't had the bandwidth to review them yet.

## How to Use

1. `git clone` this repo into your work
2. Drafts specs with your agent in the format defined in `tectonic/spec-format` and `tectonic/spec-format-reference`
3. Perform a Definition Review (`tectonic/review-discipline/definition-review`) to approve your spec and begin generating its code and artifacts
4. Perform an Implementation Review (`tectonic/review-discipline/implementation-review`) to confirm that the generation went according to spec
5. Perform a Modification Review (`tectonic/review-discipline/modification-review`) to change a spec
6. Perform a Maintenance Review (`tectonic/review-discipline/maintenance-review`) as needed to confirm that your specs are still valid

## When You Have Problems

Flame me in an issue.
