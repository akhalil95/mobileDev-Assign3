# ADR: Retail Company 

## Decision 1: Hybrid App
We choose to develop a Hybrid app.
### Rationale
It offers offline mode support, browsing of products and order histories, syncing data when online. It also enables the app to run on both Android and iOS platforms. React Native framework offers seamless integration with push 
notifications.

## Decision 2: React Native
We opt for React Native as our primary UI framework.
### Rationale 
React Native has the ability to write once and deploy on both iOS and Android. It supports offline data access and can integrate well with push notfication services, making it ideal for the retail app.

## Decision 3: Node.js
Node.js will serve as the backend language.
### Rationale 
Node.js is suitable for high-traffic apps. It has a vast npm repository for various libraries, including payment gateways and analytic tools. Its compaitable with JSON-based data exchange align with React Native frontend.

## Decision 4: Permissions
The app will request minimal permissions: internet access, push notfications, and locations.
### Rationale
These permissions are essential for the core functionalities of the app, including offline browsing, push notfications, and location-based services.

## Decision 5: Local Storage and Cloud Sync
Combination of local storage for offline data access and cloud database for data sync when online.
### Rationale
Allows users to browse products and view orders offline. Ensures up-to-date information across devices and supports the loyalty program's data management.

## Decision 6: Payment Gateways
We will use Stripe and Paypal.
## Rationale
They support multiple payment methods and are easy to integrate.
