<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

  <h3 align="center">HealthCare Management System</h3>
</div>

## Acknowledgements

Special thanks to JavaScript Mastery for providing an excellent tutorial that inspired and guided us in building this healthcare management application. Their insights into modern web technologies helped us create a robust and efficient system. Follow their tutorial on [YouTube](https://www.youtube.com/@javascriptmastery/videos) to learn step by step.

## About The Project

The HealthCare Management System is a full-stack application designed to streamline patient registration, appointment booking, and administrative management.

### Frontend

- **Next.js 14** with App Router for building fast, scalable web applications.
- **TypeScript** for ensuring type safety and improved code reliability.
- **Tailwind CSS** for responsive and modern UI design.
- **React Hook Form** with Zod validation for efficient form handling.
- **ShadCN UI** components for reusable design patterns.

### Backend

- **Appwrite** for authentication, database, and storage services.
- **Twilio** for SMS notifications and real-time updates.
- **Sentry** for performance monitoring and debugging.

### Key Features

- Secure authentication for patients and admins.
- Appointment booking and management with status updates.
- Real-time SMS notifications for patients on appointment confirmation.
- File upload and secure storage for patient records.
- Responsive design optimized for all devices.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ram-and-arun/healthcare-management-system.git
   cd healthcare-management-system
   ```

````

2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables in `.env.local`:

   ```env
   NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
   PROJECT_ID=
   API_KEY=
   DATABASE_ID=
   PATIENT_COLLECTION_ID=
   APPOINTMENT_COLLECTION_ID=
   NEXT_PUBLIC_BUCKET_ID=

   NEXT_PUBLIC_ADMIN_PASSKEY=111111
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

## Tech Stack Details

- **Next.js**: Frontend framework for server-side rendering and static site generation.
- **TypeScript**: Statically typed JavaScript for better developer experience.
- **Appwrite**: Open-source backend as a service for database, authentication, and storage.
- **Twilio**: SMS notifications and communication.
- **Sentry**: Application monitoring and error tracking.
- **Tailwind CSS**: Utility-first CSS framework for modern designs.
- **ShadCN**: Collection of reusable UI components.

## Created By

- Ramachandra Kulkarni
- Arun Basavaraj Alur

## Tutorial Reference

Learn how to build this project by following JavaScript Mastery's detailed tutorial on [YouTube](https://www.youtube.com/@javascriptmastery/videos).

## Contributing

Feel free to fork this project and submit pull requests for improvements.
````
