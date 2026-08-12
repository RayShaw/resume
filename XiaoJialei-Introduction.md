
# English interview self-introduction

Hello, my name is Xiao Jialei. I'm a full-stack engineer based in Guangzhou. I have more than ten years of software development experience, and frontend development is my strongest area.

In my most recent role, I mainly worked on a WeChat Mini Program and its admin system. I delivered more than 100 pages and features for over 10,000 members, and we released updates every week. I also built reusable React and TypeScript components for forms, filters, and dialogs.

Frontend was my main job, but I also worked with backend engineers on Java API design and integration. This work included login, JWT, user permissions, and business APIs with Java 17 and Spring Boot 3. I also helped improve page loading and reduce repeated requests with frontend and Redis caches.

Before this,  I built data dashboards with Vue and ECharts for A web systemEarlier, I worked on a clinical data system with React, Node.js, and MongoDB. I started my career as a Java developer. These roles gave me experience in frontend, backend, and database work.

One thing I do well is follow a feature through the full process. I can discuss requirements and user flow, build the frontend, work on the API, test the feature, release it, and fix production issues. I work closely with product, design, and backend teams. I use Codex and Claude Code for some tasks, but I review every change and run tests.

I am looking for a full-stack role where I can use my frontend strengths and continue to work on backend development. Thank you for your time.



# English project introductions

## Project 1: WeChat Mini Program

I worked on a WeChat Mini Program for member campaigns and coupon services. It served over 10,000 members. I built campaign pages, coupon distribution and claim pages, and coupon package purchase pages.

I used TypeScript and business APIs to show the right content for each campaign and coupon state. I blocked repeated clicks and showed clear loading, payment, and error states. I also moved non-home pages into subpackages and combined repeated requests. This reduced startup downloads and repeated data loading.

On the backend, I designed Java 17 and Spring Boot 3 APIs and database calls for coupon orders. The service checked the order and payment result before issuing coupons. Refund rollback kept the order, payment, and coupon records consistent if one step failed. I also handled WeChat login checks and kept token state in Redis, including refresh, expiration, and logout.


## Project 2: Operations admin system

I worked on the operations admin system. Staff managed members, coupons, settings, and dashboards.

I built the frontend with React, TypeScript, and Ant Design. Complex forms had many rules, so I created shared components for forms, filters, dialogs, and status messages. TypeScript types checked inputs and API data. This reduced repeated code and kept the pages consistent.

I also handled login and permissions. The request layer checked JWT state and returned expired sessions to login. The frontend used RBAC data from the server to control routes and actions. The server still made the final permission check.

For Java API integration, we used SpringDoc to confirm data formats and JUnit to test main cases. This reduced API mismatches.

Across the admin system and Mini Program, I delivered over 100 pages and features for over 10,000 members. We released updates weekly.
