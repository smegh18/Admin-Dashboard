# Marketplace Admin Panel

A comprehensive multi-role administration panel for the Demand24 marketplace platform, supporting restaurants, delivery services, booking management, and e-commerce operations.

## 🚀 Features

### Multi-Role Support
- **Admin Panel**: Complete system administration with full CRUD operations
- **Seller Dashboard**: Restaurant/shop management interface
- **Waiter Interface**: Order management for restaurant staff
- **Master Panel**: Service provider management system
- **Delivery Management**: Comprehensive delivery and logistics control

### Core Functionality
- 📊 **Dashboard & Analytics**: Real-time statistics and reports
- 🏪 **Shop Management**: Multi-vendor marketplace support
- 📦 **Product Catalog**: Complete product and inventory management
- 🛵 **Delivery System**: Advanced delivery zone and pricing management
- 📅 **Booking System**: Table reservations and appointment scheduling
- 💳 **Payment Processing**: Multiple payment gateways integration
- 🎯 **Marketing Tools**: Coupons, advertisements, and promotions
- 📱 **Mobile Ready**: Responsive design for all devices
- 🌍 **Multi-language**: i18n support with dynamic translations
- 💬 **Real-time Chat**: Firebase-powered communication system

### Advanced Features
- **POS System**: Point of sale integration
- **Gift Cards & Memberships**: Customer loyalty programs
- **Parcel Delivery**: Package delivery service management
- **Career Management**: Job posting and application system
- **Blog & Content**: Content management system
- **Review System**: Rating and feedback management
- **Notification Center**: Multi-channel notification system
- **Backup & Cache**: System maintenance tools

## 🛠️ Technology Stack

### Frontend
- **React 16.14.0** - Core framework
- **Ant Design 4.20.6** - UI component library
- **Redux Toolkit** - State management
- **React Router Dom 6.3.0** - Navigation
- **Axios** - HTTP client
- **ApexCharts** - Data visualization
- **React Beautiful DND** - Drag and drop functionality

### Backend Integration
- **Firebase** - Real-time database and authentication
- **Google Maps API** - Location services
- **CKEditor** - Rich text editing
- **QR Code Generation** - React QRCode

### Development Tools
- **Sass** - CSS preprocessing
- **i18next** - Internationalization
- **Prettier** - Code formatting
- **Webpack Bundle Analyzer** - Build optimization

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase account
- Google Maps API key

### Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd admin_website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Configuration**
   Create a `.env` file in the root directory:
   ```env
   REACT_APP_MAP_API_KEY=your_google_maps_api_key
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
   ```

4. **Firebase Configuration**
   - Set up Firebase project
   - Configure authentication
   - Set up Firestore database
   - Configure hosting (optional)

5. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

## 🏗️ Project Structure

```
src/
├── assets/                 # Static assets (images, css, scss)
├── components/             # Reusable UI components
│   ├── forms/             # Form components
│   ├── report/            # Report components
│   ├── shop/              # Shop-specific components
│   └── upload/            # File upload components
├── configs/               # Configuration files
│   ├── app-global.js      # Global app configuration
│   ├── i18next.js         # Internationalization config
│   └── theme-config.js    # Theme configuration
├── context/               # React context providers
├── helpers/               # Utility functions
├── layout/                # Layout components
├── redux/                 # State management
│   ├── slices/           # Redux slices
│   └── selectors/        # Redux selectors
├── routes/                # Route definitions
│   ├── admin/            # Admin routes
│   ├── seller/           # Seller routes
│   ├── waiter/           # Waiter routes
│   └── master/           # Master routes
├── services/              # API services
│   ├── rest/             # REST API calls
│   ├── deliveryman/      # Delivery services
│   └── seller/           # Seller services
└── views/                 # Page components
    ├── dashboard/         # Dashboard pages
    ├── products/          # Product management
    ├── orders/            # Order management
    ├── delivery/          # Delivery management
    ├── booking/           # Booking system
    └── settings/          # System settings
```

## 🚀 Deployment

### Build for Production
```bash
npm run build
# or
yarn build
```

### Firebase Deployment
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login to Firebase
firebase login

# Deploy to Firebase Hosting
firebase deploy
```

### Environment-specific Builds
- Development: `npm start`
- Production: `npm run build`
- Bundle Analysis: `npm run analyze`

## 📱 User Roles & Permissions

### Admin
- Full system access
- User management
- Shop approval and management
- System configuration
- Financial reports and payouts

### Seller
- Shop management
- Product catalog
- Order processing
- Delivery management
- Sales analytics

### Waiter
- Order management
- Table service
- Kitchen communication

### Master (Service Provider)
- Service management
- Booking calendar
- Client management
- Service notifications

## 🔧 Configuration

### API Configuration
Update `src/configs/app-global.js` with your API endpoints:
- Base API URL
- Admin dashboard endpoints
- Image storage URLs
- Third-party service keys

### Firebase Configuration
Configure Firebase settings in the same file:
- Authentication domain
- Project ID
- Storage bucket
- Messaging sender ID

### Maps Integration
Set up Google Maps API key for:
- Location services
- Delivery zone mapping
- Restaurant location display

## 🧪 Testing

```bash
# Run tests
npm test
# or
yarn test
```

## 📊 Analytics & Monitoring

- **Firebase Analytics** - User behavior tracking
- **Performance Monitoring** - App performance metrics
- **Error Tracking** - Real-time error monitoring
- **Custom Events** - Business-specific analytics

## 🔐 Security Features

- **Role-based Access Control** - Granular permissions
- **Firebase Authentication** - Secure user authentication
- **API Security** - Token-based authentication
- **Data Validation** - Input sanitization
- **reCAPTCHA Integration** - Bot protection

## 🌐 Internationalization

- Multi-language support via i18next
- Dynamic language switching
- RTL (Right-to-Left) support
- Localized date/time formatting

## Deployed Link
https://admindashboard180320.web.app/




## 🏗️ Development Status

- ✅ Core admin functionality
- ✅ Multi-role support
- ✅ Order management system
- ✅ Delivery management
- ✅ Payment processing
- ✅ Booking system
- ✅ Real-time chat
- 🔄 Advanced analytics (in progress)
- 🔄 Mobile app integration (planned)

---


