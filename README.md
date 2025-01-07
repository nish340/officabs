# officabs
OfficeCabs is a city-focused car/bike pooling platform designed to address traffic congestion, pollution, and the affordability of daily travel in cities like Chandigarh, India. The platform allows vehicle owners to list their vehicles, routes, and available seats for ride seekers to browse and book monthly or long-term rides.

Key Features
    1. User Roles:
        ◦ Vehicle Owners:
            ▪ List their vehicle details, routes, available seats, and charges.
            ▪ Upload documents like Aadhaar, Driver’s License, and Vehicle RC for identity verification.
        ◦ Ride Seekers:
            ▪ Browse and book rides based on available routes, vehicle owners, and locations.
            ▪ Offer ratings and make donations.
        ◦ Admins:
            ▪ Manage users (approve/deactivate accounts).
            ▪ Resolve disputes between ride seekers and vehicle owners.
            ▪ Oversee the platform and its security features.
    2. Additional Features:
        ◦ Ratings: Vehicle owners and ride seekers can rate each other.
        ◦ Donations via UPI: Users can donate to the platform.
        ◦ Document Verification: Upload and validate documents for user authenticity.
        ◦ Email Verification: Ensure security and user authenticity.

Technical Stack
    • Backend: Node.js, NestJS
    • Frontend: Angular
    • Database: PostgreSQL or MySQL (Relational Database)
    • File Storage: Amazon S3 (for documents)
    • Authentication: JWT (JSON Web Tokens) for session management, email verification for security
    • Payment Handling: UPI integration for donations
    • Other Tools: Google Maps API (for route calculations when integrated), Cron jobs for booking reminders