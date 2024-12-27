# Gutenburg Blocks Test Environment

A working docker container with Wordpress, a blocks theme ([recommended by this Udemy course](  3 A working docker container with Wordpress, a blocks theme ([recommended by this Udemy course](https://booking.udemy.com/course/gutenberg/)), and updated (Dec. 27th, 2024) composer and npm package specifications.

## Getting the Container Up And Running
1. Clone the repo.
1. `cd` to the root folder and run `docker compose up --detach`
1. Visit `http://localhost:6080`
 - If you get an error, run `docker compose logs -f db` to confirm the database is up and ready for connection.

## Connecting to the Database Locally
### Connection Credentials
- `host=localhost`
- `port=6036`
- `user=test_user`
- `password=test_pass`
- `database=test_db`
