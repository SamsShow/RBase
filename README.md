# RideBase - Blockchain-Powered Ride Sharing Platform

A modern ride-sharing application built with Next.js, integrating blockchain technology for secure and transparent transactions. The platform allows users to connect their crypto wallets, select pickup and dropoff locations, and complete ride bookings with cryptocurrency payments.

## Features

- **Interactive Map Interface**: Powered by Mapbox for real-time location selection and ride tracking
- **Blockchain Integration**: Connect your Web3 wallet (Metamask) for secure payments
- **Location Services**: Search for locations and get accurate ride duration and pricing
- **Responsive Design**: Optimized for both desktop and mobile experiences
- **Sanity CMS Backend**: User data management with Sanity.io

## Tech Stack

- **Frontend**: Next.js, React.js, TailwindCSS
- **Maps & Geolocation**: Mapbox GL, Mapbox Geocoder
- **Blockchain**: Ethereum (ethers.js), Web3 integration
- **Backend**: Sanity.io Content Management System
- **Authentication**: Web3 wallet authentication (Metamask)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```
NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=your_mapbox_token
NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
NEXT_PUBLIC_SANITY_DATASET=your_sanity_dataset
NEXT_PUBLIC_SANITY_API_VERSION=your_sanity_api_version
```

## Project Structure

- `/components`: React components for the UI
- `/context`: Context providers for state management
- `/pages`: Application routes and API endpoints
- `/public`: Static assets
- `/styles`: Global styles and TailwindCSS configuration
- `/src/sanity`: Sanity.io configuration and schemas

## Main Pages

- **Home (`/`)**: Landing page showcasing the application features
- **Ride (`/ride`)**: Main interface for booking rides with map and location selection

## API Routes

- **/api/map**: Endpoints for location coordinates and ride duration calculations
- **/api/db**: Endpoints for Sanity database operations

## Learn More

To learn more about the technologies used:

- [Next.js Documentation](https://nextjs.org/docs)
- [Mapbox GL JS Documentation](https://docs.mapbox.com/mapbox-gl-js/api/)
- [Ethers.js Documentation](https://docs.ethers.io/)
- [Sanity.io Documentation](https://www.sanity.io/docs)

## Deployment

Deployed on https://ride-base.vercel.app/

This application is deployed on Vercel, the platform from the creators of Next.js.
