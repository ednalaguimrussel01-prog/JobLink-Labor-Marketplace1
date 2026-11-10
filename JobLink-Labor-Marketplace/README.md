# JobLink – Labor Marketplace

JobLink is a browser-based labor marketplace prototype that connects customers who need work done with workers looking for jobs.

## Features

- User registration as a customer or worker
- User login and logout
- Admin dashboard for viewing and activating/deactivating accounts
- Customers can post job requests
- Job categories: Electrical, Plumbing, Cleaning, and General Labor
- Workers can accept open jobs and mark their accepted jobs as completed
- Customers can rate workers after job completion
- Job status indicators and category filtering
- Browser localStorage is used to save users and jobs on the current browser

## Technologies

- HTML
- CSS
- JavaScript
- Browser localStorage

## How to run

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Register a customer or worker account, or use one of the sample accounts below.

## Sample accounts

- Admin: `admin` / `admin123`
- Customer: `customer1` / `pass123`
- Worker: `worker1` / `pass123`

These are demonstration credentials for the prototype. Change or remove them before any real-world use.

## Notes

This version is a front-end prototype. It does not use a server-side backend or a shared database. Data is stored in the browser's localStorage, so it is local to that browser and device. The sample implementation also stores passwords in browser storage; it is not suitable for production use without secure server-side authentication and password hashing.
