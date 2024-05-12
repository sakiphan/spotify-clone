# Spotify Clone

This project is designed to simulate a Spotify-like music streaming service interface. It is developed using Next.js, Supabase, Stripe, and Tailwind CSS.

## Features

- Music playback
- User authentication
- Premium subscription options
- Responsive design

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

You need to have Node.js and npm/yarn installed to run this project.

### Installation

1. Clone the repository:
   ```bash
   git clone https://https://github.com/sakiphan/spotify-clone.git
   cd spotify-clone
   ```
   
 ###  Install Dependencies
 ```
 npm install
 ```
 
 ### Create a .env file and fill in the following variables
 ```
 NEXT_PUBLIC_SUPABASE_URL='your-supabase-url'
NEXT_PUBLIC_SUPABASE_ANON_KEY='your-supabase-anon-key'
SUPABASE_SERVICE_ROLE_KEY='your-supabase-service-role-key'

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY='your-stripe-publishable-key'
STRIPE_SECRET_KEY='your-stripe-secret-key'
STRIPE_WEBHOOK_SECRET='your-stripe-webhook-secret'
```
### Development
```
npm run dev
```
This command will launch a development server at http://localhost:3000.

### Configuration
The project uses default configuration files for Next.js, Tailwind CSS, and other libraries. Refer to these files for further details and customization.





