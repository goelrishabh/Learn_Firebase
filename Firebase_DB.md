# Firebase_DB

Firebase offers two cloud-based, client-accessible database solutions that support realtime data syncing:

- **Cloud Firestore** is Firebase's newest database for mobile app development. It builds on the successes of the Realtime Database with a new, more intuitive data model. Cloud Firestore also features richer, faster queries and scales further than the Realtime Database.
- **Realtime Database** is Firebase's original database. It's an efficient, low-latency solution for mobile apps that require synced states across clients in realtime.

> Both Realtime Database and Cloud Firestore are **NoSQL Databases**.

https://firebase.google.com/docs/database/rtdb-vs-firestore

***For powering a news app, turn-based multiplayer game, or something like  your own version of Stack Overflow, Cloud Firestore will probably look  pretty favorable from a pricing standpoint. For something like a  real-time group drawing app where you're sending across multiple updates a second to multiple people, it probably will be more expensive than  the Realtime Database.***



# DATABASE

>>> [YouTube](https://www.youtube.com/watch?v=v_hR4K4auoQ&list=PLl-K7zZEsYLluG5MCVEzXAQ7ACZBCuZgZ&index=2&t=0s)

##### SQL DB

    > We store the data in the form of a tables!
    > We have schemas i.e Every row in the table is well defined!
    > Strict rules and every column defines what type of data can it take
    > To make the relationship betweens the diff tables we use what called as Foriegn Key (_FK) that points to the ID of other tables data!

- Now all of the above work is done in the BackEnd AND for ease of the above steps we have what called various Databases like SQLite, Postgres, and all sorts of Relational Databases!
- If the Data Becomes Larger and Larger then we need to put this Database on the More Powerful Machines (perfoming operations faster) and this is known as VERTICALY SCALING!


##### NoSQL DB

    > In this we store the data in the form of either:
      > Key-Value pair
      > Nested big JSON tree like structures (pstree command in linux)
      > Json Collections
    > They don't have any schema aka can put any type of data at any point in the DB!
    > Iteration is Easy and less effect on anything else!
    > In this we have to keep duplicates and which leads to MESS
    > Change in One Place will require us to chane it in multiple places!
    > NO NEED TO RUN JOINS or related to fetch the data!

- Now the choice of this type of DB depends on the type of DATA & OPERATIONS performed on it, i.e duplicate if the operation is going to be frequent rather than sticking to the Traditional formats like RDBMS
- We can distribute this data to several machines and know as HORIZONTALY SCALING!

### Cloud FireStore

    > It is Made up of DOCUMENTS & COLLECTIONS
    > Every Collection has Document(s)
    
    > DOCUMENT- Consist Key-Value pairs like JSON refer as Fields and Value can be Anything from String, boolean, binary, arrays, Maps, etc.
      > DOCUMENTS should be less than 1mb else need to breakup them
      > Can't contain another DOCUMENT
      > Can Point to other COLLECTIONS but not DOCUMENTS
      > 
    > COLLECTIONS- Just like HashMap with value being DOCUMENT and nothing else aka image, string, etc...
    
    > Firestore Root can only point to Collection(s)
    > 

>>> [YouTube](https://www.youtube.com/watch?v=v_hR4K4auoQ&list=PLl-K7zZEsYLluG5MCVEzXAQ7ACZBCuZgZ&index=2&t=0s)