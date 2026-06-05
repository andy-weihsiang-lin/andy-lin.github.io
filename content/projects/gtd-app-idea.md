+++
title = 'GTD App Ideas'
date = 2026-06-03T10:23:04-04:00
+++

After reading the book *Getting Things Done* (GTD) by David Allen, I plan to develop my own productivity app **GTD** the incorporates the idea from the book and some extensions based on my preference and needs.

I plan to build the app with Python and SQL. I would like to use this post to collect ideas for features to be implemented in the app:

#### 1. Centralized Interface
The book GTD suggests arranging actions in the following lists:
- Projects
- Next Actions
- Waiting For
- Someday/Maybe

I think this system was well-designed for paper-based environment, yet I feel it cumbersome to find actions in lists here and there, so I will hope to establish only one single (centralized) interface to manage everything though the database is still designed in the way GTD suggests.

#### 2. Historical Activity Recording
I want the system to keep records of 
- Completed tasks
- Task durations
- Productivity

I want to record to be properly stored for future analysis, which is similar to an actuarial experience practice.

#### 3. Project Length Estimation
I want the app to estimate the duration of a new project based on historical record of similar tasks. For example:

The "GTD" Project
- Historical average: 40 hours
- Expected completion: 45 hours

The concept is: Historical Data -> Forecast Model -> Future Completion Dates

This is analogous to actuarial forecasting.


#### 4. Sensitivity Analyasis

I want the app to conduct sensitivity analysis. For example:
- What if I study 30 min/day more?
- What if I spend weekends coding?

and seeing the impact on projected completion dates.

#### 5. Activity Feeder
I want the app to feed/assign **Next Action** based on 
- **Context:** tool, people, agenda, etc
- **Time available:** consider when I should stop
- **Energy available:** help decide the difficulty of Next Action
- **Priority:** follow the 6-level concept in GTD, bottom-up

Rather than manually/arbitrarily browsing list for decision, which adds mental burdens.

#### 6. Analysis Reports
I want the app to be capable of generating 
- productivity reports
- completion reports
- workload reports
- forecasting reports
- acquisition report
   - similar to income statement in financial reports
   - shows knowledge I acquired during a specific time period (e.g., a quarter)
   - and also time/money that I spent on such acquisition?
- balance sheet (maybe?)
   - Asset
      - the accumulation of my acquired knowledge, I assume? 
      - maybe include the discounted value of future expected financial income?
   - Liabilities
      - what defines the liabilities here? maybe commitments?
   - Shareholder value
      - what does it mean here?

#### 7. Command-Line Interface (CLI) in Initial Version
ChatGPT helped me propose a learning path:
- PostgreSQL
- Python
- Build CLI productivity app
- Evolve into better UI

#### 8. SQL-Centered Data Model
The database is a core design component rather than merely a storage backend.

#### 9. Long-Term Evolution Toward Better UI
Starting with CLI, the UI may be enhanced:
- TUI (Terminal UI)
- Desktop app
- Web app

#### 10. Integrate Email Fuction
I want the app to be capable of sending email, e.g., automotically sending email to my delegatee(s) before the actual need-by date as a reminder.

#### 11. Confidence Interval
Instead of a deterministic estimate, the app may provide a confidence interval for forecasting, such as
- Completion forecast:
   - 50%: Aug 15
   - 75%: Sep 1
   - 90%: Sep 20

#### 12. Variance Reports
Provide information such as
- Average: 23 TUs
- Std Dev: 18 TUs

to identify uncertainty.

#### 13. Resource Allocation Reports
Provide a report like:
- Time allocation
   - Actuarial: 45%
   - Python: 25%
   - Investing: 15%
   - English: 15%

#### 14. Forecast Accurary Report
Since the system will forecast completion dates (in terms of a point-estimate or a confidence interval), I want to to provide analysis like
- Forecast: 40 TUs
- Actual: 50 TUs
- Errors: +25%
- Error (Last 12 months): 12%
- Forecast Bias: Underestimation

This creates a feedback loop.

#### 15. Bottleneck Detection

#### 16. Task Split
If the current task is identified as "too large" after I start working on it, there should be a button that can help divide it into smaller pieces, where the time already spent will be allocated to one of the sub-tasks.


