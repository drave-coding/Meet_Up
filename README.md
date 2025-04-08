# MeetUp

MeetUp is a video calling web application built using Next.js, React, and Stream SDK. It allows users to schedule, join, and manage video meetings seamlessly. The app was created to simplify virtual communication and includes features such as instant meetings, scheduled meetings, personal meeting rooms, and meeting recordings.

## Tech Stack

- **Frontend**: Next.js, React
- **Backend**: Node.js
- **Database**: Stream SDK (for video calls)
- **Others**: TailwindCSS, Clerk for authentication, Zustand, React Datepicker

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/drave-coding/Meet_Up
   cd meet_up
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   - Create a `.env.local` file in the root directory.
   - Add the following variables:
     ```
     NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
     STREAM_SECRET_KEY=your_stream_secret_key
     NEXT_PUBLIC_BASE_URL=http://localhost:3000
     ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage Instructions

1. **Sign Up or Sign In**: Use Clerk authentication to create an account or log in.
2. **Create a Meeting**:
   - Navigate to the home page and select "New Meeting" for an instant meeting or "Schedule Meeting" to plan a meeting.
   - Copy the meeting link and share it with participants.
3. **Join a Meeting**:
   - Use the "Join Meeting" option and paste the meeting link.
4. **Personal Meeting Room**:
   - Access your personal meeting room for recurring meetings.
5. **View Recordings**:
   - Navigate to the "Recordings" section to view and play meeting recordings.

## Features

- **Instant Meetings**: Start a meeting instantly with a unique link.
- **Scheduled Meetings**: Plan meetings with a specific date and time.
- **Personal Meeting Room**: A dedicated room for recurring meetings.
- **Meeting Recordings**: Access and play recorded meetings.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Authentication**: Secure user authentication using Clerk.
- **Customizable Layouts**: Choose between grid and speaker layouts during meetings.

## Folder Structure

```
meet_up/
├── app/                   # Next.js app directory
│   ├── (auth)/            # Authentication pages
│   ├── (root)/            # Main application pages
│   ├── globals.css        # Global styles
│   └── layout.tsx         # Root layout
├── components/            # Reusable UI components
├── hooks/                 # Custom React hooks
├── providers/             # Context providers
├── constants/             # Static constants
├── lib/                   # Utility functions
├── public/                # Static assets
├── styles/                # TailwindCSS configuration
├── actions/               # Server-side actions
├── middleware.ts          # Middleware for route protection
├── tailwind.config.ts     # TailwindCSS configuration
├── tsconfig.json          # TypeScript configuration
└── package.json           # Project dependencies and scripts
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

For more details, refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Badges

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Demo

- **Live Demo**: [MeetUp Live](https://your-deployed-url.com)
- **Screenshots**:
  - Home Page:
    ![Home Page](https://via.placeholder.com/800x400)
  - Meeting Room:
    ![Meeting Room](https://via.placeholder.com/800x400)

## Changelog

See the [CHANGELOG.md](CHANGELOG.md) file for a detailed list of changes.
