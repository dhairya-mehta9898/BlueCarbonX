# Carbon Credit Verifier

A modern React application for carbon credit project verification with approve, reject, and request clarification functionality.

## Features

- **Document Review**: Approve, reject, or request clarification for environmental projects
- **Status Tracker**: Monitor document status changes with timeline view
- **Projects Management**: View all assigned tree/carbon credit projects with filtering
- **Certificate Downloads**: Generate and download completion certificates for approved projects
- **Modern UI**: Clean white background with blue hover effects and professional typography

## Project Types

All projects are focused on environmental sustainability:

- **Amazon Rainforest Reforestation** - 2,500 tons CO₂
- **Urban Tree Planting Initiative** - 800 tons CO₂  
- **Mangrove Restoration Project** - 1,800 tons CO₂
- **Forest Fire Prevention System** - 3,200 tons CO₂
- **Agroforestry Implementation** - 1,200 tons CO₂
- **Bamboo Forest Development** - 1,500 tons CO₂
- **Community Tree Nursery Program** - 600 tons CO₂
- **Carbon Credit Verification System** - 0 tons CO₂

## Design Features

- **Clean White Background**: Professional, minimal design
- **Blue Hover Effects**: Consistent blue (#1976D2) hover states on all interactive elements
- **Modern Typography**: Inter font with bold headlines and clean body text
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Glassmorphism Elements**: Subtle transparency and blur effects

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Usage

### Document Review
1. Navigate to "Document Review" tab
2. Review the sample forest restoration project
3. Use action buttons to Approve, Reject, or Request Clarification
4. View status updates in real-time

### Status Tracker
1. Click "Status Tracker" tab
2. Filter documents by status (All, Pending, Approved, Rejected, Clarification)
3. Click any document card to view detailed status history
4. See timeline progression from Pending → Approved/Rejected

### Projects Management
1. Click "Projects" tab
2. Filter by tabs: All Projects, My Projects, Team Projects
3. Use category, priority, and status filters
4. Sort by due date, name, progress, or priority
5. View project statistics and carbon credits
6. Download certificates for completed projects

## Components

- `App.js`: Main application with navigation and page routing
- `Navigation.js`: Top navigation with three main sections
- `ActionButtons.js`: Approve/Reject/Clarification buttons with blue hover effects
- `StatusDisplay.js`: Status indicators with modern styling
- `StatusTracker.js`: Document status monitoring with timeline view
- `ProjectsList.js`: Project management with filtering and certificate downloads

## Technology Stack

- **React 18**: Modern React with hooks
- **CSS3**: Custom styling with modern features
- **Google Fonts**: Inter font family for professional typography
- **Responsive Design**: Mobile-first approach

## Color Scheme

- **Primary**: Forest Green (#2C5530)
- **Secondary**: Light Green (#4A6741)
- **Accent**: Blue (#1976D2) for hover effects
- **Background**: Clean White (#FFFFFF)
- **Text**: Dark Green (#2C5530) for headings, Light Green (#4A6741) for body

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Development

This project was created with Create React App and includes:
- React 18 with modern hooks
- Responsive CSS with flexbox and grid
- Professional typography and spacing
- Accessibility considerations
- Modern web standards

