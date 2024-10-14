# Vehicles Hub - Car Owner Management Platform

**Description**: Vehicles Hub is a comprehensive car rental application designed to help car owners manage their vehicles, bookings, and earnings seamlessly. It provides an intuitive platform for owners to list their vehicles, track bookings, communicate with renters, and monitor their income, all from a single dashboard. The app offers real-time notifications, secure management, and easy-to-use features for optimal user experience.

**Technologies Used**:
- **Flutter**: Cross-platform mobile app development.
- **Cubit (Bloc)**: State management for handling UI states and business logic.
- **Firebase Cloud Messaging (FCM)**: For push notifications to keep car owners updated in real time.
- **Laravel (Backend)**: RESTful API to manage data transactions and provide seamless communication between the app and the server.
- **OTP SMS Masr**: Secure OTP-based authentication for verifying car owners' identity.
- **Payment Integration**: Manage payments via **Stripe** and **other local payment methods**.

**Architecture**:
The application is designed using **Clean Architecture** to provide modularity, scalability, and separation of concerns:
- **Presentation Layer**: Built using Flutter and Cubit for state management, ensuring smooth interactions and responsive design for car owners to manage their profiles, cars, and bookings.
- **Domain Layer**: Handles core business logic such as car listings, bookings, and income tracking.
- **Data Layer**: Communicates with the **Laravel backend** for data retrieval and synchronization. Also manages local storage for offline capabilities.
- **Push Notifications**: Powered by Firebase Cloud Messaging (FCM), ensuring car owners receive updates on bookings, payments, and user interactions.

**Key Features for Car Owners**:
- **Vehicle Listings**: Easily add and manage your fleet of cars. You can update vehicle information, availability, and pricing with ease.
- **Booking Management**: Monitor all bookings, confirm or reject rental requests, and view detailed information on each booking.
- **Earnings Tracking**: Get a clear overview of your earnings with detailed reports and income tracking.
- **Push Notifications**: Receive real-time updates on new bookings, cancellations, and other important activities.
- **User Communication**: Communicate with renters directly within the app through in-app messaging.
- **Secure Authentication**: Log in securely using **OTP SMS** verification provided by **Masr**.
- **Multi-language Support**: Manage your account in both Arabic and English for ease of use.

**Challenges Solved**:
- Implementing **OTP authentication** for secure and smooth login experiences.
- Developing a robust **booking management system** that allows owners to efficiently manage multiple rentals simultaneously.
- Ensuring **real-time notifications** for immediate updates using Firebase Cloud Messaging (FCM).
- Managing **state transitions** using **Cubit** for clear and efficient handling of UI states across the platform.
- Providing detailed **earnings and analytics** for better financial tracking.

**App Links**:
- [Google Play Store - Owner Version](https://play.google.com/store/apps/details?id=co.boldbrand.vehicles_owner)
- [Apple App Store - Owner Version](https://apps.apple.com/in/app/vehciles-hub-owner/id1658426303)

**Live Demo**:
Due to confidentiality, the source code is not available. However, I can offer a live demo during a meeting, where I will showcase the entire car owner management platform. The demo can be done using an emulator or live production version of the app.

To explore the application yourself, feel free to download it from the [Google Play Store](https://play.google.com/store/apps/details?id=co.boldbrand.vehicles_owner) or [Apple App Store](https://apps.apple.com/in/app/vehciles-hub-owner/id1658426303).

**Contact for Demo**:
If you are interested in a personalized demonstration or have any further questions, please reach out to me. I'd be happy to provide more insights into the app's functionalities and walk you through how car owners can manage their vehicles effectively.
