# Prime-Estate
A Real-Estate Mern Stack App

Prime Estate is a comprehensive real estate web application developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to browse, search, and interact with property listings, while also providing agent contact and user profile management capabilities. The project leverages various supporting technologies like Tailwind CSS, Vite, React Redux, JWT, and Firebase to deliver a robust and feature-rich user experience.

## Key Features

1. **User Authentication**: Users can sign up, log in, and even sign in through their Google accounts to access personalized features. This includes the ability to manage their profiles and create their own property listings.

2. **Property Listings**: The application displays a list of available properties fetched from the backend database. Users can view detailed information about each property, including images, location, description, price, and amenities.

3. **Filtering and Sorting**: The website offers extensive filtering options, allowing users to refine property listings based on criteria such as amenities, offers, and property type. Additionally, users can sort the listings by price and time to find the most relevant properties.

4. **Search Functionality**: Users can search for properties using keywords or specific criteria, making it easy to find the perfect home or investment.

5. **Agent Contact**: Prospective buyers or renters can contact real estate agents directly through the application for inquiries or property viewings. This feature is integrated with email functionality for seamless communication.

6. **User Profile**: Authenticated users can update their profiles and create their own property listings using the CRUD (Create, Read, Update, Delete) functionality provided by the application.

7. **Responsive Design**: The website is designed to be responsive and optimized for various devices and screen sizes, ensuring a consistent and user-friendly experience across desktop and mobile platforms.

## UI (User Interface)

The Prime Estate website features a visually appealing and intuitive user interface built using React.js and Tailwind CSS. The application's layout is divided into several key sections:

1. **Header**: The header includes the Prime Estate logo, a search bar, and navigation links for Home, About, and Sign In.

2. **Property Listings**: The main section of the website displays a grid of available property listings, each with a preview image, location, price, and other key details.

3. **Filtering and Sorting**: The sidebar on the left-hand side allows users to filter and sort the property listings based on various criteria, such as property type, amenities, and price range.

4. **Property Details**: When a user clicks on a specific property listing, they are taken to a detailed view that showcases additional information about the property, including high-quality photos, a description, and contact information for the real estate agent.

5. **User Profile**: Authenticated users can access their profile page, where they can update their personal information and view or manage their own property listings.

6. **Responsive Design**: The website's user interface is designed to be responsive, ensuring a seamless experience across various devices, from desktop computers to mobile phones and tablets.

## Backend

The backend of the Prime Estate application is built using Express.js, a popular Node.js framework. The backend is responsible for handling the following key functionalities:

1. **API Endpoints**: The backend exposes a set of RESTful API endpoints that allow the frontend to fetch property listings, user data, and other relevant information.

2. **User Authentication**: The backend manages user authentication and authorization using JSON Web Tokens (JWT). This includes handling user sign-up, sign-in, and profile management.

3. **Property Management**: The backend provides CRUD (Create, Read, Update, Delete) operations for property listings, allowing users to add, update, and remove properties from the system.

4. **Database Integration**: The backend integrates with a MongoDB database to store and retrieve property and user data. It uses Mongoose, an Object Document Mapping (ODM) library, to interact with the MongoDB database.

5. **Email Integration**: The backend includes functionality to send email notifications to users, such as when a user contacts a real estate agent or when a property is added to the system.

6. **Error Handling and Logging**: The backend implements robust error handling and logging mechanisms to ensure the application's stability and aid in troubleshooting.

## Technologies Used

- **Frontend**: React.js, Tailwind CSS, Vite, React Redux, JWT
- **Backend**: Express.js, Node.js, MongoDB, Mongoose, JWT
- **Additional Services**: Firebase (Authentication, Storage, Real-time Database, Analytics)

## Installation and Setup

1. Clone the repository:

git clone https://github.com/Sumit-J99/Prime-Estate2.git


2. Navigate to the project directory:

cd Prime-Estate


3. Install dependencies for both frontend and backend:

npm install
cd client && npm install


4. Set up environment variables:
   - Create a .env file in the root directory and add the necessary environment variables.
   - Also, create a .env file in the client directory and add the required environment variables.

5. Start the backend server:

npm run dev


6. Start the frontend development server:

cd client && npm run dev


7. Open your browser and navigate to the local development server URL to view the application.

## Contributing

If you would like to contribute to the Prime Estate project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure the project is still functioning correctly.
4. Push your changes to your forked repository.
5. Submit a pull request, detailing the changes you've made and the problem you've solved.

## License

This project is licensed under the [MIT License](LICENSE).

# Deployment 
The Project is Deployed at link  : https://prime-estate2.onrender.com/
