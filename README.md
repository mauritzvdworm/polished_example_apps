# Polished Example Applications <img src="images/polished_logo_transparent.png" align="right" width="120" />

Example Shiny applications using [polished](https://github.com/Tychobra/polished) for authentication and user management.

You can sign into each of the apps linked below using:

 - email: demo@tychobra.com
 - password: polished

Additionally, the code for each app is available in this repo.  To run the apps locally, you will need to set up polished.  Set up instructions are available at this link: [https://github.com/Tychobra/polished/edit/master/README.md](https://github.com/Tychobra/polished/edit/master/README.md)

#### 1. Minimal app using polished

example coming soon

#### 2. Customize the Sign In / Register UI

Companies often want to add their logos and branding to the sign in and register pages.  With polished, you can easily customize these pages.  Just pass your custom UI to the `sign_in_page_ui` argument of `secure_ui()`.  

[Live Example](https://tychobra.shinyapps.io/custom_sign_in) 

#### 3. No Invite Required

Allow anyone to register and sign in to your app (i.e. no invite required).  See the code of a simple example in the "no_invite_required/" directory and the [live demo here](https://tychobra.shinyapps.io/no_invite_required).

#### 4. Apps Dashboard

[apps_dashboard](https://tychobra.shinyapps.io/apps_dashboard). With `polished`, users can sign in to multiple Shiny apps using the same email/password sign in credentials.  This allows you to make a dashboard of Shiny apps.  Users who sign into the dashboard of Shiny apps (or any Shiny app hosted in the same polished project) will then not have to reenter their credentials to switch between the Shiny apps they are authorized to access.  You can set user access at a per Shiny application level.  These are the example Shiny apps we included in the Shiny Apps Dashboard
  - [basic_insurer_dashboard](https://tychobra.shinyapps.io/basic_insurer_dashboard)
  - [interest_rate_walk](https://tychobra.shinyapps.io/interest_rate_walk)

#### 5 Custom Admin Functionality

You can add custom tabs to the admin dashboard by passing the ui and server code to the `secure_ui()` and `secure_server()` functions.  Example coming soon.
