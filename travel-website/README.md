# Performance Testing Practice

## 1. Application Overview

This project uses a sample travel agency website to practice performance testing.
**Application Under Test:** [BlazeDemo](https://blazedemo.com/)

The application allows users to search for flights, select a flight, enter passenger details, and complete a booking.

The booking process consists of four pages:

### Page 1 – Flight Search
Users select their departure and destination cities using dropdown menus.

**Main functionality:**
- Select departure city.
- Select destination city.
- Search for available flights.

### Page 2 – Flight Selection
The application displays available flights based on the selected route. For this practice scenario, the search is from Paris to Buenos Aires.

**Main functionality:**
- View available flights.
- Compare flight details and prices.
- Select a flight.

### Page 3 – Booking Details
After selecting a flight, users are redirected to a booking form where they enter their information.

**Main functionality:**
- Review flight details.
- Enter passenger information.
- Fill in the required booking fields.
- Submit the booking.

### Page 4 – Booking Confirmation
After submitting the form, the application displays a confirmation page containing a thank-you message and the booking details.

**Main functionality:**
- Verify the booking confirmation.
- Review the confirmed flight information.

## 2. Business Workflow

The main booking flow is:

1. Search for flights.
2. Select an available flight.
3. Enter passenger details.
4. Submit the booking.
5. View the confirmation page.

**Note:** The 40-user limit is an initial testing assumption.