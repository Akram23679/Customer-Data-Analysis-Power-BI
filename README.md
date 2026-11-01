# Customer Data Analysis

**PRDA-04** · Power BI and Tableau project by **Akram Ali**

Who shops in 10 Istanbul malls, what they buy, how they pay, and nine suggestions for the company.

![Power BI overview page](3_Dashboard/Screenshots/Page1_PowerBI_Overview.png)

## At a glance

| | |
|---|---|
| **Data** | 99,457 transactions · 10 columns · 10 malls · 1 Jan 2021 to 8 Mar 2023 |
| **Questions** | 10 business questions plus a dashboard |
| **Tools** | MySQL Workbench · Excel · Power Query · DAX · Power BI · Tableau |
| **Output** | 3-page Power BI report, 2-page Tableau dashboard, analysis report, presentation |

## Key data finding

The brief describes `price` as the price per unit, but it is already the transaction total (one Clothing item costs 300.08 TL; five cost 1,500.40 TL). Multiplying quantity × price would give 251.5M TL instead of the correct **68.55M TL**.

## Key findings

- **Women make 59.8% of purchases** and bring 59.7% of revenue, but men spend the same per order (691 vs 688 TL).
- **All ages shop about equally:** every age from 18 to 69 has 1,830–2,057 transactions.
- **Three categories bring 94.8% of revenue:** Clothing (45.3%), Shoes (26.5%) and Technology (23.0%).
- **Payment mix is the same for everyone:** about 45% cash, 35% credit and 20% debit in every group.
- **Two malls bring 40% of revenue:** Mall of Istanbul (13.85M TL) and Kanyon (13.71M TL).

## Suggestions

1. Focus on Clothing, Shoes and Technology.
2. Use low-price categories (food, cosmetics) to cross-sell.
3. Grow the male customer base.
4. Keep marketing broad across ages.
5. Start a loyalty programme.
6. Encourage card and digital payments.
7. Learn from the top malls.
8. Plan a February campaign.
9. Improve the data (fix the price description, keep adding data).

## Repository

```
index.html, style.css     project web page (HTML and CSS only)
1_Brief/                  the 11 tasks and column descriptions
2_Data/                   Customer.xlsx (99,457 rows)
3_Dashboard/              dashboard screenshots and an interactive web dashboard
4_Report/                 analysis report (PDF and Word)
5_Presentation/           presentation (PPTX and PDF)
```

## Limitations

- Every `customer_id` appears once, so repeat customers can't be measured.
- March 2023 has only 8 days of data.
- The 18-29 age group covers 12 ages; the others cover 10.
