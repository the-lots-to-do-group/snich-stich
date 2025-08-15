# snich-stich
Let's make sure that snitches don't get stitches.


 ### Basic idea 💡

1. User signs up with a govt id to prevent multiple sign ups per user.
2. User can request an anonymous account upon which a new account Id, password and a gpg key pair is generated. The public key is stored in the original account along with a count for the number of times a new account was created and reset. The other credentials are never stored in the original account.
3. Once an anonymous account is created it by default becomes inaccessible after 6 months unless the original account requests a refresh using the user id and public key.
4. The user is allowed to refresh the anonymous account any number of times to extend its validity for another six months till the validity expires if the user does not refresh during that period.
5. Once the validity of an anonymous account is expired then the user must create a new anonymous account which will have limited permissions for 5 years including not allowed to up vote or down vote but can post, comment and text other users.
6. If a user needs to reset the anonymous account while it is still active, the current anonymous account cannot be refreshed again and the new account will also have limited permissions.
