# Airbnb Clone Project - StayEase

## Project Overview
This project is a full-stack clone of AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings.

**Tech Stack:**
- Frontend: HTML, CSS, JavaScript (React)
- Backend: Node.js/Express
- Database: MySQL/PostgreSQL
- Version Control: Git & GitHub
- UI/UX Design: Figma

---

## Team Roles

| Role | Responsibilities |
|------|-----------------|
| Project Manager | Oversees timeline, coordinates team, manages deliverables |
| Frontend Developers | Implements UI components, ensures responsive design |
| Backend Developers | Builds APIs, manages database, implements business logic |
| Designers | Creates mockups, maintains design system, ensures UX quality |
| QA/Testers | Writes test cases, performs testing, reports bugs |
| DevOps Engineers | Manages deployment, CI/CD pipeline, server infrastructure |
| Product Owner | Defines requirements, prioritizes features, represents stakeholders |
| Scrum Master | Facilitates agile processes, removes blockers, organizes meetings |

---

## Technology Stack

| Technology | Purpose in Project |
|------------|-----------------|
| React | Build responsive frontend UI components |
| Node.js/Express | Build backend APIs and server logic |
| MySQL/PostgreSQL | Store data for users, properties, bookings, reviews, payments |
| Git & GitHub | Version control and collaboration |
| Figma | Design UI/UX mockups and prototypes |

---

## Database Design

**Key Entities and Relationships:**

| Entity | Key Fields | Relationships |
|--------|------------|---------------|
| Users | id, name, email, password, role | User can have multiple bookings |
| Properties | id, owner_id, title, description, price, location | Property belongs to owner, has multiple bookings |
| Bookings | id, user_id, property_id, start_date, end_date | Booking belongs to a user and a property |
| Reviews | id, user_id, property_id, rating, comment | Review belongs to a user and a property |
| Payments | id, booking_id, amount, status, payment_method | Payment belongs to a booking |

---

## Feature Breakdown

| Feature | Description |
|---------|------------|
| User Management | Users can register, log in, and manage profiles, ensuring personalized experience. |
| Property Management | Owners can list properties, update details, and manage availability. |
| Booking System | Users can search properties, make bookings, and receive confirmations. |
| Payment Integration | Users can securely pay for bookings using various payment methods. |
| Reviews & Ratings | Users can leave reviews and ratings to maintain transparency and trust. |

---

## API Security

- **Authentication & Authorization:** Ensures only authorized users can access specific resources.
- **Rate Limiting:** Protects APIs from abuse and overuse.
- **Data Validation & Encryption:** Sensitive data, like passwords and payments, are secured.
- **Importance:** Protects user data, secures payments, and ensures overall platform integrity.

---

## CI/CD Pipeline

- **What it is:** Continuous Integration (CI) and Continuous Deployment (CD) automates testing and deployment.
- **Importance:** Speeds up development, reduces human errors, ensures consistent releases.
- **Tools:** GitHub Actions, Docker, Jenkins.

---

## UI/UX Design Planning

### Design Goals
- Create intuitive booking flow
- Maintain visual consistency
- Ensure fast loading times
- Prioritize mobile responsiveness

### Key Features
- Property search and filtering
- Detailed property viewing
- Secure checkout process
- User authentication

### Primary Pages

| Page | Description |
|------|------------|
| Property Listing View | Grid display of available properties with filters |
| Listing Detailed View | Complete property details with images and booking form |
| Simple Checkout View | Streamlined payment and booking confirmation |

**Importance of User-Friendly Design:**  
A well-designed booking system reduces friction, increases conversion rates, and improves customer satisfaction.

### Figma Design Specifications
**Color Styles:**  
- Primary: #FF5A5F  
- Secondary: #008489  
- Background: #FFFFFF  
- Text: #222222  
- Secondary Text: #717171  

**Typography:**  
- Primary Font: Circular, Medium (500), 16px  
- Headings: Circular, Bold (700), 24px-32px  
- Secondary Text: Circular, Book (400), 14px  

---

## UI Component Patterns

**Planned Components:**
- **Navbar:** Logo, Search bar, User navigation, Responsive menu
- **Property Card:** Property image, Basic details, Favorite button, Responsive layout
- **Footer:** Site links, Company info, Social media links, Copyright info

---

