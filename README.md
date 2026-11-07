# RenderRCars — Premier Luxury & Supercar Rentals (React Edition)

> Production-grade **React** application built with **Vite** and **React Router DOM**.

---

## 🏎️ Active URL Routes

| Route | Page Component | Description |
| :--- | :--- | :--- |
| **[`/`](http://localhost:3000/)** | `HomePage` | Flagship landing page with real-time telemetry, advanced sort (Price, Rating, Horsepower), seating filter (2, 4-5, 7 seats), video showcase, and FAQs |
| **[`/details/:carId`](http://localhost:3000/details/bmw-m4)** | `CarDetailsPage` | Deep-linkable vehicle specifications (e.g. `/details/bmw-m4`, `/details/audi-r8`, `/details/toyota-fortuner`, `/details/mercedes-amg`), engine specs, drivetrain, and luxury features |
| **[`/booking`](http://localhost:3000/booking?car=bmw-m4)** | `BookingPage` | 4-step reservation scheduler & live pricing calculator (`/booking?car=bmw-m4`) |
| **[`/agreement`](http://localhost:3000/agreement)** | `AgreementPage` | 11-clause master self-drive rental contract with digital signature acceptance |
| **[`/payment`](http://localhost:3000/payment)** | `PaymentPage` | Multi-method checkout: UPI (Dynamic QR/VPA), Credit/Debit Card (3D visual preview), Net Banking, EMI, and OTP verification |
| **[`/confirmation`](http://localhost:3000/confirmation)** | `ConfirmationPage` | Official reservation voucher, booking reference code, and 1-click printable receipt (`window.print()`) |
| **[`/my-bookings`](http://localhost:3000/my-bookings)** | `MyBookingsPage` | Driver member itinerary portal showing active/completed trips, totals paid, and 1-click printable voucher downloads |
| **[`/wishlist`](http://localhost:3000/wishlist)** | `WishlistPage` | Personal dream garage with real-time bookmark counter and one-click reservation |
| **[`/login`](http://localhost:3000/login?role=driver)** | `LoginPage` | Standalone authentication portal (`/login?role=driver` or `/login?role=admin`) |
| **[`/admin`](http://localhost:3000/admin)** | `AdminPage` | Protected fleet command dashboard, live KPI analytics, fleet vehicle management, and booking status controls |

---

## 🚀 Quick Start

```bash
# 1. Install Dependencies
npm install

# 2. Run Development Server
npm run dev

# 3. Build for Production
npm run build

# 4. Preview Build
npm run preview
```
