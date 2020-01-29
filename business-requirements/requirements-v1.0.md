## Initial Requirements Brainstorming

1. Basic Chat functions (WhatsApp) with multiple account integration and only for closed user group - only for people in your phonebook and request to connect feature for people outside phonebook

   - basic chat functionality should be ok
   - only allowed for phone book contacts should be ok
   - Request for connection needs to be discussed as it breaks point 2 i.e. only allowing people in the contact book to be added.

   > SK: This would work in case some person has your contact number and wants to get in touch with you so request to add number and accepting request would mean that numbers exchanged only on approval. This would also work for social media page. ( what you post there - text, checkin, I have named it arrive at, picture and if I have responded on that then my contacts would be able to see it but not comment or react on your post, so they would need to add you and if you know the person or want to know the person, then you would accept his/her request and acceptance means phone numbers exchanged, gets accountability and keeping in touch gets real)

2. Lock individual chat/groups

- Locking should be ok
- need to make sure of the strategy which is required for locking the chats

> SK: like in WhatsApp there is an option to archive, we would give option of moving the group or individual chat to locker. Password can be set through lock settings in main settings.

3. UPI payment gateway

- this is a 3rd party integration
- need to go through the options that the payment gateway provides before we can connect
- there might be security considerations from the gateway that need to be understood
- normally, there is an OTP process so that is an extra step that needs to be done
- as a feature it makes sense

> SK: For this I have already tied up with YES Bank for their UPI payment gateway. I can connect you with the tech team. They have 50+ APIs for use cases.

4. Audio Calling & Video Calling ( You have to suggest can we do it in 1st phase both, or in 2nd alternately, either audio first and video later???)

- I would not go for this initially
- reason being that audio and video calling is dependent on the VOIP protocol that is dependent on the ISP's
- need to look a bit more into it

5. Filter option for filtering chat ( parameters like Contacts currently online, unread messages, friend requests, size, frequently contacted etc)

- we should have this feature
- need to decide on the number of filters that might be provided to the user
- filtering and sorting are two different things. you would like to think about that
- search is another feature which is different from filtering

> SK: Search icon would be anyway there. Filter is to filter out the main chat window and show on the screen those chats according to the user selected parameters. Eg 1- if you have unread chats in WhatsApp you have to scroll down to actually land on those chats.

> SK: if you want to see online friends you can select online from filter and it will filter out those friends who are online ( for users h=who have hidden their online status, they will not show. In WhatsApp you have to actually open the chat window of a particular friend to see if they are online or not . OR sort can be used to sort according to the selected parameter. I mean any one can be used - Filter or Sort

6. Poll option within group

- creating polls in itself is not a big issue here
- saving polls and making them available is another thing
  > SK: Download Telegram to understand better. Will make a group with you and Roopsi to show you poll feature.
- keeping track of the individual polls w.r.t. the chats or groups needs to be thought through
  > SK: Polls increases user engagement

7. Commenting/reacting with slap, hug,lol on DP / status messages

- should be ok
- more of a design problem rather than implementation - OK

8. In WhatsApp status button in footer we can give BeeSocial button with message (Your personal social media coming soon and work on it in the 2nd phase)

- ok - OK

9. Calendar in groups to schedule activity for group members ( Can we do this in first phase??)

- what kind of activities are we talking about?
  > SK: any event can be created for meeting, going out etc for particular individual or within group. Like you create in Outlook.
- what type of calendar apps are we talking about?
  > SK: No outside apps

10. Share text, photo, Location, file (Size can we give till 1.5Gb??).

- sharing text is not an issue
- sharing location is not an issue
- sharing file has database considerations as we need to host those files - OK

11. Group formation (How many members can we add?? Like telegram gives upto 100000 members)

- not sure about this
- normally number of users to be allowed would depend on the efficiency of the app and the database considerations as you would need to save all these combinations somewhere till the time the group is active
- we also need to remove the data once the group has been dissolved - OK

12. Customisation of Online status ( like if you can hide)

- should be ok - OK
