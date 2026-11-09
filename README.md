# RouteWise – Bus Booking Analytics Dashboard

A beginner-friendly, pastel-colour dashboard starter for the Solvathon bus ticket analytics challenge.

## Included features
1. Ticket analytics: total, confirmed, cancelled and pending tickets.
2. Revenue analysis: daily confirmed-fare revenue.
3. Passenger analytics: passenger-seat counts over time.
4. Route analysis: most and least booked routes.
5. Time analysis: peak booking hours and departure-time patterns.
6. Cancellation analysis: cancellation rate and cancelled travel-date trend.
7. Intelligent insights: rule-based observations and a simple 7-day linear trend estimate.

Also included:
- Route and status filters
- CSV export
- Responsive layout for mobile and desktop
- Sample booking records

## Run it
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Internet access is needed to load Chart.js from its CDN.

No Python installation or server is needed for this first frontend demo.

## Important limitations
- The dashboard currently uses sample data stored in the JavaScript `bookings` array.
- It is a frontend prototype, not yet connected to a live booking database or backend.
- Revenue is calculated from confirmed fares only. Refunds, taxes, commissions and payment fees are not modelled.
- The demand estimate is a simple illustrative linear trend, not a validated machine-learning forecast. Do not present it as accurate real-world prediction.
- For a real submission, connect an approved dataset/backend, validate calculations, handle privacy securely, and test edge cases.

## Where to edit sample data
Open `index.html` and find `const bookings = [`.
Each booking has:
- `id`, `name`, `route`
- `booked` (booking date/time)
- `travel` (travel date)
- `seats`, `fare`
- `status` (`Confirmed`, `Cancelled`, or `Pending`)
- `departure` (`Morning`, `Afternoon`, `Evening`, or `Night`)

Use fictional data for demos unless your team has permission to use real passenger data.
