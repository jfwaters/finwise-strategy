# Pricing recommendation: move FinWise to freemium

October 22, 2026 · From: Senior PM · To: FinWise leadership team

## The problem

FinWise has product-market fit and $10M ARR, but growth is expensive and leaky. Only 2% of trial users convert to paid, 40% of paid customers remain after one year, and most growth is bought through paid acquisition.

The reverse trial isn't moving people to pay. Over the last 13 months, monthly conversion held at 1.9–2.1% while trial starts ranged from 321 to 644 and feature usage swung widely. Every trial that ends without converting is acquisition spend we don't recover, and the small business walks away.

## Recommendation

Replace the reverse trial with a freemium model.

| Tier | What's included | Price |
| --- | --- | --- |
| Free | Import data and organize the business's finances, with no time limit | $0 |
| Paid | Financial Modeling beyond a free usage allowance, plus scenario planning | Subscription |

Free users can try Financial Modeling up to a set limit, so they see the payoff before they hit the paywall. Existing customers keep their current plans.

## Why this is the right move now

- **It fits our stage.** We're in Stage 1, Value Creation. The priority is getting more small businesses to experience value and build a habit, not forcing a purchase decision at a trial deadline.
- **It cuts our dependence on paid acquisition.** Businesses that keep using a free tier stay in our funnel instead of disappearing when a trial ends. They also bring in others through word of mouth and their accountants.
- **It puts the paywall at the moment of value.** Financial Modeling is where users move from seeing their numbers to making decisions with them. It's the stronger of our two activation indicators: its monthly usage tracks conversion weakly (r = 0.24), while Import usage shows no relationship. The signal is weak and based on 13 months of totals, so we treat it as a hypothesis to test, not a proven lever.
- **It should improve retention.** Customers who build a habit before paying should churn less than those pushed to pay at a deadline.

## How we'll know it's working

We'll run freemium against the reverse trial on a randomized 50% of new sign-ups for one quarter.

| Measure | What we're looking for |
| --- | --- |
| Revenue per new sign-up (primary) | Equal to or higher than the reverse trial |
| Paid conversion within 90 days | Higher among free users who reach the Financial Modeling limit |
| 90-day paid retention | Higher than reverse-trial customers |
| Blended acquisition cost per paid customer | Lower |
| Cost to serve free users (guardrail) | Within an agreed budget |

The headline conversion rate will likely fall, because the free tier adds many more non-paying users. We should judge the test on revenue per sign-up and paid customer growth, not conversion rate.

## Risks and decision

- **The free tier may be good enough.** Some businesses may never upgrade. We'll keep modeling and scenario planning behind the paywall and adjust the free usage limit based on test results.
- **Value may not be the only barrier.** If free users reach the Financial Modeling limit and still don't pay, price is the next lever to test.
- **Free users cost money.** Support and infrastructure costs are tracked as a guardrail.

**Decision requested:** approve a one-quarter freemium test on 50% of new sign-ups, with a go/no-go review at the end of the quarter.
