#  Two-Wheeler Marketplace Web App

A *full-stack marketplace platform* for buying, selling, and exploring *bikes, scooters, and EVs*.
This project solves the drawbacks of existing second-hand bike apps like *OLX/Quikr* by adding *trust, AI-powered verification, transparency, and after-sale services*.

---

##  Features

###  Core Marketplace

* Browse *bikes, scooters, and EVs*.
* Advanced *search & filters* by brand, price (₹), year, mileage, and fuel type.
* *Vehicle details page* with specs, images, and on-road price.
* *Compare models side-by-side*.
* *Financial tools*: EMI calculator (₹), fuel cost calculator (Petrol vs EV).
* *Upcoming launches* with price and release details.
* *Showroom explorer* with Google Maps integration.
* *Book test rides* directly from the app.
* *Used bike marketplace* with seller ads and buyer search.

---

###  Trust & Safety

* *AI Image Detection* to block fake/duplicate images.
* *RC & Insurance verification* (via VAHAN/DigiLocker APIs or mock).
* *Verified Seller Badges* for trusted sellers.
* *Inspection reports* for used bikes.

---

###  Transparency & Pricing

* *AI-powered Market Price Estimator* for used bikes.
* *Bike History Reports* (ownership count, accidents, insurance claims).
* *Price vs Market graphs* to aid buyer decisions.

---

###  Communication & Payments

* *In-app chat* with phone masking.
* *Predefined FAQs* for quick responses.
* *Spam protection*: only verified buyers can contact sellers.
* *Escrow payments* with Razorpay (test mode).

---

###  After-Sale Services

* *Digital RC transfer assistance*.
* *Insurance renewal integration*.
* *Optional warranty packs* (engine/gearbox).

---

##  Tech Stack

* *Frontend*: React.js / Next.js + TailwindCSS
* *Backend*: Node.js + Express
* *Database*: MongoDB
* *Authentication*: Firebase Auth / JWT
* *AI Image Detection*: TensorFlow.js / OpenCV.js
* *Payments*: Razorpay (test mode)
* *Maps API*: Google Maps

---

##  Problem Solved

Existing second-hand apps (OLX, Quikr, etc.) have issues like:

* Fake or misleading listings.
* Lack of transparent pricing & history.
* No proper communication or after-sale support.

 This app *fills the gaps* with *trust, safety, AI verification, transparent pricing, and extra services*.

---

##  End Goal

A *secure, transparent, and user-friendly marketplace* for two-wheelers in India that bridges the trust gap and enhances the user experience beyond OLX/Quikr.

---

##  Getting Started

1. Clone the repo:

   bash
   git clone https://github.com/your-username/two-wheeler-marketplace.git
   cd two-wheeler-marketplace
   
2. Install dependencies:

   bash
   npm install
   
3. Run the app:

   bash
   npm run dev
