# Car Rental API
> A RESTful API built with C#/.NET for managing car rentals with vehicle availability tracking, reservation, and customer rental limits.
---
## About
Car Rental API is a lightweight car rental management service that allows users to catalog vehicle models, register physical vehicles, and handle the full rental lifecycle through a structured REST interface.
---
## Technologies
- C# / .NET
- ASP.NET Core
- Entity Framework Core
---
## Getting Started
```bash
# Clone the repository
git clone https://github.com/KayronJ/car-rental-api.git
# Restore dependencies
dotnet restore
# Run the project
dotnet run
```
---
## Requirements
| Functional Requirements                                                                  | Non-Functional Requirements                                  |
|--------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| User must be able to register a vehicle model with name, category, and daily rate          | API endpoints must follow REST interface standards            |
| User must be able to add a vehicle (license plate) to a vehicle model                      | API must follow URL versioning (/api/v1/)                    |
| A rental can only be created if an available vehicle exists; otherwise the customer joins the reservation queue | Error responses must follow a standardized format |
| A customer cannot have more than 2 active rentals at the same time                         | API must use correct HTTP status codes                        |
| User must be able to list rentals with filters (status, customer) and pagination           |                                                                 |
