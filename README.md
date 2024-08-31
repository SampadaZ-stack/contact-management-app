# Contacts Management Application

## Overview

The Contacts Management Application is a full-stack application built using Angular for the frontend and .NET Core for the backend. This application allows users to manage contact information, including creating, reading, updating, and deleting contacts. It provides features like sorting, pagination, and searching of contact records.

## Features

- CRUD Operations: Create, Read, Update, and Delete contacts.
- Sorting: Sort contacts by ID, First Name, Last Name, and Email.(hover on column name and click)
- Pagination: Navigate through large sets of contacts with paginated views.
- Search: Filter contacts using a search functionality.(enter letter it will search)
- Responsive UI: Built with Angular Material for a modern and responsive design.

## Technologies

- Frontend: Angular 13+, Angular Material, RxJS, Angular Reactive Forms
- Backend: .NET Core 6+, Entity Framework Core (if using database), Mock JSON file
- Testing:  xUnit
- Styling: Angular Material UI components

## Getting Started

### Prerequisites

- Node.js and npm (for Angular)
- .NET Core SDK (for backend)
- Angular CLI
- SQL Server or other database if not using a mock file

### Setup and Installation

#### Frontend (Angular)

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-repo/contacts-management-app.git
   cd contacts-management-app/frontend
