## ionFireChat
ionFireChat is a sample chat widget powered by Firebase. We created a simple authentication system with email and Facebook support in Ionic.

### Setup

1. Setting up a Firebase Account

In order to user Firebase, you need to have an account with them. Url: https://www.firebase.com/signup/

2. Setting up a facebook App for Login
Login the firebase dashboard, and select the `login&&Auth` tab, select the `facebook` tab, fill the `Facebook APP Id ` and `Facebook App Secret`.
https://developers.facebook.com/

3. Install the lib by bower

```
bower install firebase --save
bower install angularfire --save
bower install angular-md5 --save  // md5 for Angular.js and Gravatar filter
```

4. Replace the firebase url with your's in `www/js/configs.js`


### Issue
  - Signup modal closing earlier.
