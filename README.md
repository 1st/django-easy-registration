django-easy-registration
========================

Django easy registration via email+password, twitter, facebook, google and other OAuth and OpenID services.


Main goal
------------------------

I have found that other "good" solutions like django-registration, djang-social-auth is hard to setup for new project.

Goal of this project - is to help developers to easy and fast setup best user registration (that also support social auth) and start develop their project.

If you can help me - please do this in any time by make push requests, or discuss with me about how can we do this project more easy to use by any Django developer.

How it is works
------------------------

User can login to Django powered website via fast registration:
 - via email and password
   - press "Register" and enter email
   - confiirm email address by press link in received email message
   - fill unique username. Select password
   - also available: reset password; change password; change email with send confirmation message to new email
 - via social network
   - press on link "associate" near the social network name and login to this social network
   - select unique username on website
   - user can add only single association per each social network
   - user can delete any social association. But, he need to have one association, if he have not setup email+password

User can add any number of associations in any time. He can also delete or set email+password asociation at any time.

See also:
 - https://github.com/1st/django-easy-registration/wiki