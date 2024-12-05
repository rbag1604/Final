# ShopMe - E-commerce Fashion Website

**Project Link:** [ShopMe - Live Website](https://icy-island-09e93d61e.4.azurestaticapps.net/#)

## **Project Overview**
ShopMe is a dynamic e-commerce platform where users can browse through a variety of men's and women's fashion products. It offers a smooth and modern shopping experience with filters to help users find specific products. The website features a responsive design, ensuring accessibility on both mobile and desktop devices.

---

## **Tech Stack**

### **Frontend**
- **React**: Component-based library for building user interfaces.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **Vite**: Lightning-fast build tool for development and bundling.
- **React Router**: For seamless routing and navigation.

### **Backend**
- **No Backend**: This is a static web application with mock data stored in JSON files.

### **Deployment**
- **Azure Static Web Apps**: For hosting and serving the static site.
- **GitHub Actions**: Automated CI/CD pipeline for continuous deployment.

### **Tooling & Libraries**
- **PostCSS**: For processing CSS.
- **Context API**: State management solution for the application.
- **Jest & React Testing Library**: For unit and integration testing.

---

## **Key Features**
- **Landing Page**: A visually appealing homepage with an introduction to the platform.
- **Routing & Navigation**: Easy-to-use navigation to explore different categories and products.
- **Product Filtering & Search**: Filter products based on categories and price range for a personalized experience.
- **Storytelling**: Engage users with a compelling narrative about fashion and shopping.
- **Responsive Design**: Optimized for both desktop and mobile devices.

---

## **Agile Methodology**
To ensure efficient project management, I used **GitHub Projects** to track progress with an Agile workflow.

### **Epics**
- **User Management**
- **Navigation**
- **Filtering & Search**
- **Storytelling**

### **Features**
- **Implement Routing** – React Router for page navigation.
- **Create Landing Page** – Design a visually appealing homepage.
- **Add Filtering Logic** – Implement product filters (by price, category).
- **Design Product Pages** – Create detailed pages for each product.

---

## **Web Application Features**

### **Landing Page**
The landing page is created using semantic HTML and is visually attractive, introducing users to the platform and its purpose. It includes animations for smooth transitions.

### **Routing & Navigation**
React Router is used to navigate between different sections of the site. The navigation bar has links to product categories, the homepage, and other important sections.

### **Storytelling**
A compelling narrative about the fashion journey and shopping experience is structured through React components. Sections include product highlights, testimonials, and the platform’s mission.

### **Data Handling & Filtering**
Product data, including images, prices, and descriptions, is stored in a JSON file. Filtering logic is implemented for users to filter products by category, size, and price range.

### **Styling & Presentation**
TailwindCSS is used for responsive design, ensuring a seamless user experience across different screen sizes. The design is simple, modern, and visually appealing to enhance the user’s shopping journey.

---

## **CI/CD Pipeline**
The deployment process is automated using **GitHub Actions**. Upon pushing changes to the main branch, the GitHub Actions pipeline automatically deploys the latest version of the website to **Azure Static Web Apps**.

### **CI/CD Documentation**
- The GitHub Actions pipeline is set up to deploy the application automatically every time changes are pushed to the main branch.
- **Azure Static Web Apps** ensures that the site is live and updated with the latest features and fixes.

---

## **Best Practices Followed**
- **Component-Based Architecture**: The project is structured into reusable components for easy maintenance and scalability.
- **State Management**: The Context API is used to manage application-wide state, including the shopping cart and filters.
- **Testing**: Unit and integration tests were added using Jest and React Testing Library to ensure functionality and component behavior.
- **Accessibility**: The application follows WCAG 2.1 guidelines to ensure it is accessible to users with disabilities, including keyboard navigation and ARIA roles.
- **Performance Optimization**: The application uses React.lazy for code splitting, ensuring faster initial loads and better performance.

---

## **Future Scope**
- **User Authentication**: Implement user login and registration for a personalized shopping experience.
- **Payment Gateway Integration**: Add support for online payments to complete the shopping process.
- **Advanced Filtering**: Add more advanced filters based on product reviews, ratings, and availability.
