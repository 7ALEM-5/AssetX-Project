# AssetX

A B2B marketplace for surplus and used business assets

AssetX is a web-based B2B marketplace that helps companies sell surplus, used, or obsolete business assets and helps other companies acquire equipment at below-new prices. The MVP focuses on electronics in Egypt and brings three transaction models together in one platform: fixed-price listings, auctions, and Requests for Quotation (RFQs).

AssetX is designed to make business-asset trading more organized and transparent than relying on brokers, personal networks, or general-purpose classifieds. Company verification, listing moderation, transaction status tracking, and basic dispute handling help create a more trusted environment for companies that may not have worked with one another before.


MVP note: AssetX is currently scoped as a pilot MVP. Payments are simulated; the platform does not process real payments or provide logistics, inspection, or physical handover services.




The problem

Companies often accumulate equipment they no longer need after upgrades, restructuring, or changes in operations. Selling these assets can be difficult: businesses may depend on personal contacts, brokers, or disconnected online groups, which can limit reach, add friction, and make it harder to understand the asset's value.

At the same time, startups and small and medium-sized businesses need affordable equipment but may struggle to find suitable items, compare options, and determine whether a seller is a reliable business. This leaves corporate supply and demand fragmented.

AssetX aims to connect these two sides through a dedicated marketplace where companies can discover assets, make offers, bid in auctions, and publish their own purchasing requirements.

Product goals

•
Provide one organized marketplace for business assets in Egypt.

•
Support fixed-price sales, auctions, and RFQs in a single product.

•
Build trust through company profiles and an Admin-reviewed verification badge.

•
Launch with electronics and validate the marketplace through a small company pilot.

•
Test whether companies are willing to complete transactions through the platform before expanding categories or monetization.

User roles

Buyers

Companies looking for affordable business equipment. Buyers can search and filter listings, purchase eligible fixed-price assets, bid in auctions, and publish RFQs to receive offers from sellers.

Sellers

Companies with surplus assets. Sellers can create individual or batch listings, choose a fixed-price or auction model, manage listing statuses, and submit offers to relevant RFQs.

Platform administrators

AssetX operations users who review company verification requests and listings, monitor auctions and RFQs, manage company accounts, and review and resolve disputes.

Visitors

Unauthenticated users who can browse published marketplace listings and company profiles. Actions that require a verified company account are restricted until verification is complete.

A company may participate as a buyer, seller, or both, subject to the final account and permission design.

Core capabilities

Marketplace discovery

•
Browse published electronics listings.

•
Search by keyword and use filters, sorting, and asset details to find relevant equipment.

•
View seller company profiles and verification status.

Fixed-price transactions

•
Buyers can initiate a purchase for an eligible published listing.

•
The listing is reserved when the purchase flow succeeds.

•
The transaction progresses through simulated payment and buyer receipt confirmation.

•
The listing is marked as sold when the transaction is completed.

Auctions

•
Sellers can publish timed auctions for eligible assets.

•
Verified buyers can place bids that meet the starting price or minimum increment rules.

•
Auction bidding requires a simulated refundable deposit.

•
Buyers are notified when they are outbid; the auction closes automatically at its end time.

•
A winning bid creates a transaction that continues through the purchase and receipt-confirmation flow.

Requests for Quotation (RFQs)

•
Buyers can publish a description of what they need, including relevant specifications and a deadline.

•
Sellers can browse open RFQs and submit offers before the deadline.

•
Buyers can compare offers and select one, creating a transaction.

•
RFQs can expire or be cancelled; sellers cannot submit offers to their own company's RFQ.

Company verification and trust

•
Companies register with company details and confirm their email address.

•
Admins review company information and approve, reject, or request more information.

•
Approved companies receive a public verified badge.

•
Unverified companies may browse, but actions requiring a verified business account are restricted.

Listing management and moderation

•
Sellers can create a listing with asset details, category, condition, quantity, location, images, and sale type.

•
Sellers can save drafts, submit listings for review, and manage eligible listings.

•
Admins approve or reject submitted listings; rejected listings include a reason so the seller can make corrections and resubmit.

Transactions and disputes

•
Buyers and sellers can follow transaction status and see the next required action.

•
Either party to an eligible transaction can file a dispute.

•
Admins review the transaction and dispute details, record a resolution, and notify both parties.

Notifications and administration

•
In-app and email notifications communicate important account, listing, auction, RFQ, and transaction updates.

•
Admin tools support verification, moderation, company-account management, and monitoring of active auctions and RFQs.

Typical user journeys

Selling an asset

1.
Register a company account and confirm the company email.

