# Sequence Diagrams #

## Use Case 2 ##
  * **Actors:** Registered User
  * **Purpose:** Add a post
  * **Preconditions:**
    * User must login to the system.
    * User must select a topic in order to add post.
  * **Action Items:**
    * User will open a topic which he/she wishes to add post on
    * User will click the “Write a post” button.
    * A text box will be opened at the bottom of the page.
    * User will write his/her content in the text box for the post.
    * User will click “Enter” on his/her keyboard or the “Share” button on the bottom of the text box.
  * **Postconditions:**
    * The post will be added to the profile page of the commenter.
    * The post will be visible by quests and registered users who view that topic.
    * The post may be rated by other registered users.


http://i.imgur.com/QmzMGll.jpg?1

## Use Case 3 ##
  * **Actors:** Registered User
  * **Purpose:** Add a comment
  * **Preconditions:**
    * User must login to the system.
    * User must select a post in order to comment.
  * **Action Items:**
    * User will open a post which he/she wishes to comment on
    * User will click the “Write a comment” button.
    * A text box will be opened at the bottom of the page.
    * User will write his/her comment in the text box.
    * User will click “Enter” on his/her keyboard or the “Share” button on the bottom of the text box.
  * **Postconditions:**
    * The comment will be added to the profile page of the commenter.
    * The comment will be visible by quests and registered users who view that post.
    * The comment may be rated by other registered users.

## Use Case 4 ##
  * **Actors:** Registered User
  * **Purpose:** Log in
  * **Preconditions:**
    * User must have an account in the system.
    * User shall provide correct username and password.
  * **Action Items:**
    * User will enter his/her username and password.
    * System will check the information provided by the user.
  * **Postconditions:**
    * User will login to the system and will be directed to his/her homepage if the username password combination is correct.
    * User will be informed if the username/password combination is not correct.

## Use Case 6 ##

  * **Actors:** Registered User
  * **Purpose:** Rate a Post
  * **Preconditions:**
    * User should have and account and login.
    * There should be at least one topic and one post in that topic
  * **Actions**
    * User sees a topic
    * User clicks on that topic and sees posts in it.
    * User chooses a post to be liked and click “Like” button in this post.
  * **Postconditions:**
    * This post’s rating will be updated.
    * If it is necessary, order of posts under the topic will be re-arranged.

## Use Case 14 ##
  * **Actors:** Registered User
  * **Purpose:** Rate a comment
  * **Preconditions:**
    * User must have an account and login.
    * User must choose a comment to rate.
  * **Actions:**
    * User will open a post.
    * User will scroll down the post page.
    * User will click "like" or "dislike" depending if he/she liked it or not.
  * **Postconditions:**
    * System will recalculate the rating of the post.
    * The new rating of the post will be visible by all users.
## Sequence Diagram For Use Cases 3-4-6-14 ##

