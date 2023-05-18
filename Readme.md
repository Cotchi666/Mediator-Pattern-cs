In this section C#:
We're gonna be learning how to use Mediator Pattern.

In general, when we wanna send a notification to the users, we've to know exactly what reference of those users and use that reference, we're able to call the method of the users. But what happens if we have thousand or milion users. It's gonna be tricky.

With that being said, the problem could be fixed with MEDIATOR PATTERN.
<br/>
(***** each other user must have its meditor *****)
<br/>
We just create the one "Mediator" which contains list of users and when a new user created, the meditor will recognize that user and sign it, so on... You send a notification at this time, the mediator's about to check the list of user, then do this method.

- Reference: <a href="https://www.google.com/" target="_blank">MEDIATOR</a>
