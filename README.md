# BranchOps Customer

A homeowner-first responsive experience for exploring windows and doors, shaping a preliminary project estimate, sharing opening details and saving a project summary.

## Included

- Responsive homeowner-facing landing page and product category exploration.
- Four-step project builder: category and quantity, product preferences and approximate dimensions, photo/video selection, and contact details.
- Preliminary estimate calculator with category, material, quantity and approximate-size adjustments.
- Local browser persistence for saved projects.
- Project summary modal, copy-to-clipboard, print and delete actions.
- No real payment, e-signature, email, SMS, CRM, inventory, scheduling or backend integrations.

## Run locally

Open index.html in a browser, or serve this folder with any static web server.

## Deploy on Render

1. Create a New Static Site in Render.
2. Connect https://github.com/sachintechpro/branchops-customer.
3. Branch: main.
4. Build command: leave blank.
5. Publish directory: .
6. Create the static site.

## Demo boundaries

- Estimates are illustrative planning ranges, not formal quotes or offers.
- Dimensions are customer-entered and must be professionally verified before ordering.
- Browser storage is local to the current browser/device; it is not a customer account or cloud database.
- Selected media filenames are displayed, but no upload or transmission occurs.
- Submitting this form does not create an operational job, take payment, execute an agreement or schedule installation. Those require later review and explicit business confirmation.

## Structure

- index.html — page structure
- styles.css — responsive visual system
- app.js — project builder, estimate logic and local persistence
