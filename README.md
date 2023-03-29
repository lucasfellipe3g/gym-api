# App

GymPass style app.

## Functional Requirements

- [x] It should be able to register;
- [x] It should be able to authenticate;
- [x] It should be able to get the profile from logged user;
- [x] It should be able to get the number of check-ins for an logged user;
- [x] It should be able to get the history of check-ins;
- [x] It should be able to find nearby gyms;
- [x] It should be able to find gyms by name;
- [x] It should be able to check-in on gym;
- [x] It should be able to validate a check-in from user;
- [x] It should be able to register a gym;

## Business Rules

- [x] It should not be able to user register with same email;
- [x] It should not be able to do two or more check-ins in the same day;
- [x] It should not be able to check in on distant gym;
- [x] It should not be able to validate the check-in after 20 minutes of its creation
- [x] It should be able to validate check-in if you're an admin;
- [x] It should be able to register a gym if you're an admin;

## Non-functional Requirements

- [x] The user's password must be encrypted;
- [x] The application data must be persisted in a PostgreSQL database;
- [x] All data lists must be paginated with 20 items per page;
- [x] The user must be identified by a JWT (Json Web Token);
