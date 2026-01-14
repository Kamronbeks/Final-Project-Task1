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

(image_d25871.png rasmini shu yerga sudrab tashlang)

## 📁 Technical Implementation
- **Controller:** `HelloController.java`
- **Template:** `greeting.html` (Thymeleaf)
- **Mapping:** `@GetMapping("/greeting")` with `@RequestParam`
