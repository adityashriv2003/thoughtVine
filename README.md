# cloudSEKpost-comment

## Tech Used
1. Node.js
2. Express.js
3. MongoDB
4. Mongoose

## Post - Comment Service
This website allows users to create accounts or log in to existing ones. Once logged in, they can create text posts and optionally add images. Other users can view these posts and leave comments. Users can also edit or delete their comments at a later time.

## Architecture
1. **Express.js**: Used to build the server.
2. **MVC**: Followed for structuring the application.
3. **Handlebars**: Used for rendering dynamic content in place of HTML.
4. **MongoDB Atlas**: Used to store the data.
5. **Authentication Service**: Implemented as a security measure.

## Why MongoDB?
1. **Schema Flexibility**: Accommodates varied post and comment formats without strict schemas.
2. **Scalability**: Scales horizontally to handle growing data volumes and user traffic.
3. **High Performance**: Delivers fast read and write operations, especially when optimized.

## Instructions to Run
1. Create a free cluster on MongoDB Atlas and replace the URL in the `.env` file to connect the database properly.
2. The website will be hosted on http://localhost:3030/.
3. Run `npm start` (if you have the npm module).
4. If the database connection is successful, you'll see the message "Database connected".
