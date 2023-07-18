# Pizzeria - Website 🍕🍹🍽️

This project is a website for a pizzeria, where customers can view the menu of pizzas and beverages 🍕🍹, learn about the location and opening hours 🗺️⏰, and get information about the pizzeria's mission, vision, and values 🚀.

## Key Features 🎯

- **Pizza and Beverage Menu**: Users can explore the available pizza and beverage menu at the pizzeria. Each menu item displays an image, name, description, and price 💰.

- **Location and Contact**: The pizzeria's location is showcased on a Google Maps map along with the address and contact phone number ☎️. Customers can also communicate via WhatsApp with just one click 📲.

- **Dark Mode**: A "Dark Mode" button is implemented to allow users to switch between light and dark appearances based on their preferences 🌙.

- **Mission, Vision, and Values**: The pizzeria shares its mission, vision, and values in a dedicated section for customers to better understand the company's philosophy 🌟.

- **Real-Time Updates**: The menus and the Mission, Vision, and Values section are automatically updated in real-time using Firebase Cloud Firestore ⚡️. This allows the page administrator to modify menu items and other relevant information from a Firebase control panel.

- **Image Storage**: Firebase Storage is used to store pizza and beverage images, enabling high-quality image loading and display on the page 🖼️.

## Technologies Used 🛠️

- **HTML**: The basic structure of the webpage is implemented using HTML.

- **CSS and Bootstrap**: CSS is used for styling the page, and Bootstrap is employed to enhance appearance and responsiveness.

- **JavaScript, Firebase Firestore, and Storage**: JavaScript handles dynamic functionality, and Firebase Firestore is used as the database to store and update menu items and company information in real-time. Firebase Storage is used to store and retrieve pizza and beverage images.

## Installation and Setup 🚀

1. Download the repository or clone the project to your local machine.

2. Open the `index.html` file in your web browser to view the main page.

3. Configure your own Firebase project following Firebase instructions. Obtain the configuration credentials, including the "API Key," and ensure you replace the `firebaseConfig` variable in the `config.js` file with your own credentials provided by Firebase.

4. Create a Cloud Firestore database in Firebase with the necessary collections for pizza and beverage menus and the Mission, Vision, and Values section.

5. Store pizza and beverage images in Firebase Storage and update image paths in the `index.html` file to suit your specific needs.

## Additional Notes 📝

- The page uses Google Analytics to track and analyze user behavior. Make sure to replace `UA-YOUR-TRACKING-CODE` with your own tracking code.

- Remember to keep your Firebase credentials and other sensitive data secure. Avoid sharing confidential information in public spaces.

## Contribution 🤝

If you wish to contribute to this project or report issues, you can do so by submitting a Pull Request or opening an Issue in the repository.

## License ⚖️

This project is licensed under the MIT License. You can refer to the `LICENSE` file for more details.

---

I hope this description covers all the essential features and details of the pizzeria website. If you have any questions or suggestions, don't hesitate to reach out to the development team. Enjoy your delightful experience at the Pizzeria! 🍕🎉
