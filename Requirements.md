# Requirements #
The system requirements are outlined below.
## Summary ##
> The system is a web and Android crowdsourcing application that collects user-created information about a broad array of topics. Users who are interested  in a spesific topic can add new content, comment on existing posts, rate content, and view content. The system uses semantic tags to connect related topics into a web of information so that users can explore topics in a cohesive, non-compartmentalized manner.


## Glossary ##
**user:** any person who uses the system whether logged in or not

**post:** a page containing information on a topic

**administrator:** person who has full access to the system and is responsible for managing and supporting a computer system or network

**comment:** response of a user to a content, written under ‘comments’ sections

**profile:** a brief description that provides information about user with photos, personal interests, post history, etc.

**rating:** a number that correlates to the usefulness or integrity of a post, comment or user

**tag:** a keyword that is assigned to the piece of information of the content that allows for relating similar content

**crowdsourcing:** the process of obtaining needed data from a large group of people.

**version:** a form of a post at a point in time

**system:** software that can be used through the web or mobile applications

**web client:** the part of the software that is shown to the user through the web

**mobile application:** a computer program designed to run on mobile phones and tablets that displays the system to the user

# 1.Website Requirements #
  * **1.1 Functional Requirements:**
    * **1.1.1 The system shall require new users to fill a signup form and submit it.**
      * 1.1.1.1 All users shall enter a unique username.
      * 1.1.1.2 All users shall enter a password.
      * 1.1.1.3 Users shall give extra optional information about themselves if they desire.
    * **1.1.2 The users shall sign into the system with their username and password.**
      * 1.1.2.1 There shall be a feature to retrieve lost/forgotten passwords.
      * 1.1.2.2 Users shall be able to update personal data on their profile.
      * 1.1.2.3 Users shall have options for privacy and security.
    * **1.1.3 The users shall be able to add content to the website.**
      * 1.1.3.1 The user shall be able to to edit posts.
      * 1.1.3.2 The user shall be able to comment on posts.
      * 1.1.3.3 The user shall be able to tag content semantically.
      * 1.1.3.4 The system shall inform the user about similar posts to prevent duplicates.
    * **1.1.4 The users shall be able to view the posts without logging in.**
    * **1.1.5 The system gives recommendation to users about similar and related contents.**
      * 1.1.5.1 The system shall link related topics and posts.
    * **1.1.6 The system shall provide a rating mechanism for content and users.**
      * 1.1.6.1 The system shall order content according to ratings.
      * 1.1.6.2 The user shall be able to rate content.
      * 1.1.6.3 The system shall be able to calculate a user’s rating by considering his/her content’s ratings.
      * 1.1.6.4 The user shall be able to see the rating of content.
      * 1.1.6.5 The user shall be able to see the rating of any users.
      * 1.1.6.6 The user shall be able to see the author of posts and his/her rating.
      * 1.1.6.7 The user shall be able to rate other users.
    * **1.1.7 The system shall be able to provide a version system.**
      * 1.1.7.1 The version of a content shall be changed when a user edits it.
      * 1.1.7.2 The user shall be able to see the version history of a content.
    * **1.1.8 The system shall provide a reference system.**
      * 1.1.8.1 The user shall be able to provide internal and external links on his/her posts.
      * 1.1.8.2 The user shall be able to share his/her posts on social media.
    * **1.1.9 Users shall be able to follow other users.**
      * 1.1.9.1 Users shall receive notifications about posts which are added or updated by users they follow.
    * **1.1.10 The users shall be able to report posts which lacks quality or not related to the topics they are linked.**
      * 1.1.10.1 The administrator shall be able to delete reported posts.
      * 1.1.10.2 The administrator shall be able to ban a user who owns reported posts.
    * **1.1.11 The system shall be searchable.**
      * 1.1.11.1 The user shall be able to explore topics by searching tags or key words.
      * 1.1.11.2 The user shall be able to search for users.
      * 1.1.11.3 The system shall return results which are semantically linked with what the user searches.
      * 1.1.11.4 The system shall order the results according to their ratings.
    * **1.1.12 The user shall be able to create posts.**
      * 1.1.12.1 The user shall be able to contribute by creating a new post and adding information to it.
      * 1.1.12.2 The user shall be able to create as many posts as he/she wants.
    * **1.1.13 The user shall be able to create topics.**
      * 1.1.13.1 The user shall be able to add posts only under topics and these posts shall be related to the topic they are assigned to.
      * 1.1.13.2 The user shall be able to link any two topics if he/she thinks they are related enough.
      * 1.1.13.3 The user shall be able to see additional topics it is linked when he/she picks any topic.
  * **1.2 Non-Functional Requirements:**
    * **1.2.1** **The system shall operate in a secure manner.**
      * 1.2.1.1 Confidential user information, such as passwords or telephone number, shall be hidden.
      * 1.2.1.2 The system shall have security measures against attacks and hacking attempts.
    * **1.2.2 The registration to the system shall be free of charge.**
      * 1.2.2.1 The terms may be changed and all users must be informed about this.
    * **1.2.3 The system shall be efficient.**
      * 1.2.3.1 Pages shall be loaded in short time which doesn't disturb the user .
      * 1.2.3.2 The system shall be recoverable without seriously affecting the user's experience..
    * **1.2.4 The system shall be easy to use and accessible.**
      * 1.2.4.1 The system shall provide a user friendly, easy to use interface.
      * 1.2.4.2 The system shall be designed for use by people with minimal computer knowledge.
    * **1.2.5 The web client shall be compatible with the most popular browsers used in the last five years and Android smart phones.**
    * **1.2.6 The web page content shall be fully compliant with international laws.**
      * 1.2.6.1 The system shall provide a means of reporting illegal/unethical issues to admins.
      * 1.2.6.2 The website shall present necessary copyright text and warnings for users.

# 2.Mobile Application Requirements #
  * **2.1 Functional Requirements:**
    * **2.1.1 Same as Website Functional Requirements, outlined in 1.1.**
    * **2.1.2 A notification system will be implemented.**
      * 2.1.2.1 Notifications shall be pushed instantly to the user’s mobile phone.
      * 2.1.2.2 Users shall be able to disable notifications to their phone.
  * **2.2 Non-Functional Requirements:**
    * **2.2.1 The mobile application shall be run on the Android platform.**
    * **2.2.2 The mobile application shall be implemented using Java language.**