2.
Complete the company verification process.

3.
Create an asset listing or batch and choose fixed price or auction.

4.
Submit the listing for Admin review.

5.
Once approved, manage the published listing and follow buyer activity and transaction updates.

Buying at a fixed price

1.
Search and filter the marketplace.

2.
Review the asset details and seller company profile.

3.
Confirm the purchase and simulated-payment terms.

4.
Follow the transaction status and coordinate physical handover outside the platform.

5.
Confirm receipt to complete the simulated transaction flow.

Participating in an auction

1.
Open an active auction and review its closing time, current bid, minimum next bid, and deposit information.

2.
Complete the simulated deposit step and submit a valid bid.

3.
Follow bid status and notifications.

4.
If the winning bid is yours, continue through the transaction and receipt-confirmation flow.

Requesting equipment through an RFQ

1.
Publish an RFQ describing the equipment needed and its deadline.

2.
Review offers submitted by sellers.

3.
Compare offers and select the preferred one.

4.
Continue with the transaction created from the selected offer.

MVP scope

The MVP is focused on validating the core marketplace and transaction journeys for electronics in Egypt. Its intended scope includes:

•
Company registration and manual Admin verification.

•
Electronics asset and batch listings.

•
Fixed-price purchases.

•
Basic timed auctions with simulated refundable deposits.

•
RFQs and seller offers.

•
Search, filters, and sorting.

•
Seller dashboard and listing management.

•
Admin moderation and monitoring.

•
Basic dispute handling.

•
In-app and email notifications.

•
Sandbox/simulated payment flows.

Out of scope for the MVP

The following capabilities are not part of the current MVP scope:

•
Native mobile applications.

•
AI-based pricing or valuation.

•
Logistics, delivery, or asset inspection services.

•
Advanced analytics or advanced auction features.

•
Live payment processing or real-money escrow.

•
Automated company verification.

•
Multiple user accounts within one company.

•
An Arabic-language interface.

These may be considered in future iterations after pilot feedback and validation.

Trust, payments, and handover

Company verification means that the company has been reviewed by an AssetX administrator; it is not a guarantee of the quality or condition of a specific asset. Asset details and condition should be reviewed by buyers before proceeding.

All payment activity in the MVP is simulated and does not move real money. Physical inspection, collection, delivery, and handover take place outside the platform and are coordinated by the companies. The product should clearly communicate these limitations throughout the relevant flows.

Pilot and success measures

The initial pilot is intended to validate whether verified companies will discover, negotiate, and complete asset transactions through AssetX. The project documentation identifies these success measures:

•
Onboard 10 verified companies, with 0% introductory commission during the pilot.

•
Publish listings across electronics subcategories.

•
Create RFQs and receive seller responses.

•
Demonstrate completed pilot transactions through fixed-price, auction, and RFQ journeys.

•
Keep search and filtering under two seconds and bid acknowledgement under one second.

•
Assess whether the platform can reduce reliance on brokers and validate willingness to transact online.

Business model

The proposed primary revenue stream is a commission on successful transactions. The commission rate and whether it is paid by the seller, buyer, or shared between both sides are to be determined through customer validation.

Potential future revenue streams include featured listings and premium company subscriptions. The pilot prioritizes validating transactions and the commission model before scaling.

Product status and roadmap direction

AssetX is documented as an MVP project developed within the Digital Egypt Pioneers Initiative. The recommended implementation sequence is:

1.
Fixed-price listing and purchase journey.

2.
RFQ creation, offer submission, and comparison.

3.
Basic auctions, including deposit and auction-end states.

4.
Pilot testing with verified companies and iteration based on user feedback.

5.
Consider expansion to additional categories and monetization after validation.

The product documentation identifies company onboarding and marketplace liquidity—bringing sellers and buyers into the marketplace together—as key pilot challenges.

Documentation

The project documentation describes the proposal, requirements, use cases, data model, risks, and MVP boundaries. UX planning should also account for the status and exception cases in registration, verification, listing review, auctions, RFQs, transactions, and disputes.

Technology

The project documentation does not specify a final technology stack. Add the selected frontend, backend, database, hosting, and development setup here once those decisions are confirmed.

Getting started

Setup and run instructions should be added after the repository's technology stack and project scripts are finalized. Include the required runtime versions, environment variables, database setup, development command, test command, and any seed-data instructions here.

Team

•
Mohamed Ashraf

•
Mohamed Mostafa

•
Ezz Mohamed

•
Mohamed Yasser

•
Youssef Moataz

Project context

Developed as a project within the Digital Egypt Pioneers Initiative.

