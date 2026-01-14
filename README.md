# 🌐 Task 1: Spring Boot Web Application 

This is a simple Spring Boot web application that demonstrates basic MVC controller functionality and Thymeleaf template rendering.

## 🛠 Project Features
- **MVC Controller:** Handles incoming GET requests.
- **Dynamic Greeting:** Accepts a name parameter via URL.
- **Thymeleaf Integration:** Renders HTML templates with dynamic data.
- **Git Management:** Proper `.gitignore` to exclude IDE and target files.

## 🚀 Use Cases & Examples

### 1️⃣ Default Greeting
- **URL:** `http://localhost:8080/greeting`
- **Description:** Displays a default "Hello, World!" message when no name is provided.

 ![Image Alt](https://github.com/Kamronbeks/Final-Project-Task1/blob/36a41a909d47682b1a64e57616026a1aa3f441ed/Screenshot%202026-01-14%20101042.png)

## 📁 Technical Implementation
- **Controller:** `HelloController.java`
- **Template:** `greeting.html` (Thymeleaf)
- **Mapping:** `@GetMapping("/greeting")` with `@RequestParam`
