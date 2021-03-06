page_main_title: API Tokens
main_section: Platform
sub_section: Tutorials
sub_sub_section: API
page_description: Overview of Shippable's Account Settings API section UI

#API Tokens
This is where you generate, view and manage access tokens to use our [API](/platform/api-overview).

##Adding a token
To add a token:

- Click on **Account Settings** (gear icon on the far right of the dashboard).
- Click on 'API tokens' and then 'Add Tokens' button.
- Enter a token name and click on `Add` to create a new token.
- IMPORTANT: Remember to copy the token. For security reasons, the token will never
be displayed again.

##Deleting a token
To delete a token, click on the `Delete` button next to the token you want to delete.
##Free User Tokens and Paid User Tokens
### What is a Free User Token
All tokens generated by a user on free plan are free user tokens.
### What is a Paid User Token
All tokens generated by a user on paid plan are paid user tokens.
### Difference between Free User Token & Paid User Token
Free user tokens have limited access and can only use the tokens in eventTrigger to trigger a build, whereas users with paid user tokens can access the full Shippable API.

**Please remember to keep your token safe and do not share it with anyone.** If your token get compromised, API calls can be made on your behalf and compromise the security of your Shippable account.

Treat your API token like an admin password. In case this happens, just deleting the token will remove all access to the token. You can create a new one to replace it and make sure you update it in all external services that might have been using it.
