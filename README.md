# Carfare
Compare new and used car prices from dealers near you and see the estimated out-the-door total for each one: listed price, sales tax, doc fee, and title and registration. Estimates only.
- Search any make, model, year, ZIP, and distance
- New and used inventory
- Every price component shown per dealer
- Editable sales tax rate that re-prices results instantly
- Direct links to each listing
- Plain HTML/CSS/JavaScript front end, one Node.js serverless function, hosted on Vercel, listings from the MarketCheck API.
- api/search.js       Serverless search function
public/index.html   Front end and price calculator
.env.example        Environment variable template
Listing data provided by MarketCheck. Totals are estimates and not an offer. Confirm all prices, taxes, and fees with the dealer.
