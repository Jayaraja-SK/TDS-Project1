# TDS-Project1

- I did write a python script to scrape the data by using pagination to get all the records of a specific URL as each one is limited to 30 records, where fetching the users list did require only 14 requests, but for the repos list, once the current page encounters a count of records of less than 30 (or) the page count for the user has exceeded 16, the pointer moved to the next user
- There isn't very high/good relation between the no. of followers and no. of the repos a user has
- As per the Stockholm data, a user being followed by an another one is solely dependent on the quality of work and the community engagement, and not on the no. of repositories
