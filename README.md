# Blog Platform

Welcome to the Blog Platform! This backend system allows users to write, update, and delete blogs.

## Base URL

https://blog-backend-server.vercel.app

## Postman Collection

For detailed information about each API endpoint, request parameters, responses, and more, please refer to the [Postman API Documentation](https://documenter.getpostman.com/view/38345873/2sAYdcrXe8).

## API Endpoints

### 1\. Authentication

#### 1.1 Register User

**POST** `/api/auth/register`

#### 1.2 Login User

**POST** `/api/auth/login`

---

### 2\. Blog Management

#### 2.1 Create Blog (User)

**POST** `/api/blogs`

#### 2.2 Update Blog (User)

**PATCH** `/api/blogs/:id`

#### 2.3 Delete Blog (User)

**DELETE** `/api/blogs/:id`

#### 2.4 Get All Blogs (Public)

**GET** `/api/blogs`

#### 2.5 Get My Blogs (User)

**GET** `/api/blogs/me`
