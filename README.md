# Sample fleet and home-product landscape

This folder is a layout example. Every person, date and volume in it is dummy data. Do not treat any figure as live performance.

The page shows how a vehicle base splits across home products: vehicle only, home charger, home battery, and the full stack. Filters, the cohort table and the trend all use the same rules as the working dashboard. The names and the numbers are not.

## Who it is for

Sales and home-energy planning, and the analyst who prepares that review.

## What it answers

- How many owners have a vehicle only, versus a charger, a battery, or the full stack?
- What share have a home charger or a home battery today?
- Are multi-vehicle households more attached to home products than single-vehicle ones?
- What share of owners are first-time buyers versus repeated buyers?
- How does today's attach differ by first-product year, or by vehicle delivery year?
- Of partner orders, how many were already customers versus new, and what did existing customers already own?

## The problem it solved

Vehicle ownership, home-charger attach, home-battery attach and partner orders sat in separate extracts. A reviewer could not see, on one page, the opportunity pool (vehicle only), the step-up pool (charger but no battery), and whether older cohorts were more attached than recent ones. The dashboard rolls that up to people, not accounts, so a leasing firm does not collapse into one customer.

## How it is built

- HTML and CSS for the page
- JavaScript for filters, the mix, the cohort table and the trend
- Canvas for the attach trend and the partner split (no external chart library)
- Python to build the sample extract embedded in the page

The live version is assembled from vehicle and energy extracts into one HTML file. This copy is not. It reads only `landscape_data_SAMPLE.js` in this folder.

## Dummy data

There are 4,180 fictional people and 5,735 fictional vehicles, dated 2018 to 2026. Hubs, product names and partner totals are invented. The mix, the first-time share and the partner split are not the live rates.

Open `index.html` in a browser. Keep it next to `landscape_data_SAMPLE.js`.

To open it from GitHub the same way as the partnership sample, upload this folder as the repository root so `index.html` is at the top of the repo, not inside another folder. Both files have to stay side by side. GitHub shows the source if you click the file; use the same preview link you used for the partnership sample to see the page.
