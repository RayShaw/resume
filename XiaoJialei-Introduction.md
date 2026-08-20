
# English interview self-introduction

Hello, my name is Xiao Jialei. I'm a full-stack engineer based in Guangzhou. I have more than ten years of software development experience, and frontend development is my strongest area.

In my most recent role, I mainly worked on a WeChat Mini Program and its admin portal. Across both products, I delivered more than 100 pages and business modules. The Mini Program supported more than 10,000 members, and our team released updates weekly. For the admin portal, I built reusable React components in TypeScript for forms, filters, and dialogs.

Frontend development was my main focus, but I also contributed to Java API design and integration with the backend team. I worked on member, coupon, and login APIs built with Java 17 and Spring Boot 3. I also helped pages load faster and reduced duplicate requests by adding caching on the frontend and in Redis.

Before that, I built data dashboards with Vue and ECharts for a web data analysis system. Earlier, I worked on a clinical data system using React, Node.js, and MongoDB. I started my career as a Java developer. These roles gave me experience in frontend, backend, and database work.

One thing I do well is take a feature from requirements to production. I can discuss requirements and user flows, build the frontend, integrate the API, test and release the feature, and fix production issues. I work closely with product managers, designers, and backend engineers. I sometimes use Codex and Claude Code to help with development, but I review every change and run tests.

I am looking for a full-stack role where I can use my frontend strengths and continue doing backend work. Thank you for your time.



# English project introductions

## Project 1: WeChat Mini Program

I worked on a WeChat Mini Program for membership benefits and coupon activities. It supported more than 10,000 members. I built activities pages, coupon distribution and redemption flows, and membership package purchase pages.

I used JavaScript and backend APIs to show the right content for different activities and coupon states. I disabled repeated actions while a request was in progress and showed clear loading, payment, and error states. I also moved non-home pages into subpackages and combined duplicate API requests. This reduced the initial download size and unnecessary data loading.

On the backend, I contributed to the design and integration of member, coupon, and login APIs built with Java 17, Spring Boot 3, and MyBatis-Plus. I helped confirm the API contracts with SpringDoc OpenAPI and add JUnit tests for key cases. I also helped integrate WeChat login, including client-side JWT checks and Redis-based token refresh and logout. The server performed the final authentication and permission checks.


## Project 2: Operations admin system

I worked on an admin system for the operations team. Staff used it to manage members and coupons, configure business settings, and view dashboards.

I built the frontend with React, TypeScript, and Ant Design. Because the forms had many business rules, I created shared components for forms, filters, dialogs, and status messages. These components reduced duplicate code and kept the pages consistent. I also defined TypeScript types for component inputs and API data, which helped catch errors during development.

I also worked on login and permissions. The request layer checked whether the local token was missing or expired and redirected the user to the login page. The frontend used permission data from the server to control routes and actions. The server made the final authentication and permission checks.

For Java API integration, I used SpringDoc OpenAPI to confirm the request and response contracts and contributed JUnit tests for the main use cases. This reduced API mismatches.

Across the admin system and Mini Program, I delivered more than 100 pages and business modules. The Mini Program supported more than 10,000 members, and our team released updates weekly.


# English challenge and solution


One challenge I faced was slow loading in our WeChat Mini Program. Many business pages were in the main package, and the home page made some API requests more than once. This page was the main entry point for members, so its speed affected their first experience with the Mini Program.

I checked the startup flow and found what loaded when the app opened. I used Mini Program subpackages, so pages that were not needed at startup loaded only when users opened them. I combined duplicate API calls and added two cache layers, one on the frontend and one in Redis on the server. I tested the main flows and error cases before release.

This reduced the initial download size and unnecessary data loading, so the app opened faster. My frontend experience helped me find the problem, and my backend knowledge helped me choose a solution that worked on both sides. The team also kept its weekly release schedule.
