# Aviv Innovations: Project Showcase

Client and product work by **Judah Abib Ebenezer**, built through Aviv Innovations, Coimbatore. Source code for client projects stays private because it belongs to the clients. This repo describes what each project does, how it's built, and what I was responsible for. I'm happy to walk through the code in an interview.

| Project | Client | Platform | Stack | Status |
|---|---|---|---|---|
| [Community Alerts / Community Platform](#community-alerts) | Aviv Innovations (own product) | Android, iOS | React Native, Expo, Supabase | Android live; platform in progress |
| [Shelter House Church Platform](#shelter-house-church-platform) | Shelter House | iOS, Android, Web | Expo, TypeScript, Supabase | Completed |
| [HB Tracker](#csr-field-tracking-apps) | Dreamz Foundation, Mankind Pharma CSR | Android + web admin | Mobile app + admin panel | Completed |
| [PCOD Tracking](#csr-field-tracking-apps) | Dreamz Foundation, Mankind Pharma CSR | Android + web admin | Mobile app + admin panel | Completed |
| [Kitchen Garden Tracking](#csr-field-tracking-apps) | Dreamz Foundation, Mankind Pharma CSR | Android + web admin | Mobile app + admin panel | Completed |
| [Garbage Dumping Tracker](#csr-field-tracking-apps) | Dreamz Foundation, ZF CSR | Android + admin | Photos + GPS | Completed |
| [Budget Accounts Tracker](#budget-accounts-tracker) | Dreamz Foundation | Web | 5 role-based logins | Completed |
| [E-commerce storefronts](#e-commerce-storefronts) | Deluxe Medical Pharmacy, Ghats Aura, Bruno Bars | Web | Storefront + admin | Completed |
| [Business dashboards](#business-dashboards) | El Tribo, Ghats Aura | Web | Google Sheets backend, AI insights | Completed |
| [Team Task Manager](#team-task-manager) | WellDropp | Android + web admin | Teams, projects, tasks | Completed |

---

## Community Alerts
Notifies residents of a gated community the moment a vendor (milk, vegetables, laundry, gas) reaches the gate. It replaces a noisy WhatsApp group.
- **Roles:** president, resident and vendor, with join codes and approvals
- **Backend:** Supabase Postgres with Row Level Security, Realtime screens, and push notifications sent through a Supabase Edge Function
- **Next:** extending it into a full community platform for iOS and Android with dues tracking

<!-- screenshots: add images to /screenshots and link them here -->

## Shelter House Church Platform
A monorepo with a member app (daily devotions, urgent and regular announcements, events and RSVP) and an admin console on web and Android. Both share one Supabase backend and a common data layer.

## CSR field-tracking apps
Four Android apps with web admin panels for health and environment CSR programs:
- **HB Tracker:** tracks haemoglobin levels of anaemia patients in tribal villages and follows their improvement
- **PCOD Tracking:** tracks women's PCOD symptoms and progress after using herbal napkins
- **Kitchen Garden Tracking:** records what was distributed to women for kitchen gardens and the yield
- **Garbage Dumping Tracker:** citizens report garbage dumps with photos and GPS location, and admins track the clean-up

## Budget Accounts Tracker
A web platform with five levels of login: budget request, approval by the project manager, authorization by the finance head, transfer by head accounts, and expense tracking with bill uploads by the project accountant.

## E-commerce storefronts
Storefronts with cart, wishlist and checkout, plus order-management admin panels. Bruno Bars takes orders over WhatsApp, and the owner edits the store from a phone.

## Business dashboards
Analytics dashboards that read live data from Google Sheets. The El Tribo dashboard adds AI-generated business insights and advice. The Ghats Aura and Shelter House version generates bills automatically and saves them to Google Drive.

## Team Task Manager
A web admin panel and Android app for creating teams and projects, assigning tasks and setting up member accounts.

---
📫 judahaez@gmail.com · 🌐 [avivai.app](https://avivai.app)
