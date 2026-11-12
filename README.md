<div align="center">

<!-- Hero Banner & Header Logo -->
<a href="https://github.com/TAIJULAMAN/IrelandGo-website">
  <img src="./public/Tourenzo.png" alt="Tourenzo Logo" width="240" />
</a>

<br />
<br />

<a id="overview"></a>

# Tourenzo — Ireland Luxury Private Car Transfers & Tours Platform

**A luxury private transportation and tour booking platform offering seamless Dublin airport transfers, custom hourly chauffeur services, guided day trips, and bespoke multi-day journeys across Ireland with real-time geospatial route calculation and secure Stripe checkout.**

<br />

<a id="tech-stack"></a>

<!-- Tech Stack Badges (for-the-badge style) -->

[![Next.js 16](https://img.shields.io/badge/Next.js%2016-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript 5](https://img.shields.io/badge/TypeScript%205-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS 4](https://img.shields.io/badge/Tailwind%20CSS%204-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![Google Maps API](https://img.shields.io/badge/Google%20Maps-Geocoding%20%26%20Routes-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)
[![Leaflet](https://img.shields.io/badge/Leaflet-Interactive%20Maps-199900?style=for-the-badge&logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Stripe](https://img.shields.io/badge/Stripe-Secure%20Payments-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/)
[![NextAuth.js](https://img.shields.io/badge/NextAuth.js-5.0%20Beta-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://authjs.dev/)
[![Radix UI](https://img.shields.io/badge/Radix%20UI-161618?style=for-the-badge&logo=radixui&logoColor=white)](https://www.radix-ui.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](#license)

<br />

<a id="cta-links"></a>

<!-- Live Demo & CTA Links -->
<p align="center">
  <a href="https://tourenzo.com"><b>Explore Live</b></a> &nbsp;•&nbsp;
  <a href="#architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#core-features"><b>Core Features</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/IrelandGo-website/issues"><b>Report Bug</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/IrelandGo-website/issues"><b>Request Feature</b></a>
</p>

<br />

<!-- Hero Banner Graphic -->
<img src="./public/day-trips.jpg" alt="Tourenzo Platform Overview" width="100%" />

</div>

---

## Table of Contents

- [ Title & Value Proposition](#overview)
- [ Tech Stack Badges](#tech-stack)
- [ Live Demo & CTA Links](#cta-links)
- [ Interface Preview](#interface-preview)
- [ Core Features & Service Portals](#core-features)
  - [ Dublin Airport & Intercity Private Transfers](#airport-transfers)
  - [ Flexible By-The-Hour Chauffeur Booking](#by-the-hour)
  - [ Curated Day Trips & Multi-Day Ireland Tours](#day-trips-tours)
  - [ Geospatial Route Mapping & Stop Calculation](#geospatial-mapping)
  - [ Dynamic Pricing Matrix & Vehicle Tiers](#pricing-matrix)
  - [ Seamless Stripe Payment & Booking Workflow](#stripe-booking)
  - [ Customer Dashboard, Trip History & Reviews](#customer-dashboard)
- [ Engineering Highlights & Architecture](#architecture)
  - [ System Architecture Overview](#system-architecture)
  - [ Vehicle Fleet & Service Capability Matrix](#service-matrix)
- [ Project Directory Structure](#project-structure)
- [ Developer Info & Socials](#developer-info)
- [ License & Proprietary Notice](#license)

---

<a id="interface-preview"></a>

## Interface Preview

Experience luxury mobility, real-time map routing, and instant booking funnels built with Next.js 16, React 19, Tailwind CSS 4, Google Maps, and Leaflet.

|                          **Curated Ireland Day Trips**                           |                                 **By-The-Hour Chauffeur Hire**                                 |
| :------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------: |
| <img src="./public/day-trips.jpg" alt="Curated Ireland Day Trips" width="480" /> | <img src="./public/by-the-hour.jpg" alt="By-the-Hour Private Chauffeur Service" width="480" /> |
|        _Iconic routes: Cliffs of Moher, Ring of Kerry, Giant's Causeway_         |                 _Flexible hourly private car rental with dedicated chauffeur_                  |

|                        **Dublin Airport Transfers**                         |                                  **Luxury Fleet & Safety**                                   |
| :-------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: |
| <img src="./public/plane.png" alt="Dublin Airport Transfers" width="480" /> | <img src="./public/Safety&Comfort.jpg" alt="Safety & Comfort Fleet Standards" width="480" /> |
|       _Punctual terminal meet & greet, flight tracking & zero delays_       |            _Pristine Mercedes-Benz executive sedans, premium SUVs & luxury vans_             |

---

<a id="core-features"></a>

## Core Features & Service Portals

Tourenzo delivers a five-star private chauffeur experience across the Republic of Ireland and Northern Ireland, powered by smart dispatch calculations and instant digital reservations.

<a id="airport-transfers"></a>

### **Dublin Airport & Intercity Private Transfers**

- **Terminal Meet & Greet**: Professional drivers greet passengers in arrivals with custom name boards, assisting with luggage handling.
- **Real-Time Flight Tracking**: Flight number integration automatically adjusts pick-up times for delays or early arrivals with complimentary wait time.
- **Fixed-Rate Intercity Transfers**: Transparent fixed pricing connecting Dublin Airport (DUB), Shannon (SNN), Cork (ORK), Belfast (BFS), and Galway.

<a id="by-the-hour"></a>

### **Flexible By-The-Hour Chauffeur Booking**

- **Custom Duration Rental**: Reserve private chauffeurs by the hour (from 2 hours up to full-day dedicated hire).
- **As-Directed Itineraries**: Total flexibility to alter routes, add on-the-fly stops, and conduct business meetings or shopping trips with waiting drivers.
- **Corporate & VIP Hospitality**: Discreet, professional executive travel for visiting delegations, golfers, and event attendees.

<a id="day-trips-tours"></a>

### **Curated Day Trips & Multi-Day Ireland Tours**

- **Signature Day Trips (`/day-trips`)**: Pre-packaged full-day excursions to the Cliffs of Moher, Galway Bay, Connemara, Wicklow & Glendalough, and Belfast Titanic Quarter.
- **Bespoke Multi-Day Expeditions (`/multi-day-tours`)**: Comprehensive cross-country itineraries combining luxury chauffeur transport, scenic stops, and luxury lodge transfers.
- **Interactive Attraction Stops (`/stopage`)**: Dynamically add sightseeing stops (e.g., castles, distilleries, national parks) with automated pricing adjustments.

<a id="geospatial-mapping"></a>

### **Geospatial Route Mapping & Stop Calculation**

- **Dual-Engine Mapping (Google Maps & Leaflet)**: Fast address autocomplete (`use-places-autocomplete`), interactive maps (`@react-google-maps/api`, `react-leaflet`), and route visualization.
- **Accurate Distance & Time Estimations**: Calculates accurate drive durations, toll allowances, and optimal driving routes.
- **Dynamic Waypoint Insertion**: Add intermediate waypoints and stopovers with automated distance-based charge recalculations.

<a id="pricing-matrix"></a>

### **Dynamic Pricing Matrix & Vehicle Tiers**

- **Tiered Fleet Selection**:
  - _Executive Sedan_: Mercedes-Benz E-Class / BMW 5 Series (1-3 Passengers)
  - _Luxury Saloon_: Mercedes-Benz S-Class (VIP travel)
  - _Executive SUV / MPV_: Mercedes-Benz V-Class / Luxury Van (Up to 7-8 Passengers + Luggage)
- **Granular Pricing Engine**: Transparent base rates, per-kilometer formulas, waiting time fees, and regional tolls.

<a id="stripe-booking"></a>

### **Seamless Stripe Payment & Booking Workflow**

- **One-Click Reservation Funnel (`/booking`)**: Four-step checkout capturing flight details, passenger counts, vehicle tier, and custom requests.
- **Secure Stripe Integration**: PCI-compliant payment intents (`/stripe`), instant authorization, and instant booking confirmation dispatch (`/payment-confirmation`).
- **Cancellation & Refund Protections (`/payment-cancle`)**: Built-in grace period handling for risk-free bookings.

<a id="customer-dashboard"></a>

### **Customer Dashboard, Trip History & Reviews**

- **Traveler Dashboard (`/dashboard`)**: View upcoming itineraries, track assigned driver details, and access printable receipts.
- **Historical Bookings**: Comprehensive archive of past completed transfers and invoices.
- **Verified Customer Reviews (`/review`)**: Post-journey rating system evaluating vehicle condition, driver punctuality, and overall trip satisfaction.

---

<a id="architecture"></a>

## Engineering Highlights & Architecture

<a id="system-architecture"></a>

### System Architecture Overview

Tourenzo unites Next.js 16 App Router, Redux Toolkit state hydration, Google Maps & Leaflet GIS services, and Stripe payment processing.

```
+-----------------------------------------------------------------------------------+
|                        Client & Booking Interface (Browser)                       |
|   Next.js 16 App Router | React 19 | Tailwind CSS 4 | Google Maps API | Leaflet   |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼ (Type-safe RTK Query Hooks)
+-----------------------------------------------------------------------------------+
|                           State & Pricing Gateway Layer                           |
|   Redux Toolkit Store | RTK Query (transfersApi, bookingApi) | Redux Persist      |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼ (RESTful API / Geospatial Distance Engine)
+-----------------------------------------------------------------------------------+
|                        Backend Dispatch & Payment Gateway                         |
|   Express API | Google Distance Matrix | Stripe Payment Intents | NextAuth v5     |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼
+-----------------------------------------------------------------------------------+
|                        Database & External Cloud Services                         |
|   PostgreSQL / MongoDB | Cloudinary Assets | Email Notification Triggers (SMTP)   |
+-----------------------------------------------------------------------------------+
```

<a id="service-matrix"></a>

### Vehicle Fleet & Service Capability Matrix

| Vehicle Category    | Max Passengers | Luggage Capacity  | Dublin Airport | By-The-Hour Hire |  Day Trips  | Multi-Day Tours |
| :------------------ | :------------: | :---------------: | :------------: | :--------------: | :---------: | :-------------: |
| **Executive Sedan** |  3 Passengers  | 2 Large + 2 Small |  Full Access   |   Full Access    | Full Access |   Full Access   |
| **Luxury Saloon**   |  3 Passengers  | 2 Large + 2 Small |  Full Access   |   Full Access    | Full Access |   Full Access   |
| **Executive MPV**   |  6 Passengers  | 6 Large + 4 Small |  Full Access   |   Full Access    | Full Access |   Full Access   |
| **Luxury Van**      |  8 Passengers  | 8 Large + 6 Small |  Full Access   |   Full Access    | Full Access |   Full Access   |

---

<a id="project-structure"></a>

## Project Directory Structure

```plaintext
IrelandGo-website/
├── app/                                # Next.js 16 App Router (Core Application Routes)
│   ├── about/                          # About Tourenzo, fleet standards & chauffeur team
│   ├── airport-transfers/              # Dublin Airport transfers, flight tracker & meet/greet
│   ├── auth/                           # Authentication flows (login, register, forgot-password)
│   ├── blog/                           # Ireland travel journal, destination guides & itineraries
│   ├── booking/                        # 4-Step interactive booking funnel & vehicle selector
│   ├── by-the-hour/                    # Hourly private chauffeur hire & customized city tours
│   ├── contact/                        # 24/7 customer support, bespoke booking inquiries & phone
│   ├── dashboard/                      # Customer portal (upcoming transfers, receipts, history)
│   ├── day-trips/                      # Curated single-day sightseeing tours across Ireland
│   ├── multi-day-tours/                # Bespoke multi-day travel itineraries & cross-country trips
│   ├── payment-cancle/                 # Graceful cancellation recovery view
│   ├── payment-confirmation/           # Confirmed reservation summary, reference & PDF vouchers
│   ├── settings/                       # User profile, notification preferences & billing settings
│   ├── stripe/                         # Stripe Elements checkout session & webhook validation
│   ├── transfer/                       # Quick point-to-point transfer quote engine
│   ├── transfers/                      # Destination directory & pre-calculated route guides
│   ├── globals.css                     # Global styles, Leaflet CSS & Tailwind CSS v4 variables
│   ├── layout.tsx                      # Root layout with Plus Jakarta Sans & AuthProvider
│   ├── loading.tsx                     # Loading skeleton and route transit indicators
│   ├── page.tsx                        # Homepage (Hero search, Fleet showcase, Top tours, Reviews)
│   ├── robots.ts                       # Search engine crawler instructions
│   └── sitemap.ts                      # Dynamic SEO sitemap generator
├── components/                         # Atomic, layout & domain React components
│   ├── layout/                         # ClientLayout, global navigation header & footer
│   ├── ui/                             # Radix UI & Shadcn primitives (Dialog, Select, Tabs)
│   └── ...                             # Booking steps, vehicle cards & interactive map pins
├── config/                             # Runtime environment & SEO configuration
│   ├── envConfig.ts                    # API base URL resolvers (api.tourenzo.com)
│   └── seoRoutes.ts                    # SEO route definitions & metadata rules
├── contexts/                           # React Context providers (AuthContext)
├── hooks/                              # Custom React logic hooks & map geocoding listeners
├── lib/                                # Core utility functions & class name utilities (cn)
├── public/                             # High-resolution assets, vehicle images & destination guides
│   ├── attractions/                    # Irish landmarks, castles & coastal scenic photography
│   ├── Images/                         # Tour photography, logos & client avatars
│   ├── mainPages/                      # Page headers & hero background media
│   ├── day-trips.jpg                   # Signature day trip banner
│   ├── by-the-hour.jpg                 # Hourly chauffeur banner
│   ├── plane.png                       # Airport transfers visual badge
│   ├── Safety&Comfort.jpg              # Fleet luxury and safety visual
│   ├── Tourenzo.png                    # Brand header logo
│   └── Tourenzo.webp                   # Optimized webp brand logo
├── Redux/                              # Centralized Redux Toolkit state architecture
│   ├── features/                       # RTK Query API slice definitions
│   │   ├── auth/                       # User authentication endpoints
│   │   ├── blogs/                      # Travel blog & destination articles API
│   │   ├── booking/                    # Booking reservation submission & status API
│   │   ├── client/                     # Customer profile endpoints
│   │   ├── contact/                    # Customer support message API
│   │   ├── contents/                   # Static page marketing CMS API
│   │   ├── dashboard/                  # Dashboard summary & active reservation stats
│   │   ├── dayTrip/                    # Curated day trip tours & stops API
│   │   ├── memory/                     # User preference & trip history caching
│   │   ├── multi-day-tours/            # Multi-day itineraries & pricing API
│   │   ├── navigation/                 # Dynamic header route navigation API
│   │   ├── newsletter/                 # Newsletter email subscription API
│   │   ├── notification/               # Real-time traveler alerts & updates API
│   │   ├── payments/                   # Stripe payment intent creation & capture API
│   │   ├── review/                     # Customer rating & feedback API
│   │   ├── settings/                   # Legal terms, FAQs, About & onboarding API
│   │   ├── stopage/                    # Attraction stops & detour fee calculation API
│   │   ├── support/                    # Help center & ticketing API
│   │   ├── transaction/                # Transaction records & invoice receipts API
│   │   ├── transfers/                  # Transfer routes, distance matrix & pricing API
│   │   ├── user/                       # User account & credentials API
│   │   ├── vehicles/                   # Fleet inventory, passenger limits & specifications API
│   │   └── baseApi.ts                  # Centralized RTK Query base configuration
│   ├── Slice/                          # Redux synchronous state slices (authSlice)
│   ├── hooks.ts                        # Typed Redux hooks (useAppDispatch, useAppSelector)
│   ├── ReduxProvider.tsx               # Client-side store hydration wrapper
│   └── store.ts                        # Redux store with redux-persist integration
├── services/                           # Third-party integrations & payment helper services
├── styles/                             # Custom layout styling & map leaflet overrides
├── utils/                              # Distance, currency (£ / €) & date formatting helpers
├── components.json                     # shadcn/ui configuration manifest
├── next.config.mjs                     # Next.js compiler, image whitelists & optimizations
├── package.json                        # Project dependencies, scripts & metadata
├── performance.md                      # Web Vitals & Lighthouse performance audit docs
├── postcss.config.mjs                  # PostCSS plugins for Tailwind CSS v4
├── price-matrix.md                     # Vehicle class pricing formulas & rates documentation
├── tsconfig.json                       # TypeScript compiler options & module paths
└── README.md                           # Comprehensive documentation & platform guide
```

---

<a id="developer-info"></a>

## Developer Info & Socials

Tourenzo is architected, developed, and maintained by experienced full-stack engineers and geospatial mobility specialists.

- **Md Shah Aman Patwary** — _Lead Full-Stack Software Engineer & Maintainer_
  - 🌐 GitHub: [@TAIJULAMAN](https://github.com/TAIJULAMAN)
  - 📧 Email: [taijulaman8@gmail.com](mailto:taijulaman8@gmail.com)

---

<a id="license"></a>

## License & Proprietary Notice

Copyright © 2026 Tourenzo. All rights reserved.

This software, including its user interface design, routing algorithms, dynamic pricing engine, and backend architecture, is private and proprietary. Unauthorized copying, distribution, decompilation, or commercial exploitation without prior written consent from Tourenzo is strictly prohibited.

<div align="center">
  <b>Built with ❤️ for luxury private journeys and unforgettable Irish adventures</b>
</div>
