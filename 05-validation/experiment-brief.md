# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** Multi-Armed Bandit

**Why:** FinWise can't afford to split equal traffic for a certain duration and wait to see the outcomes, because we are optimizing for trial to paid conversion while improving retention. We therefore want to minimize dropout during the test.

_____

## Hypothesis + primary metric

If we improve the quality of the financial forecasts (and therefore value) for FinWise users, then we expect to see improved trial-to-paid conversion and improved retention.

**Primary metric:** Weekly active sessions per user, target: A 15% increase in weekly active sessions within two weeks

_Experiment: Reduce churn by showing higher quality forecast insights, Improve trial to paid conversion for new users and improve retention among existing users_

_Testing A change to the Monday email that shows forecast confidence slipping, for example (71% confident: 2 minute review), prompting users to review and confirm transactions (which will therefore improve their forecasts). Three versions of this email prompt. on Users who already have imported financial data and have used the financial modeling feature. Current experience: Users see a financial model/forecast after they import their financial data._

_Predicted outcome: Weekly active sessions increase as MAB identifies and scales the highest-performing prompt variant within two weeks. If successful: Lock in the winning prompt variant and test new variables such as timing and frequency. If unsuccessful: Review if the reminders created friction. Test a different re-engagement mechanism entirely.._

_____

## Guardrail + read date

- **Guardrail:** Financial data import completion rate should not change, since the change targets what happens after activation
- **Read date:** 14 days after launch, on the 15th, no earlier

_____
