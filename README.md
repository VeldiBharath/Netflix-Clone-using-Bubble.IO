# Netflix-Clone-using-Bubble.IO
Netflix Clone using No Code Environment


# Netflix clone build

## Database

## User

- [ ]  Name
- [ ]  Profile photo - Upload default image
- [ ]  Bookmarks - List of content
- [ ]  Profile type - Linked to profile type option set with default of user

## Content

- [ ]  Title
- [ ]  Thumbnail image
- [ ]  Description
- [ ]  Genres - List linked to genre option set
- [ ]  Rating - Linked to rating option set
- [ ]  Published year
- [ ]  Content-type - Linked to content type option set
- [ ]  Movie file - Linked to movie content data type
- [ ]  TV seasons - List of seasons data type
- [ ]  Is-published - Yes/no with no default

## Season

- [ ]  Season number - set as a number type
- [ ]  Episodes - List of episodes

## Episode

- [ ]  Episode-number - Set as a number
- [ ]  Title
- [ ]  Thumbnail image
- [ ]  Description
- [ ]  File - set as a file type

## Movie content

- [ ]  File

## Option sets

## Content type

- [ ]  Movie
- [ ]  TV Show

## Genre

- [ ]  Comedy
- [ ]  Action
- [ ]  Family
- [ ]  Drama
- [ ]  Thriller

## Rating

- [ ]  G
- [ ]  PG
- [ ]  M
- [ ]  MA
- [ ]  R

## Profile type

- [ ]  User
- [ ]  Admin

## Features

- [ ]  Building the user registration page
    - [ ]  Designing the first group
    - [ ]  Building the workflows

- [ ]  Processing a subscription payment
    - [ ]  Designing the second group for the registration process
    - [ ]  Building the workflow to hide/show relevant groups
    - [ ]  Building the workflow to process a payment & sign the user up
    - [ ]  Connecting Stripe API keys
    - [ ]  Creating a new subscription product in Stripe (create in both dev & live environments)
    - [ ]  Reviewing active subscriptions Stripe account
    - [ ]  *Full Stripe subscription tutorial [here](https://www.youtube.com/watch?v=EAhrfR62q1c)*

- [ ]  Building the user login feature
    - [ ]  Designing the new group
    - [ ]  Building the workflow to hide/show the relevant group
    - [ ]  Building the workflow to log a user in

- [ ]  Designing the home page
    - [ ]  Designing the featured section
    - [ ]  Displaying a list of additional content based on its category
    - [ ]  Creating a redirect on home page if user is not logged in

- [ ]  Building the navigation menu
    - [ ]  Building a reusable element
    - [ ]  Building the navigation workflows
    - [ ]  Adding navigation menu to home page

- [ ]  Making the navigation menu mobile responsive
    - [ ]  Building the mobile dropdown menu
    - [ ]  Creating the workflow to display dropdown menu
    - [ ]  Adding responsive conditions
    - [ ]  Rebuild navigation workflows for the mobile menu

- [ ]  User settings page
    - [ ]  Designing the page
    - [ ]  Building the workflows to update user details
    - [ ]  Displaying initial content

- [ ]  Building an admin dashboard
    - [ ]  Building the workflow to redirect to the admin dashboard page
    - [ ]  Displaying a list of uploaded content
    - [ ]  Create a search filter
    - [ ]  Making the page responsive

- [ ]  Creating/uploading a movie
    - [ ]  Building a navigation workflow from the admin dashboard page
    - [ ]  Designing the first group
    - [ ]  Designing the second group
        - [ ]  Updating the limit on the file uploader element
    - [ ]  Building the workflow to create a new piece of content
        - [ ]  Storing the new piece of content in a custom state
    - [ ]  Building the workflow to upload a movie file
    - [ ]  Creating a redirect workflow if a users account isn’t an admin
    - [ ]  Creating the condition on the button that sends someone to the admin dashboard page
    - [ ]  Building the workflow to send someone back to the admin dashboard page

- [ ]  Creating/uploading a TV show
    - [ ]  Designing the dedicated group
    - [ ]  Building the workflow to create a new season
    - [ ]  Dislaying all of the seasons within a show
    - [ ]  Designing the group to create episodes within a season
        - [ ]  Updating the limit on the file uploader element
        - [ ]  Building the workflow to display this hidden group
    - [ ]  Building the workflows to create episodes within a season
    - [ ]  Displaying all of the episodes within a season
    - [ ]  Building the workflow to show/hide the overall TV show group

- [ ]  Editing the details of existing content
    - [ ]  Sending a URL parameter through a navigation event
    - [ ]  Build workflow on the ‘create’ page to extract URL and store a value in the page’s existing custom state
    - [ ]  Creating conditions to display initial content in all fields
        - [ ]  Main group
        - [ ]  Movie group
    - [ ]  Building the workflow to edit the details of an existing content
    - [ ]  Adding conditions to the existing workflow that creates new content
    - [ ]  Add condition on the ‘create button’ to display the word ‘update’

- [ ]  Previewing the details of a show/movie
    - [ ]  Building a reusable element
    - [ ]  Displaying the details of the content
    - [ ]  Displaying the list of episodes for a tv show
        - [ ]  Designing the elements
        - [ ]  Adding conditions to hide/display elements
        - [ ]  Updating the datasource for the repeating group
    - [ ]  Displaying a list of relevant shows/movies
    - [ ]  Adding reusable element onto the home page
    - [ ]  Building the workflow to display the popup

- [ ]  Creating a custom search feature
    - [ ]  Building the search workflow from the navigation menu
    - [ ]  Building the search results page
    - [ ]  Adding the content preview popup
    - [ ]  Building the workflows to display the popup

- [ ]  Building the pages to display all movies & TV shows
    - [ ]  Building the movies page
        - [ ]  Designing the page
        - [ ]  Updating the data source for each repeating group
        - [ ]  Adding the reusable content preview popup
        - [ ]  Building the workflows to display the popup
    - [ ]  Building the TV show page
        - [ ]  Designing the page
        - [ ]  Updating the data source for each repeating group
        - [ ]  Adding the reusable content preview popup
        - [ ]  Building the workflows to display the popup

- [ ]  Bookmarking content to my list
    - [ ]  Building the workflow to add content from bookmarks list
    - [ ]  Adding the condition on the element
    - [ ]  Building the workflow to remove content from bookmarks list
    - [ ]  Creating a page to view bookmarked content
        - [ ]  Designing the page
        - [ ]  Adding the reusable element to preview content
        - [ ]  Building the workflows to display the reusable element

- [ ]  Building the feature to stream content
    - [ ]  Building a dedicated page
    - [ ]  Building a workflow to navigate to the page
    - [ ]  Installing & configuring the video streaming plugin

**Additional features:**

- Restricting content by regions - tutorial [here](https://www.youtube.com/watch?v=REj06FM4IYI&t=3s)
- Creating multiple user accounts

