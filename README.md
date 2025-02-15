# Nike Shoes Marketplace

## Day 1 - Choosing the Marketplace

### Marketplace Name: **Nike Shoes**

### Why Nike Shoes?
1. **For Everyone** - Our marketplace offers shoes for all age groups, including kids, adults, young girls, and boys.
2. **Variety** - We provide a wide range of shoes, including:
   - **Sneakers**
   - **Sports Shoes**
   - **Lifestyle Shoes**
   - **Limited Edition Shoes**
   - **High-Quality Products**
3. **Customer Benefits**
   - Fast order supply with efficient delivery.
   - Affordable pricing for every customer.
   - Guaranteed discounts on products.
   - 100% authentic and quality-assured products.
   - Ensuring customer satisfaction with no complaints.

## Day 2 - Frontend & Backend Requirements

### Frontend Requirements
- **Notifications**: Users receive alerts for order updates, promotions, and reviews.
- **Review System**: Users can leave and view product reviews with ratings.
- **User Interface**: Clean, simple, and easy-to-navigate layout for a seamless experience.
- **Responsive Design**: Optimized for both mobile and desktop users.
- **Essential Pages:**
  - **Home**: Featuring products and promotions.
  - **Product Listing**: Categories, filters, and sorting options.
  - **Product Details**: Detailed info, images, and pricing.
  - **Cart**: Easy view and modification of items.
  - **Checkout**: Simple, secure checkout process.
  - **Order Confirmation**: Summary and thank-you message post-purchase.

### Backend - Sanity CMS
- **Leverage Sanity CMS** to manage all product information, customer profiles, and order data.
- **Custom Schemas**: Designed to align with business objectives from Day 1, ensuring flexibility and scalability.

### Third-Party APIs
- **Integrate essential third-party APIs** for services like shipment tracking, payment gateways, and other backend functionalities.
- **Real-time data access**: Ensuring APIs provide up-to-date data to enhance frontend performance and user experience.

## Day 3 - Setting Up Next.js and Sanity

### Project Setup
- **Create a Next.js Project**
- **Install Sanity** for content management
- **Generate an API Token** in Sanity
- **Add API Token** to `.env` file

### Sanity Schema Configuration
- **Create `product.ts`** in Sanity’s Schema Folder
- **Import the Schema** in `index.ts`

### Data Import & API Integration
- **Create a `scripts` Folder**
- **Create `importSanityData.mjs`** to handle data import
- **Update `package.json` Scripts** to include import functionality
- **Install Axios** for API requests
- **Send Data to Sanity via API**

### Data Fetching & Display
- **Create Query** to Fetch Data
- **Fetch Data** in `next.config.ts`
- **Display Data** in the Browser

## Day 4 - Building Dynamic Frontend Components

### Key Components to Build
1. **Product Listing Component** - Displays all available products with filtering and sorting options.
2. **Product Detail Component** - Shows detailed product information, including images, price, and description.
3. **Cart Component** - Allows users to add, remove, and view items before proceeding to checkout.
4. **Checkout Workflow Component** - Manages the checkout process, including payment and order confirmation.
5. **Header Component** - Provides easy navigation and accessibility across the marketplace.

## Day 5 - Testing Error Handling and Backend Integration Refinement

### Test Cases
- **Product Page Functionality** ✅
- **API Error Handling** ✅
- **Checkout Button** ✅
- **Product Detail Page** ✅
- **Cross-Browser Compatibility** ✅
- **Mobile Responsiveness** ✅

## Day 6 - Deployment Preparation and Staging

## Deployment Information
- **Platform**: Vercel
- **GitHub Repository**: [Nike-Shoes-Website](https://github.com/TayyabAli92/Nike-Shoes-Fully-Functionally-website)
- **Staging Environment URL**: [Staging](https://nike-shoes-topaz-seven.vercel.app/)

## Environment Setup
### 1. Hosting Platform Configuration
- Chosen Platform: Vercel
- Linked GitHub Repository with Vercel
- Configured build settings and added environment variables for secure deployment

### 2. Environment Variables Configuration
- **.env File**:
  - `NEXT_PUBLIC_SANITY_PROJECT_ID`: Sanity project identifier
  - `NEXT_PUBLIC_SANITY_DATASET`: Name of the production dataset
  - `API_KEY`: Authentication key for third-party services
- Securely uploaded environment variables to Vercel

## Staging Deployment
- Deployed the application to the staging environment.
- Verified that the build process was error-free and the site functioned as expected.

## Performance Evaluation
### 1. Desktop Performance
- Analyzed rendering time, interactivity, and resource usage to ensure optimal desktop performance.

### 2. Mobile Performance
- Tested mobile navigation, page speed, and responsiveness to ensure a smooth user experience.


Stay tuned for daily updates as we progress through the hackathon!
