# feedchaos
# Welcome to FeedChaos!

This is a portfolio project intended to demonstrate some of my skills. It is a work in progress, I keep improving the code base, and may add features such as those specified below.

While this is a showcase of my current coding skills, I did use a predecessor of the app to get trading ideas. In an extended version you may, for example, check when stocks tend to reach their minimum or maximum over any time frame, or where related stocks or ones in a given field tend to go globally. While major stocks are thoroughly covered, I believe that, over time, this tool may help you discover hidden gems. This version's database was started in 2024.

As this is an experiment, not a production site, budget is kept at a minimum at the cost of availability and convenience. Stock splits or reverse splits are not taken into account, which may result in inaccurate differences. Some of the foreseen features, as well as the existence of this project are tied to budgetary contraints. Please, try existing features, check possible future additions, and don't hesitate to send me feedback at feedchaos50@gmail.com.



Technologies used:
Backend:
    • Node.js / Typescript / Javascript
    • NestJS
    • Kubernetes
    • GCP / GKE
    • Docker
    • PostgreSQL
    • Prisma
    • GraphQL
    • ESLint

Frontend:
    • Next.js / React
    • Material UI / Tanstack Material React Table
    • Storybook
    • AWS

Possible feature additions:
    • User administration / retention of user configuration
    • Screening of symbols against the list of those managed by your trading platform provider (they are now screened against my local provider's list)
    • Push notification via email or SMS when thresholds are tripped (e.g. 'value' based)
    • Addition of historical data
    • Consideration of splits and reverse splits, notification of forecasted ones
    • Quick access to existing charts services
    • Addition of charts, analyses you may like
