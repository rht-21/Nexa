# Nexa - Video Conferencing Application

Nexa is a robust and user-friendly video conferencing application built using Next.js, TypeScript, and Tailwind CSS. It aims to provide seamless and high-quality video conferencing experiences with minimal setup and maximum performance.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- High-quality video and audio conferencing
- Screen sharing
- Call recordings
- Secure and encrypted communication
- Easy to use and intuitive UI
- Responsive design for all devices
- Scalable architecture

## Installation

To get started with Nexa, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/nexa.git
   cd nexa
   ```

2. **Install dependencies:**

  ```bash
  npm install
  ```

3. **Configuration:**

   Nexa uses environment variables for configuration. Create a .env.local file in the root directory and add the following variables:

   ```bash
   # Clerk (https://clerk.com/)
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY={pk_test_key}
   CLERK_SECRET_KEY={sk_test_key}
   
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   # Stream (https://getstream.io/)
   NEXT_PUBLIC_STREAM_API_KEY={apiKey}
   STREAM_SECRET_KEY={secretKey}

   NEXT_PUBLIC_BASE_URL={domainName} #initailly localhost:3000
   ```

   Follow the documentation to generate the keys

4. **Run the development server:**

   ```bash
   npm run dev
   ```

## Usage

Nexa offers a variety of features to facilitate your video conferencing needs:

### Creating a Meeting
To create an instant meeting room

### Scheduling a Meeting
To schedule a meeting for future use

### Joining a Meeting
To join an existing meeting:

### Recording Meetings
To record a meeting for future reference:

### Screen Sharing
To share your screen with other participants:

Nexa makes it easy to host, schedule, join, and manage your video conferences efficiently.

## Contact

If you have any questions, suggestions, or feedback, feel free to contact me at:

    Email: iamrht21@gmail.com
    Instagram: @rht21
