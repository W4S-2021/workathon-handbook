# W4S Dashboard

As part of our efforts to include more volunteers in the workathon, a new centralized dashboard is being deployed for volunteers to submit their entries to.

Each volunteer will be given a usernanme and password to login to this private dashboard, where they will see a list of institutions (and number of missing applicants per institution), the number of entries they themselves have found, and the institutions they are currently finding entries for.

Beside each institution in the main table is a "claim" button which allows participants to place a "lock" on a particular institution. This prevents accidental overstepping. Locked institutions are the ones which show up at the top of the screen as "currently being worked on".

After claiming an institution or two, participants then open a page associated with it (we may put existing applicant placement pages here if we have them). On this page is a list of applicants with no placements, where a participant can click on each to submit placement information to. Once submitted, the data is stored in a separate database from the EJM website. 

Once an applicant has a placement, it is put in a list of found applicants (which can be edited later). This decrements the "missing applicant" count on the main page.

Once the workathon is over, a single utility will transfer all the placements from the dashboard to EJM itself (which removes the need for multiple accounts on EJM). The idea is by having a separate, controlled database, it would be faster and safer to record data with high volumes of interaction.
