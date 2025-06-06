# Backend Development Prompt for E-commerce Application

## Objective

Develop the backend of an e-commerce application using Django and Django REST Framework. The backend should provide REST APIs for the following functionalities:

### Features

1. **User Authentication**:

   - Login
   - Register

2. **Product Management**:

   - Add 10 dummy products to the database.
   - Provide a GET API to retrieve the list of products.

3. **User Address Management**:

   - Allow logged-in users to add multiple addresses.

4. **Cart Management**:

   - Add items to the cart.
   - Delete items from the cart.

5. **Wishlist Management**:
   - Add items to the wishlist.

### Requirements

- Use Django REST Framework for API development.
- Use SQLite as the database.
- Implement serializers for all models.
- Ensure proper request validation and error handling.
- Use Django's built-in user model for authentication.

### Unit Tests

Write unit tests for the following:

- User registration and login.
- Adding and retrieving products.
- Adding and retrieving user addresses.
- Adding and deleting items in the cart.
- Adding items to the wishlist.

### Deliverables

1. A Django project with the following structure:

   - Models for users, products, addresses, cart, and wishlist.
   - Serializers for all models.
   - Views and URLs for the specified APIs.
   - Unit tests for all functionalities.

2. A `README.md` file with instructions on how to set up and run the project.

3. A `requirements.txt` file listing all dependencies.

### Notes

- Focus only on the backend; no frontend is required.
- Use Django's default authentication system for user management.
- Ensure the code is modular and follows best practices.
