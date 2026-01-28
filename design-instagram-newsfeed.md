## Deciding Requirements 

### Functional Requirements
things are obvious that needed in the app

- user should able to create/delete post
- user should able to follow and unfollow other users
- able to scroll through newsfeed that is consist of there following posts from newest to oldest
- able to like and comment
- able to get notfications, they get notified when another user like and comment on there posts

### Non-Functional Requirements
thinks that are needed to run smoothly

- Availabilty, it should available 99.999% uptime
- Eventual consistency, if a user post something, its ok if it doesn't show up immediatly. but appears within a few seconds (1-2 seconds)
- Latency, if we click something then it should load within 1-2 seconds not more then that
- Scalibility, The system should scale through the globe, with 500M active users and 2B monthly active users
- Extensibility, System should be extensible more feature can join in future
- Usablity, the system should be highly useable, things should load fast and in a responsibe way
