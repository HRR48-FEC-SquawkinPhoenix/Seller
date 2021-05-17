# Seller

> This is an information section with item description, shipping calculator and seller's info.


## Related Projects

  - https://github.com/HRR48-FEC-SquawkinPhoenix/ImageCarousel
  - https://github.com/HRR48-FEC-SquawkinPhoenix/Add-To-Cart
  - https://github.com/HRR48-FEC-SquawkinPhoenix/Reviews


## Usage
1. Run 'npm install' from the root. This installs the necessary dependencies for the service to run.
1. Run 'npm run build' from the root. This will bundle the React components into a single file by webpack and babel that is run as a script from the index.html file.
1. Ensure that a MySQL database server is running, and the user root has password as 'password', or you can manually change it to fit your MySQL username and password in ./database/index.js.
1. run 'npm run seed' from the root. This will create the database and tables this service relies on and seed the tables with some example data. You may need to run it multiple time if error occurs.
1. Run 'npm run start' from the root. The MySQL server with the database seeded in the previous step must still be open. This will start an Express server on port 3004, and the server will respond to a request to root by serving up a static file--the index.html that runs our bundle created in step 2.
1. Once the Express server is running, the service can be accessed at 'http://localhost:3004'.
