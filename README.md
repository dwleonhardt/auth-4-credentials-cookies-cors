# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

A way of identifying who you are (username).

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Cookies are sent in the header of the HTTP request. The server sends you a cookie/cookies if you do not have them yet then you send them back in your response. Your total cookies sent in the header can only be 4kb in size, your cookies can store information without using local storage and can be set to only be stored for a certain time period or just for the session which makes the more versatile in use, and CORS and same origin policy provides enhanced security procedures for data transfers between the client and the user. 

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

Does not use local storage, it is an easy way to make sure that your website is user friendly for example not having to log in on every single page. Cookies aren't only secure unless you are using CORS and/or same origin.

> What is the difference between a session cookie and a persistent cookie?

Once you end your session on you browser your session cookie disappears while persistent cookies will stay with your browser for as long as the time period of the cookie allows.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

I think it keeps user information secure by precluding access to cookies from a third party website.

> Based on what you know, how would you explain CORS?

It implements the same origin policy with the added twist of letting the server determine which third parties can access the cookies.