![http://i.imgur.com/2yi0edC.png](http://i.imgur.com/2yi0edC.png)

## Use Case 5 ##
  * **Actors:** Registered User
  * **Purpose:** Follow a user
  * **Preconditions:**
    * User must have an account in the system.
    * The user must login to the system.
    * There are at least one or more other registered users in the system.
  * **Action Items:**
    * User will go to a user's profile page that the user wants to follow.
    * User will click the "Follow" button.
  * **Postconditions:**
    * The user will see posts by the followed user on his/her home page.
    * The followed user will be informed that they have a new follower.

## Sequence Diagram For Use Case 5 ##

![http://i.imgur.com/5OgP1Sg.jpg](http://i.imgur.com/5OgP1Sg.jpg)

## Use Case 1 ##
  * **Actors:** Guest
  * **Purpose:** Sign-up
  * **Preconditions:**
    * User must have an email address.
    * User must choose an appropriate and unique username and password.
  * **Action Items:**
    * User will click sign up button.
    * User will be directed to sign up page.
    * User will enter his information needed to become a member.
    * User will push “sign up”.
  * **Postconditions:**
    * An account will be created for the user with the information provided by the user.

## Sequence Diagram For Use Case 1 ##

![http://i.imgur.com/s0Mdw3i.png](http://i.imgur.com/s0Mdw3i.png)

## Use Case 8 ##
  * **Actors:** Registered User
  * **Purpose:** Report a post
  * **Preconditions:**
    * User must have an account and logged in.
    * User must open a post and decide to report that post.
  * **Action Items:**
    * User will open a post
    * User will click the “Report this post” button.
    * User will choose a cause of report from a given “list of causes” or write the cause in his/her own words.
    * User will click “Send Report” button.
  * **Postconditions:**
    * Report will be sent to the admin of system.
    * Admin will evaluate the report and post and then determine what to do.(delete post, ban user, or nothing)

## Use Case 9 ##
  * **Actors:** Registered User
  * **Purpose:** Report a comment
  * **Preconditions:**
    * User must have an account and logged in.
    * User must open a post then view the comments of the post and decide to report a comment of that post.
  * **Action Items:**
    * User will open a post
    * User will view the comments of the post.
    * User will click the “Report this comment” button.
    * User will choose a cause of report from a given “list of causes” or write the cause in his/her own words.
    * User will click “Send Report” button.
  * **Postconditions:**
    * Report will be sent to the admin of system.
    * Admin will evaluate the report and comment and then determine what to do.(delete comment, ban user, or nothing)

## Use Case 10 ##
  * **Actors:** Admin
  * **Purpose:** Delete a comment
  * **Preconditions:**
    * The comment must be reported by a user.
    * Admin can find a comment inappropriate.
  * **Action Items:**
    * Admin will click on the comment.
    * Admin will choose delete option.
    * Admin will approve that option.
  * **Postconditions:**
    * System deletes the comment and make it invisible to  all users.

## Use Case 11 ##
  * **Actors:** Admin
  * **Purpose:** Delete a post
  * **Preconditions:**
    * The post must be reported by a user.
    * Admin can find a post inappropriate.
  * **Action Items:**
    * Admin will click on the post.
    * Admin will choose delete option.
    * Admin will approve that option.
  * **Postconditions:**
    * System deletes the post and make it invisible to  all users.

## Use Case 13 ##
  * **Actors:** Guest and Registered User
  * **Purpose:** View a post or comment
  * **Preconditions:**
    * There is no precondition for that guest user just enter the website.
    * If registered user want to view with his/her account, he/she should sign-in but to view a post or comment sign-in isn't necessary.
  * **Action Items:**
    * Guest or registered user will search a post or he/she reads a post from homepage.
    * Guest or registered user will scroll down the page and read comments.
  * **Postconditions:**
    * There is no postcondition.

## Use Case 15 ##
  * **Actors:** Registered User
  * **Purpose:** Create a Topic
  * **Preconditions:**
    * User should have and account and login.
    * There should be no topic as “Hisarüstü Subway Station”

  * **Actions:**
    * User clicks “Create New Topic” button.
    * Enters topic name.
    * User writes his questions, observations or gives information that he already knows about this issue.
    * User clicks "Ok" button to create topic.

  * **Postconditions:**
    * A new topic “Hisarüstü Subway Station” is created. This topic has a node representation on our topic graph.
    * This node put in to graph with no incoming or outgoing arrows.

## Use Case 16 ##
  * **Actors:** Registered User
  * **Purpose:** Create a Relation
  * **Preconditions:**
    * User should have and account and login.
    * Two topics should exist in the database.

  * **Actions:**
    * User clicks "Create a Relation" button.
    * User enters related topics' headers.
    * User clicks Create Relation to apply changes.

  * **Postconditions:**
    * Now this two topics considered as related and they are shown in graph with a line between them.

## Use Case 19 ##
  * **Actors:** Registered User
  * **Purpose:** Add Tag to a Post.
  * **Preconditions:**
    * User should have and account and login.

  * **Actions:**
    * User click on a post and then click the "add tag" button.
    * User write the name of the tag opened text box.
    * Then user click the "OK" button.

  * **Postconditions:**
    * System adds the tag to the post.
    * Also system add this tag to the topic which contains that post.

## Sequence Diagrams For Use Cases 8-9-10-11-13-15-16-19 ##

![http://i.imgur.com/OKjS01S.jpg](http://i.imgur.com/OKjS01S.jpg)