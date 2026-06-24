# Ecolife Management System

A web-based operations and booking management platform built for Ecolife Pest Control. The system enables the admin team to manage bookings, assign technicians, track job statuses, and generate sales reports across all four branches.

---

## Live URL

```
https://ecolifemanagementsystem.co.ke/
```

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (single file per page, no framework)
- **Backend and Database:** Firebase Firestore
- **Authentication:** Firebase Auth (email and password)
- **Hosting:** GitHub Pages
- **Domain:** HostPinnacle (.co.ke) with Cloudflare DNS
- **Built by:** MtaaniWeb

---

## Pages

| File | Description |
|---|---|
| login.html | Entry point. Role-based redirect on login |
| dashboard.html | Admin overview with stats, recent bookings, and follow ups |
| new-booking.html | Create and assign a new job |
| bookings.html | Full bookings table with filters and status updates |
| technicians.html | Add and manage technicians across branches |
| technician-view.html | Technician personal job view and status updates |
| reports.html | Sales reports filtered by date, branch, technician, and payment status |

---

## User Roles

**Admin**
- Email: ecolifepestguard@gmail.com
- Full access to all pages and data across all branches

**Technician**
- Logs in with their personal email
- Sees only jobs assigned to them
- Can update job status from their view

---

## Branches

- Nairobi
- Nakuru
- Eldoret
- Mombasa

---

## Key Features

- Booking creation with full client and service details
- Technician assignment per booking
- Job status tracking: Pending, Assigned, Completed, Paid
- Automatic balance calculation per booking
- WhatsApp notification to technician on booking assignment
- Dashboard follow ups table showing all outstanding balances
- Sales reports per technician and per branch
- Customers per region breakdown
- Daily bookings log
- Pending balances report
- Print to PDF on reports page
- Mobile responsive across all pages

---

## Firebase Project

- **Project ID:** ecolife-system-ff2d6
- **Services used:** Firestore Database, Firebase Authentication, Firebase Hosting config

---

## Firestore Collections

| Collection | Purpose |
|---|---|
| bookings | All job records |
| technicians | Technician profiles and branch assignments |

---

## How to Add a Technician

1. Log in as admin
2. Go to Technicians page
3. Tap Add Technician
4. Enter name, email, branch, and phone
5. Firebase creates their account automatically and sends them a password setup email
6. Technician logs in at the same login URL

---

## How to Update Job Status

**Admin:** Open any booking from the bookings page, select new status in the modal, tap Update.

**Technician:** Open any job card from their view, select new status, tap Update.

---

## Maintenance

Built and maintained by MtaaniWeb.
For updates, new features, or support contact via WhatsApp: +254715392010

---

*Powered by MtaaniWeb. Your Journey to Online Success.*
