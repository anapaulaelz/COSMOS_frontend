# 🌌 COSMOS - Inventory Management System

COSMOS is a sophisticated frontend application designed for inventory management and business intelligence. Built with a cosmic space theme, it provides a comprehensive suite of tools for managing inventory, forecasting demand, tracking fulfillment, and monitoring business operations.

## 🚀 Live Demo

**🌐 [View Live Application](https://anapaulaelz.github.io/COSMOS_frontend)**

Experience COSMOS directly in your browser! No installation required.
- **Username**: `admin`
- **Password**: `admin123`

## 🚀 Project Overview

This is a modern, responsive web application that combines inventory management with an immersive space-themed user interface. The application features a unified navigation system and modular architecture that makes it easy to extend and maintain.

## 📁 Project Structure

```
COSMOS_frontend/
├── docs/                            # GitHub Pages source (web-ready)
│   ├── index.html                   # Login page (main entry point)
│   ├── css/                         # Stylesheets (6 files)
│   │   ├── styles.css              # Global styles and base theme
│   │   ├── cosmic-sidebar.css      # Navigation sidebar styles
│   │   ├── login.css              # Login page specific styles
│   │   ├── demand-forecasting.css # Demand forecasting page styles
│   │   ├── fulfillment.css        # Fulfillment page styles
│   │   └── smart-inventory.css    # Smart inventory page styles
│   ├── js/                         # JavaScript modules (6 files)
│   │   ├── cosmic-sidebar.js      # Navigation and sidebar functionality
│   │   ├── main.js                # Core application logic
│   │   ├── login.js               # Login page functionality
│   │   ├── demand-forecasting.js  # Demand forecasting features
│   │   ├── fulfillment.js         # Fulfillment page logic
│   │   └── smart-inventory.js     # Smart inventory management
│   ├── pages/                      # Application pages (9 files)
│   │   ├── dashboard.html          # Main dashboard with metrics
│   │   ├── demand-forecasting.html # Demand prediction and analytics
│   │   ├── smart-inventory.html    # Inventory management interface
│   │   ├── fulfillment.html        # Order fulfillment tracking
│   │   ├── alarms-alerts.html      # System alerts and notifications
│   │   ├── todo-board.html         # Task management board
│   │   ├── calendar.html           # Calendar and scheduling
│   │   ├── partners.html           # Partner management
│   │   └── document-base.html      # Document repository
│   └── data/                       # Real datasets for frontend (7 files)
│       ├── Total_sales_per_product.csv     # Sales data by product
│       ├── conversion_rate.csv             # Conversion and session data
│       ├── full_forecast_with_history.csv  # Forecasting data
│       ├── inventory_dashboard_data.json   # Inventory metrics and alerts
│       ├── inventory_summary.csv           # Inventory summary
│       ├── fulfillment_data.csv           # Shipping zones and times
│       └── partners.csv                   # Business partners data
├── .github/workflows/              # GitHub Actions for auto-deployment
├── .gitignore                      # Git ignore patterns
├── package.json                    # Project configuration
├── README.md                       # This documentation
└── GITHUB_PAGES_SETUP.md          # GitHub Pages setup guide
```

## 🌟 Features & Pages

### 🔐 Authentication
- **Login Page** (`index.html`): Cosmic-themed login interface with animated background
- Default credentials: `admin` / `admin123`

### 📊 Core Business Functions

#### 1. **Dashboard** (`dashboard.html`)
- Central command center with key performance indicators
- Real-time metrics and data visualization
- Integration with CSV data parsing (Papa Parse)
- Responsive grid layout for widgets

#### 2. **Demand Forecasting** (`demand-forecasting.html`)
- Advanced forecasting algorithms and visualization
- Chart.js integration for data visualization
- Historical data analysis and trend prediction
- Interactive charts with date-fns adapter

#### 3. **Smart Inventory** (`smart-inventory.html`)
- Intelligent inventory management system
- Real-time stock level monitoring
- Automated reorder point calculations
- Interactive inventory visualizations

#### 4. **Fulfillment** (`fulfillment.html`)
- Order processing and tracking system
- Shipment status monitoring
- FontAwesome icons for enhanced UX
- Real-time fulfillment metrics

### 🔧 Operational Tools

#### 5. **Alarms & Alerts** (`alarms-alerts.html`)
- System notification center
- Critical event monitoring
- Alert management and acknowledgment

#### 6. **To Do Board** (`todo-board.html`)
- Task management and organization
- Project tracking capabilities
- Team collaboration features

#### 7. **Calendar** (`calendar.html`)
- Event scheduling and management
- Integration with business operations
- Timeline visualization

#### 8. **Partners** (`partners.html`)
- Business partner information management
- Supplier and vendor tracking
- Partnership analytics

#### 9. **Document Base** (`document-base.html`)
- Centralized document repository
- File management and organization
- Document sharing capabilities

## 🎨 Design System

### Theme
- **Primary Color Scheme**: Deep space blues and cosmic purples
- **Typography**: Inter and Space Grotesk fonts
- **Animation**: Smooth cosmic transitions and particle effects
- **Layout**: Responsive grid system with cosmic sidebar navigation

### Key Design Elements
- Animated star field backgrounds
- Cosmic particle effects
- Gradient overlays and glows
- Space-themed iconography (FontAwesome)
- Responsive sidebar navigation

## 🛠 Technical Architecture

### Frontend Technologies
- **HTML5**: Semantic markup with modern standards
- **CSS3**: Advanced styling with custom properties and animations
- **Vanilla JavaScript**: Modern ES6+ features for interactivity
- **Chart.js**: Data visualization and charting
- **Papa Parse**: CSV data processing
- **FontAwesome**: Icon library for enhanced UX

### External Dependencies
- Chart.js (CDN)
- Papa Parse (CDN)
- Date-fns (CDN)
- FontAwesome (CDN)
- Google Fonts (Inter & Space Grotesk)

### Architecture Patterns
- **Modular CSS**: Separate stylesheets for each major component
- **Component-based JS**: Dedicated scripts for specific functionality
- **Unified Navigation**: Centralized sidebar system across all pages
- **Responsive Design**: Mobile-first approach with breakpoints

## 🚀 Setup Instructions

### 🌐 Quick Start (Recommended)
**Simply visit the live application**: [https://anapaulaelz.github.io/COSMOS_frontend](https://anapaulaelz.github.io/COSMOS_frontend)

No installation needed! The application is hosted on GitHub Pages and ready to use.

### 🛠️ Local Development

#### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (for local development server)

#### Installation
1. **Download/Clone the project**:
   ```bash
   git clone https://github.com/anapaulaelz/COSMOS_frontend.git
   cd COSMOS_frontend
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start development server**:
   ```bash
   npm start
   ```
   This will serve the application from the `docs` folder on `http://localhost:8080`

4. **Alternative: Serve manually**:
   ```bash
   # Using Python
   cd docs && python -m http.server 8000
   
   # Using Node.js
   cd docs && npx serve .
   
   # Using PHP
   cd docs && php -S localhost:8000
   ```

5. **Access the application**:
   - Navigate to `http://localhost:8080` (or respective port)
   - Login with: `admin` / `admin123`

## 🔧 Configuration

### Data Integration
The application is designed to work with CSV data files located in the `../data/` directory:
- `combined_final.csv`
- `conversion_rate.csv`
- `fulfillment_data.csv`
- `inventory_summary.csv`
- `partners.csv`
- And more...

### Customization
- **Styling**: Modify CSS custom properties in `src/css/styles.css`
- **Navigation**: Update menu items in `src/js/cosmic-sidebar.js`
- **Branding**: Change logos and colors in the CSS files
- **Functionality**: Extend features by modifying respective JS modules

## 🌐 Browser Compatibility

- **Chrome**: 80+
- **Firefox**: 75+
- **Safari**: 13+
- **Edge**: 80+

## 📱 Responsive Design

The application is fully responsive with breakpoints:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

## 🔒 Security Considerations

- Client-side authentication (demo purposes)
- No sensitive data storage in localStorage
- CSP-friendly external resource loading
- XSS protection through proper data handling

## 🚀 Performance Features

- Lazy loading of non-critical resources
- Optimized CSS with minimal external dependencies
- Efficient JavaScript modules
- Compressed external libraries via CDN

## 📈 Future Enhancements

- Real-time data synchronization
- Advanced user authentication
- Mobile app companion
- API integration for backend services
- Advanced analytics and reporting

## 📞 Support

For questions, issues, or contributions, please refer to the project documentation or contact the development team.

---

**COSMOS** - Navigate the Universe of Inventory Management 🌌