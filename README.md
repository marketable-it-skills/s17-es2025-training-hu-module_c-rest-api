# EuroSkills 2025 Module C - REST API Development

## Project Overview

This test project simulates Module C of the EuroSkills 2025 Web Development competition. Competitors must build a comprehensive REST API for the SkillShare Academy platform, implementing user authentication, course management, mentor booking, and a credit-based learning system.

## Competition Details

- **Duration**: 3 hours
- **Points**: 15 total (WSOS: 1+1+0+0+13)
- **Technology**: Laravel 12.x, MySQL, JWT Authentication
- **Prerequisites**: Completed Module B database schema

## Project Structure

```
/
├── project-description.md     # Complete task specification
├── development-and-deployment.md  # Setup and deployment guide
├── metadata.json             # Project metadata
├── marking/
│   └── marking-scheme.json   # Assessment criteria
└── assets/
    └── project-description-images/  # Task-related images
```

## Key Requirements

### Core Features

- JWT-based authentication system with API tokens
- Course management API with enrollment and progress tracking
- Mentor booking system with credit-based payments
- Credit earning system (3-5 credits per chapter)
- Transaction history and balance management

### Technical Stack

- **Backend**: Laravel 12.x with API routes
- **Database**: MySQL with proper relationships
- **Authentication**: JWT tokens with middleware protection
- **Validation**: Form request classes with business rules
- **Documentation**: Clear API endpoint documentation

### API Endpoints (10-12 total)

- Authentication: register, login, profile management
- Courses: catalog, details, enrollment, progress
- Mentors: discovery, profiles, booking, availability
- Credits: balance, transactions, earning, spending

## Assessment Focus

1. **Functionality (13 pts)**: Working endpoints with proper validation
2. **Code Quality**: Laravel conventions and clean architecture
3. **Security**: Authentication, authorization, input sanitization
4. **Integration**: Seamless connection with Module B database

## Time Allocation

1. **Setup & Auth (45 min)**: Laravel setup, JWT implementation
2. **Database & Models (60 min)**: Schema extensions, Eloquent relationships
3. **Core APIs (75 min)**: Endpoint implementation, validation, testing

This project builds upon Module A (static design) and Module B (admin interface), preparing for Module D (frontend integration).
