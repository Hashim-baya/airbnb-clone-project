# airbnb-clone-project

# **Project Overview**

This project is a full-stack clone of AirBnB, replicating core functionality to allow users to discover, view, and book properties.

# **Project Goals**

## **Core Functionality**

### **User Authentication**
- Sign up/login with email or social accounts
- Profile management (personal info, booking history)

### **Property Listings**
- Browse properties with filters (price, location, amenities)
- Search functionality with autocomplete

### **Booking System**
- Real-time availability calendar
- Secure payment processing (simulated)
- Booking confirmation/email notification

### **Technical Objectives**
- Frontend: Build responsive UI with React using modern hooks and state management
- Backend: Create RESTful APIs with proper error handling
- Database: Design efficient schema for properties, users, and bookings
- Performance: Optimize load times (lazy loading, image compression)
- Testing: Achieve 80%+ test coverage with Jest/React Testing Library

### **UX/UI Targets**
- Mobile-first design with seamless cross-device experience
- WCAG AA accessibility compliance
- Reusable component library (Figma )


# UI/UX Design Planning

## Design Goals
- Deliver an **intuitive** and **accessible** interface for all users.
- Ensure **consistency** across devices (mobile-first approach).
- Prioritize **speed** and **clarity** in the booking process.
- Achieve **WCAG AA** accessibility compliance.

## Key Features to Implement
- Responsive property grids with lazy-loaded images.
- Interactive filters (price, location, amenities).
- Real-time booking availability calendar.
- Minimalist checkout flow (3 steps max).

## Primary Pages

| Page                  | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | Displays search results in a grid/card layout with filters and sorting options. |
| **Listing Detailed View** | Shows high-res photos, amenities, host info, and booking calendar.          |
| **Simple Checkout View**  | Streamlined form with booking summary, payment (simulated), and confirmation. |

## Importance of User-Friendly Design
A well-designed booking system:
- **Reduces abandonment**: Clear UI = fewer frustrated users.  
- **Builds trust**: Professional design increases perceived credibility.  
- **Saves time**: Fewer steps = faster conversions.  
- **Encourages repeat use**: Positive experiences drive loyalty.

  # UI/UX Design Planning

## Figma Design Specifications

### Color Styles
| Type           | Hex Code  | Usage                          |
|----------------|----------|--------------------------------|
| Primary        | `#FF5A5F` | Buttons, CTAs, Interactive Elements |
| Secondary      | `#008489` | Secondary accents, Highlights  |
| Background     | `#FFFFFF` | Page backgrounds               |
| Text           | `#222222` | Primary text, Headings         |
| Secondary Text | `#717171` | Captions, Inactive elements    |

### Typography
**Font Family:** Circular  

| Usage          | Weight | Size   | Example Class       |
|----------------|--------|--------|---------------------|
| Headings       | 700 (Bold) | 24px-32px | `.heading-1`, `.heading-2` |
| Primary Text   | 500 (Medium) | 16px   | `.body-text`        |
| Secondary Text | 400 (Book) | 14px    | `.caption`, `.helper-text` |

### Importance of Identifying Design Properties  
1. **Consistency**  
   - Ensures identical styling across all screens/devices.  
2. **Developer Handoff**  
   - Provides exact values (colors, fonts) for accurate implementation.  
3. **Scalability**  
   - Design tokens (like color variables) allow easy future updates.  
4. **Accessibility**  
   - Documented contrast ratios and font sizes meet WCAG standards.  
5. **Team Alignment**  
   - Serves as a single source of truth for designers/devs.  
