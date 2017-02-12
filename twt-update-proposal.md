# Tuesdays With Toni
## Lesson Proposal

### Overview

This proposal is for switching TWT to a once a week lecture style class, to be given from 5:00pm - 6:30pm/7:00pm on Tuesdays. Would probably be an hour of lesson with 30 minutes for questions, helping specific students, or just overrun time for the lesson. I would need a classroom to do this in and would be hoping for 10+ people to attend each session, though honestly I would probably give the lesson even if only 3 people showed up.

I currently only have 5 weeks planned out, and would be proposing to start this Tuesday, May 2nd (1705 cohort) so I have enough time to really put together some solid lectures and plan out code examples.

### Why?

I've seen a lot of the same knowledge gaps in students from the 3 mods when I did TWT as a student and the 3 mods I've done it since I've been an alumni. There's so much knowledge that teachers needs to get through during the day that they don't always have time to focus more depth on a topic or the 'how' part of the process. I think I could reach a lot more students by doing a class for groups of people, targeting each week specifically to at least one mod. This would replace my normal TWT sessions, though I would still make myself available for one-on-one mentoring if a student went out of their way to request me.

### Week 1 - ActiveRecord & SQL
#### Focus: BE Mods 2 & 3

The process of constructing a query, both in raw SQL and ActiveRecord.

- How do I take a request 'find me the most ridden bike' and turn it into a query?
- What table should you start with?
- Different types of joins and when to use them
- Maybe even down to subqueries and checking associations
- How to use aggregate functions and what to put in a group by clause

### Week 2 - RSpec Testing
#### Focus: BE Mods 2 & 3

Advanced testing in RSpec, including mocks, stubs, doubles, and testing style.

* Various RSpec matchers (match_array, a_hash_including, etc.)
* Doubles and when to use them
* Stubbing and setting expectation mocks
* When to use these things and when NOT to use them
* How to write good test specs (probably mostly non-capybara focused) including a dive into what GSC uses as a testing style guide

### Week 3 - Git/GitHub/PRs
#### Focus: All mods, all programs

In depth dive into git, advanced git workflow, and style guides. Possibly a longer lesson since I taught some of this to mod 3 FE on Feb 10th and it took about 80 minutes.

* What is git really doing when you commit?
* 3 three trees/file collections
* branching and why to do it
* rebase/cherry-pick (when and when not to do it, wtf is it doing?)
* git log and all its super awesome features
* git add -p and Sourcetree
* git reset demystified
* git remotes
* recovering from git reset --hard (yes, it is possible)
* commit message and PR style/guidelines

### Week 4 - Helpful Terminal/Environment Setup
#### Focus: Mod 1, FE or BE

Now that mod 1 has gotten their feet wet a little, they might be ready for things like how to update your terminal prompt, save your GitHub password, and configuring iTerm. Could also be useful for other mods who are interested, but some might know this stuff already.

* terminal prompts (colors, git branch/state, etc.)
* bash vs. fish
* git completion in terminal
* saving GitHub username/password
* setting up aliases (including git aliases)
* setting up iTerm profiles & other iTerm settings (including keymappings for options & command that are natural)
* git commit routing to atom or another text editor
* basic VIM in case you want to use that plus git commit auto-wrapping and spell checking for vim

### Week 5 - Heroku
#### Focus: Mods 2 - 4, FE or BE

A more in depth look at Heroku, how it interacts with git, and what it's capable of.

* what is heroku and why use it?
* deploying to heroku (including pushing branches, buildpacks, and migrations)
* heroku dynos (what's free, dyno sizes and properties, one-off dynos)
* free addons that are great for you to use
* heroku logs and debugging production
* connecting to S3 to store assets
* background workers and sidekiq (including sidekiq monitoring)
* common heroku commands

### Week 6 - TBD
