It is basically a service booking app.

We have 2 groups of users - The clients & The Sub-Contractors

Sub-Contractors have their profiles and their locations saved
Clients have their profiles and locations saved.

There is a list of Services called "Services_List" in the system for which a sub-contractor or a Client can select

The Services_List is provided by the systems administrator.(service_name is Unique)
(we may give a suggestion box to suggest more services if it is not in our list)

Sub-contractor selects a service that he can provide and sets his price for that service

So a service can have many prices but a price is for only one service.
    i.e. a one-to-many relationship hence the Sub_Contractor_Services model
    will have a foreignkey relating it to the Services_List model
    At the same time, the created Sub_Contractor_Service is linked to the particular subcontractor.

