## Culinarix API Documentation

Greetings, developers! Welcome to the Culinarix API Documentation. Below are the repositories containing various APIs developed for our exciting Culinarix project.

**Links to each Repository**

| Links                  | Description                     |
|---------------------------|---------------------------------|
| [Collaborative Filtering API](https://github.com/alghoziii/culinarix-collaborative-filtering)  | Get restaurant recommendations based on the Collaborative Filtering  |
| [Content-Based Recommendation API](https://github.com/LeeVonks/culinarix-content-based) | restaurant recommendations based on the unique characteristics of each dining establishment.        |
|  [Login - Register API](https://github.com/alghoziii/api-login-register) |  the implementation of the login and registration API for the Culinarix project.  |

### 1. [Collaborative Filtering API](https://github.com/alghoziii/culinarix-collaborative-filtering)

Explore the Collaborative Filtering API, where culinary adventures begin! Get personalized restaurant recommendations based on collaborative user preferences.

**Endpoints Summary:**

| Method | Endpoint                  | Description                     |
|--------|---------------------------|---------------------------------|
| GET    | `/prediction/{user_id}`  | Get restaurant recommendations based on the Collaborative Filtering  |
| GET    | `/top-rated`              | Get top-rated restaurants        |


### 2. [Content-Based Recommendation API](https://github.com/LeeVonks/culinarix-content-based)

Indulge in the Content-Based Recommendation API, where taste meets technology! Discover restaurant recommendations based on the unique characteristics of each dining establishment.

**Endpoints Summary:**

| Method | Endpoint                  | Description                     |
|--------|---------------------------|---------------------------------|
| GET    | `/recommendations/{place}`| Get restaurant recommendations based on the content-based recommendation |
| GET    | `/top-rated`              | Get top-rated restaurants        |
| GET    | `/search`              | Get restaurant details with search feature        |



### 3. [Login - Register API](https://github.com/alghoziii/api-login-register)

Get ready to experience seamless user authentication with our Login - Register API. Register new users, log them in, and retrieve user information effortlessly.

**Endpoints Summary:**

| Method | Endpoint         | Description          |
|--------|------------------|----------------------|
| POST   | `/auth/register`      | Register a new user  |
| POST   | `/auth/login`          | Log in a user        |
| GET    | `/user/details` | Get user information |

Feel free to dive into these APIs and enhance your Culinarix experience. If you have any questions or suggestions, our development team is here to assist you. Happy coding! 🚀
