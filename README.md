/*
 * ==========================================================================================
 * README: Code Sample for Everlaw - Personal Bio Website
 * Author: Joel V. Samuel
 * ==========================================================================================
 *
 * ## Project Overview
 *
 * This file contains the key source code for my personal portfolio website, a fully
 * functional Spring Boot web application that I developed and deployed myself. The
 * goal of this project was twofold: first, to deepen my understanding of the
 * end-to-end process of standing up a modern web application, and second, to create a
 * professional space to showcase my skills and experience.
 *
 * This project is a direct reflection of my ability to take a project from concept to
 * a live, deployed state, which aligns with Everlaw's emphasis on end-to-end feature
 * ownership.
 *
 * ## Technologies & Architecture
 *
 * - **Backend:** Java, Spring Boot (Web, Tomcat)
 * - **Frontend:** JSP (JavaServer Pages), CSS, HTML
 * - **Build & Dependency Management:** Apache Maven
 *
 * The application follows a classic Model-View-Controller (MVC) pattern. Spring Boot's
 * embedded Tomcat server handles web requests, which are routed by a `HomeController`
 * to render the appropriate JSP view (`home.jsp`). This demonstrates a clean
 * separation of concerns between handling web traffic and presenting the UI.
 *
 * ## Included Files
 *
 * To provide a comprehensive yet concise view of the project, I have consolidated the
 * most important source files below:
 *
 * 1.  **`pom.xml`:** The Maven Project Object Model. It defines the project's
 * dependencies (like Spring Boot Starter Web), build configurations, and metadata.
 * It's the blueprint of the entire project.
 *
 * 2.  **`HomeController.java`:** The Spring MVC controller. This class is responsible for
 * handling incoming HTTP requests. In this simple application, it maps the root URL ("/")
 * to the `home.jsp` view.
 *
 * 3.  **`home.jsp`:** The JavaServer Pages view. This is the frontend of the application,
 * containing the HTML structure and presentation logic for the main page.
 *
 * 4.  **`website.css`:** The custom stylesheet for the website. It demonstrates my ability
 * to craft a clean and professional user interface.
 *
 * This curated sample showcases my proficiency in Java and the Spring ecosystem, as
 * well as my skills in fundamental web technologies.
 *
 */

