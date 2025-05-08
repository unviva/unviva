This article defines set of principles for next generation software development. It would require introduction of new kind compilers/interpreters with a new understanding.

# Isolation
Code changes doesn't affect the code not being worked on.
When a component proven to be working, it works forever. Unless the component itself modified.

# Story Mode
Application flows in a story mode, rather than trying to cover all possibilities with "if/else"s or loops. Each story has it's own seperate file.

As an example, a user wants to visit profiles of other users, follows the 'profile' story, which includes sub-stories in the same file. such as 'like, message' etc.

Of which main purpose is to prevent bugs.

# Local Data Only
Rather than syncing every action with remote server, it uses local storage only. In such a scenario, each device known as client today, becomes server and data is similar to a whatsapp message of JSON text between 2 devices.

For example, visiting a profile of other, is to make a request from other device, which also stores it's own contacts and likes, posts ...etc. which are sent back to requesting device, similar to text messaging.

In that sense, non-person requests, such as payment, directory (listing)...etc. are also work same. 

Though it relies on connection availability, when it's off, it's off.

# Detached from Properiatery and Rights
Rather than tens of 1000s apps for the same purpose, single or few apps that does the job, globally. Which would be free of ownership. But rather runs with project management.
