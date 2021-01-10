# Chop Suey Backend

This is the API for the project Chop Suey. Chop Suey is a e-commerce website for a restaurants created using Strapi.js, React, Redux and Material UI. This API consist of 3 API end points. Categories, dish and user.

Check out the Front End of this project [Here](https://github.com/DeboDevelop/ChopSuey).

### Requirements

node v10.22.0 or above.

npm v6.14.7 or above.

strapi 3.4.1 or above.

### To Run Locally

1. Clone the repository

2. Install the Dependencies

    `npm install`

3. Run the Server

    - For Development
      `npm run develop`
    - For Production
      `npm run start`

4. Open localhost:1337 to open the application.

5. Create an admin user.

6. Use the application to edit the data, as you please.

### API endpoints

1. http://localhost:1337/categories

Used to GET and POST categories.

2. http://localhost:1337/categories/:id

Used to GET 1, PUT and DELETE a categories.

3. http://localhost:1337/dishes

Used to GET and POST dishes.

4. http://localhost:1337/dishes/:id

Used to GET 1, PUT and DELETE a dish.

5. http://localhost:1337/auth/local/register

Used to register a user using POST request.

6. http://localhost:1337/auth/local

Used to login a user using POST request.

## License

This project is licensed under the GPLv3 License - see the [LICENSE](LICENSE) file for details

# Author

[Debajyoti Dutta](https://github.com/DeboDevelop)
