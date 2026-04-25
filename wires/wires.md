Twitter Clone Front-End Wireframes
Login / Signup Page
+--------------------------------------+
|          Twitter Clone               |
|--------------------------------------|
|                                      |
|        [ Username / Email ]          |
|        [ Password ]                  |
|                                      |
|        [ Login Button ]              |
|                                      |
|        Don't have an account?        |
|        [ Sign Up ]                   |
|                                      |
+--------------------------------------+
Home Feed Page
+--------------------------------------------------+
| Navbar: Home | Profile | Logout                  |
+--------------------------------------------------+
| What's happening?                                |
| [ Write a new tweet...              ]            |
| [ Post Tweet ]                                   |
+--------------------------------------------------+
| @username                                        |
| This is a tweet example.                         |
| [View Profile] [Delete if owner]                 |
+--------------------------------------------------+
| @anotheruser                                     |
| Another tweet appears here.                      |
| [View Profile]                                   |
+--------------------------------------------------+
User Profile Page
+--------------------------------------------------+
| Navbar: Home | Profile | Logout                  |
+--------------------------------------------------+
| @username                                        |
| User profile information                         |
+--------------------------------------------------+
| Latest tweets by this user                       |
+--------------------------------------------------+
| Tweet 1                                          |
| [Delete if owner]                                |
+--------------------------------------------------+
| Tweet 2                                          |
+--------------------------------------------------+
Tweet Component
+--------------------------------------------------+
| @username                                        |
| Tweet content goes here.                         |
| [Profile] [Delete]                               |
+--------------------------------------------------+
App Flow
Login / Signup
      |
      v
Home Feed
      |
      |-- Click username
      v
User Profile Page

Home Feed
      |
      |-- Post tweet
      |-- Delete own tweet
      |-- Logout
