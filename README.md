# EHR: Project Structure Representation

EHR-MIS/
│── EHR-MIS.sln                      # Solution file
│
├── src/
│   ├── EHR-MIS.Web                  # ASP.NET Core Web Application (UI Layer)
│   │   ├── Controllers/             # Controllers for each module
│   │   ├── Views/                   # Razor Views (MVC)
│   │   ├── wwwroot/                 # Static files (CSS, JS, images)
│   │   └── Program.cs
│   │
│   ├── EHR-MIS.Core                 # Core Business Logic
│   │   ├── Entities/                # Database Models (Patient, Doctor, Invoice, etc.)
│   │   ├── Interfaces/              # Service Interfaces
│   │   └── Services/                # Business Logic Implementation
│   │
│   ├── EHR-MIS.Infrastructure       # Data Access Layer
│   │   ├── Data/                    # DbContext (EF Core)
│   │   ├── Repositories/            # Repository Implementations
│   │   └── Migrations/              # Database Migrations
│   │
│   └── EHR-MIS.Tests                # Unit & Integration Tests
│
├── docs/                            # Project Documentation
│
└── README.md                        # Project Overview
