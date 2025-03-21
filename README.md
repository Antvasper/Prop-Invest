# Prop-Invest
Prop Invest
# PropInvest - Property Investment Finder

A SaaS application that helps people find investment properties and calculate potential ROI in Australia.

## Preview Login Credentials

For the preview version, you can use these demo accounts:

- **Free Tier User:**
- Email: demo@example.com
- Password: password123

- **Premium Tier User:**
- Email: premium@example.com
- Password: password123

## Features

- Property search and filtering
- ROI calculator
- Saved properties
- Recent searches
- Market trends analysis
- Subscription management (Free and Premium tiers)
- User dashboard

## Tech Stack

- Next.js 14
- React
- NextAuth.js for authentication
- Tailwind CSS with shadcn/ui components

## Environment Variables

Make sure to set the following environment variables:

- `NEXT_PUBLIC_APP_URL`: The URL where your application is deployed
- `GOOGLE_CLIENT_ID`: (Optional) For Google authentication
- `GOOGLE_CLIENT_SECRET`: (Optional) For Google authentication
- `DOMAIN_CLIENT_ID`: For Domain.com.au API integration
- `DOMAIN_CLIENT_SECRET`: For Domain.com.au API integration

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables
4. Run the development server: `npm run dev`
5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This application can be deployed to Vercel:

1. Push your code to a Git repository
2. Import the project in Vercel
3. Configure environment variables
4. Deploy

## Preview Version Notes

The preview version uses in-memory storage instead of a database for demonstration purposes. Data will not persist between sessions or deployments.

## License

This project is licensed under the MIT License.
