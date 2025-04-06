# live link: https://Futurekhat.netlify.app/

# Future Khat

**Future Khat** is a platform that allows users to send messages to their future selves. It's perfect for setting goals, creating reminders, and building personal time capsules. With an intuitive interface, users can schedule emails to be delivered at any future date.

## Features

- **Compose Rich Emails**: Use a rich text editor to create personal and meaningful messages. Add images, format text, and make it unique.
- **Flexible Scheduling**: Pick any date in the future for your message to be delivered, whether it's next week or years from now.
- **Reliable Delivery**: Relax while we ensure your message is delivered exactly when you want it.

## How It Works

1. **Write Your Message**: Compose your email using our rich text editor.
2. **Pick Your Date**: Schedule the delivery date of your email.
3. **Sit Back and Relax**: We'll handle the delivery and ensure your message reaches your future self on time.

## Getting Started

Follow these steps to set up and run the project:

### Prerequisites

- [.js](https://nodejs.org/) (version 14 or higher)
- Any modern web browser

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ayush-7083/future-khat.git
   cd laya-hun-khat
   
2. Install dependencies:
```bash
npm install
```

3. Set up the environment variables:
Create a .env file in the root directory and define the following variables:
```bash
VITE_SUPABASE_URL=your-supabase-database-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
VITE_RESEND_API_KEY=your-resend-api
```
4. Start server:
```bash
npm run dev
```
5. Access the application at ```http://localhost:3000``` in your web browser.

### Usage
Visit the homepage and sign in or sign up.
Click "Start Writing" to compose your email.
Schedule a delivery date for your message.
Relax and let us handle the rest!

### Tech Stack
Frontend: React.js, HTML, CSS(Tailwind)
Backend: Node.js, Express.js
Database: Supabase(PostgreSQL)
Email Service: Resend API


### Contributions
We welcome contributions to improve this project! Here's how you can contribute:

Fork the repository.
1. Create a feature branch:
```
git checkout -b feature-name
```
2. Commit your changes:
```bash
git commit -m "Add your message here"
```
3. Push your changes:
```bash
git push origin feature-name
```
5. Open a pull request.

### License
© 2024 Laya Hun Khat. All rights reserved.
