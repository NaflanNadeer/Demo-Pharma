# Qatar Pharma interactive demo

A responsive React + Vite concept with a navy/white visual system and teal/mint accents. All integrations are simulated; use fictional customer and prescription data.

## Run

Node 22+ recommended (verified with Node 24).

```sh
npm ci
npm run dev
```

Production: `npm run build`. Serve the generated build with `npm run preview`.

## Demo walkthrough

1. Browse homepage categories or Shop products. Search and filter the catalog.
2. Open a product, adjust quantities and add it to your care bag. Normal saline requires quantities in multiples of ten.
3. Use Business account to activate a simulated verified corporate account: 15% negotiated pricing and Net-30 purchase orders.
4. Open your bag. Prescription orders need a sample file; only the filename is held in React session state. Select a destination to see illustrative shipping estimates. Submit an order.
5. Open Admin workspace from the footer. Approve prescription orders with a simulated clinical sign-off, then simulate payment receipt, dispatch and delivery. Corporate purchase orders require accounts approval.
6. Open My account to track the resulting status. Open Mobile app preview from the footer for an interactive phone-sized customer concept.

## Boundaries

No backend, authentication, actual upload, payment, ERP, OTP, WhatsApp messaging, carrier booking, GPS tracking or native app binaries. Data resets on reload. Business login is an explicit demo persona, not a security boundary. Shipping quotes are illustrative and do not establish pharmaceutical delivery eligibility. Arabic toggle demonstrates RTL layout and selected headline labels; complete Arabic translation is a production deliverable. Subsidiary isolation and multiple merchant accounts need discovery. Product descriptions and brand identity are illustrative pending client assets and review. Illustrations are local SVG assets. Fonts use Google Fonts with system fallbacks.

## Production discovery

Confirm Bright ERP version, API/sandbox access, warehouse inventory and customer price book mapping; authorized clinical roles and approval audit requirements; QIB post-approval payment and credit policies; subsidiary legal/merchant structure; destination and transport eligibility; Arabic translations; legacy exports; and service SLAs before fixing commercial estimates. Legal and regulatory assertions must be verified by qualified client advisors.
