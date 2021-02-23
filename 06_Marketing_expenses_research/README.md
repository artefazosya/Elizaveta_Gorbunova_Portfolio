# Marketing expenses research

This is a study project dedicated to `Business Analytics` theme from `Yandex.Practicum Data Analysis` course.

**Key words**: LTV, CAC, ROMI, cohort analysis. 

**Libraries used**: pandas, matplotlib, seaborn, scipy.

## Project's goal<a id='goal'></a>

The project's goal is to to help Yandex.Afisha optimize marketing expenses.

### We have the following data:

- Server logs with data on Yandex.Afisha visits from June 2017 through May 2018
- Dump file with all orders for the period
- Marketing expenses statistics

The **visits** table (server logs with data on website visits):
- `Uid` — user's unique identifier
- `Device` — user's device
- `Start Ts` — session start date and time
- `End Ts` — session end date and time
- `Source Id` — identifier of the ad source the user came from

The **orders** table (data on orders):
- `Uid` — unique identifier of the user making an order
- `Buy Ts` — order date and time
- `Revenue` — Yandex.Afisha's revenue from the order

The **costs** table (data on marketing expenses):
- `source_id` — ad source identifier
- `dt` — date
- `costs` — expenses on this ad source on this day

### We are going to study:
1. How people use the product
2. When they start to buy
3. How much money each customer brings
4. When they pay off 