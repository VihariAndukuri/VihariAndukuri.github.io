---
layout: post
title: Re-type Password must go
---



When users want to try out a new website or app, one of the first steps they encounter is the sign-up flow. This stage is crucial, as it is where a significant number of users drop off. The sign-up form is also one of the first impressions users have of the website or app.

As a user, one of my pet peeves about sign-up forms is being asked to re-enter my password. Even worse is when the form doesn’t show what I typed, making me second-guess whether I entered my desired password correctly without any typos.

In this post, we will explore the various ways sign-up forms require users to set passwords, the rationale behind these designs from the perspective of a Product Manager/Product Designer, and why these methods can cause frustration for users



## Re-Enter Password

Perhaps one of the earliest and most enduring designs for sign-up forms, this layout has been a staple since the early days of the internet.

![Grab]({{site.baseurl}}/assets/posts/password/confirm.png)

Its simplicity is notable: users are prompted to enter a password and then re-enter it to confirm, ensuring no typos slip through. The password is masked, ostensibly to protect against prying eyes. 

This is a design pattern, that in my opinion, needs to die.

<br>

#### Usability Issues

* The re-enter password field adds unnecessary work for the user without providing significant benefits. Experiencing friction at the sign-up stage can cause a substantial number of users to abandon the process.
* Passwords are masked, which is generally good for security. However, since the user cannot see what they are typing, the chances of making typos increase.
* If the user mistypes the password in either the 'Password' field or the 'Re-Enter Password' field, they have no way of knowing where the mistake occurred. The only solution is to re-type both fields, adding further frustration.

Amazon's Sign Up flow exhibits these usability issues.

![Amazon]({{site.baseurl}}/assets/posts/password/amazon.png){:height="1000px" width="610.33px" }



## Masking the Password

Some Sign Up forms do not ask the user to re-enter or confirm the password. However, they don't allow the user to see what they had typed in either

#### Usability Issues

* Since users cannot see what they are typing, the chances of making typos increase, leading to reduced confidence in what they have entered.
* If a user makes a typo when setting the password, they will face login issues when trying to log in for the first time. This could inevitably lead to frustration and result in the user giving up and never returning to the app or website.

Facebook's Sign Up flow uses this method.

![Facebook]({{site.baseurl}}/assets/posts/password/facebook.png){:height="1000px" width="610.33px" }

<br>

## Better UX: Show/Hide Password

The 'Re-Enter Password' field is, no doubt, well-intentioned. It ensures that the user enters the correct password.

A simple way to achieve this without causing usability issues is by providing a button or checkbox to show/hide the password. By allowing the user to see what they are typing, we can avoid forcing them to type it again. This also saves the user from the frustration of making a typo when setting up their password.

![Instagram]({{site.baseurl}}/assets/posts/password/instagram.png){:height="1200px" width="810.33px" }



## Best UX: Show/Hide Password + Validation Rules

Is it possible to improve on the previous design? Yes! Simply state the password rules clearly without making users jump through hoops.

Target's Sign Up process has one of the best UX I have ever come across so far.

It clearly lists down the requirements in plain language. It specifies that the password must contain 8-20 characters. It also mentions that the password should satisfy at least 2 of the additional requirements.

![Target]({{site.baseurl}}/assets/posts/password/target.png){:height="1500px" width="1110.33px" }

These designs show how the workflow of setting up a password in Sign Up can be greatly simplified without any major technical efforts or design overhaul. The improved UX would enable the users to sign up faster and provide a satisfying user experience. 
