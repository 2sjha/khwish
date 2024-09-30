## Khwish
Khwish was a personal project I created in early 2020. Khwish, based on the word 'Khwaish,' which means 'a wish' in Hindi/Urdu, was a community funding platform where users could create events/goals/wishes and share them with their friends. Friends & family could contribute money to support the events. The platform consisted of 3 applications, an Android app, a React website, and a Spring Boot backend. 

### [Khwish App](https://github.com/2sjha/khwish-app)
This app was for users to create/modify/close events and do the same for goals/wishes inside those events. Users could share a website link to those events via all sharing options available on Android. Users could also monitor contributions to their goals. Users also had access to their wallets, which maintained their total collections and all credit & debit activities. Users could submit a withdrawal request of any amount from their wallet at any time.

### [Khwish Web](https://github.com/2sjha/khwish-web)
This mobile-first website was for the gifters/contributors to support their friends' & family's events. Previously shared links would take the contributors to this website, where they could securely make payments via [Instamojo](https://www.instamojo.com/) to specific goals inside the shared event.
After successful or unsuccessful payment, the website would show a thank you or a retry popup, respectively. The contributors would also get a thank you email upon successful contribution.


### [Khwish Backend](https://github.com/2sjha/khwish-backend)
This Spring Boot based server application was the platform's backbone providing API endpoints for all core functions. This backend application had several integrations with third-party dependencies, like the PostgreSQL database, Firebase Authentication & Notifications, Instamojo Payments, Facebook SDK, Sendgrid Emails, Google Sheet updates, and Slack webhook messages. An extensive list of functions can be found on the repository's page.

<br><br>
Khwish platform was discontinued around mid-late 2020; I'm no longer actively working on this project.