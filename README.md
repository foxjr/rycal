# rycal
RYCAL is customizable calendar software that auto-allocates time and is based on the concept of Day Types for agenda planning. This idea will develop over time, and is due to my family's obvious need for highly programmable agenda planning software. It will be free, open-source software, and APIs with documentation will be created to allow others to benefit. 

Due to Day Type design, it seems it will lend itself well to an object-oriented approach. I will use python for the original classes because I enjoy coding in python.

---

After doing some brainstorming, I realized it's more about the people. RYCAL groups will be families, and children (in the graph sense) of those groups will be members. RYCAL should work to establish all the correct members of a family with as little input as possible from users. It will be about making sure people are in the right places at the right times, as well as providing an intuitive way to accomplish more tasks. Days will be automatically created based on people, and so all days can be defined as 1 of n types.

There should also be an easy method for data input. I'm thinking we should implement voice commands via audio receiver -> || Platform Interface || -> speech-to-text -> Natural Language Understanding (NLU)/Dialog Management (DM) -> Google Calendar API (for now...)* -> Google Agenda Event/Reminder**. The service could also respond via voice with perhaps a more obvious flow.

---




* This means the service will also be behind a google sign in, which won't hurt -- right now, anyway. 
** So users can also use the Google Calendar app since it's pretty nice and obviates all the calendar server concerns
