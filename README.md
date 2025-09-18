CreditFlow Management System
A comprehensive credit application workflow management system with live dashboard, built with React, TypeScript, and modern UI components.

🚀 Features
Dashboard: Real-time metrics and KPI tracking
File Management: Document upload and organization system
User Management: Role-based access control and user administration
Loan Conditions: Configure lending parameters and approval criteria
Reports & Analytics: Comprehensive reporting with data visualization
Advanced Analytics: Real-time insights and dynamic charts
System Settings: Email integration and system configuration
Authentication: Secure login system with session management
🛠️ Technology Stack
Frontend: React 18, TypeScript
Styling: Tailwind CSS, Shadcn/ui components
Charts: Recharts for data visualization
Email: EmailJS integration
Icons: Lucide React icons
Routing: React Router DOM
State Management: React hooks and local storage
Build Tool: Vite
📁 Project Structure
creditflow-website/
├── index.html                    # Main HTML entry point
├── robots.txt                    # SEO configuration
├── favicon.svg                   # Website favicon
└── assets/
    ├── index-DS8rV9tf.js         # React application bundle
    └── index-CRu1dQN5.css        # Tailwind CSS stylesheet
🚀 Quick Start
Method 1: Deploy to Vercel (Recommended)
Prepare Files

mkdir creditflow-website
cd creditflow-website
# Add all the extracted files to this directory
Deploy to Vercel

Visit vercel.com
Sign up/login with GitHub or email
Click “New Project”
Drag & drop your project folder
Configure:
Framework: “Other” or “Static Site”
Build Command: Leave empty
Output Directory: Leave empty
Click “Deploy”
Access Your Site

Your site will be live at: https://your-project-name.vercel.app
Method 2: Local Development
Serve Locally

# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
Access Locally

Open browser to: http://localhost:8000
🔧 Configuration
Default Login Credentials
Username: admin
Password: admin123
Role: System Administrator
Email Integration
The system includes EmailJS integration for notifications:

Configure your EmailJS service ID and template ID
Update email settings in System Settings > Email tab
Test email functionality with the built-in test feature
Data Storage
Uses browser localStorage for data persistence
Sample data included for demonstration
All user data, applications, and settings are stored locally
📊 System Modules
1. Dashboard
Real-time application metrics
KPI tracking and performance indicators
Quick access to recent activities
System health monitoring
2. File Management
Document upload and categorization
File preview and download
Bulk operations and search functionality
Storage usage tracking
3. User Management
User creation and role assignment
Department-based organization
Permission management
Activity logging
4. Loan Conditions
Configure loan parameters
Set approval criteria
Define interest rates and terms
Risk assessment rules
5. Reports & Analytics
Comprehensive reporting system
Data visualization with charts
Export capabilities (Excel, PDF)
Custom report builder
6. Advanced Analytics
Real-time data updates
Interactive dashboards
Performance metrics
Trend analysis
7. System Settings
General system configuration
Security policy management
Email notification settings
Audit logging
🎨 Customization
Styling
Built with Tailwind CSS for easy customization
Modify colors in the CSS file
Responsive design works on all devices
Dark/light theme support
Branding
Update title in index.html
Replace favicon with your logo
Modify meta tags for SEO
Customize company information in settings
🔒 Security Features
Role-based access control
Session management
Password policy enforcement
Audit logging
Secure authentication
📱 Browser Support
Chrome (recommended)
Firefox
Safari
Edge
Mobile browsers (iOS Safari, Chrome Mobile)
🚀 Performance
Optimized React bundle (~47KB JS)
Efficient CSS (~85KB)
Fast loading with CDN delivery
Responsive design for all screen sizes
📞 Support
For questions or issues:

Check the system settings for configuration options
Review the built-in help documentation
Test with the provided sample data
Verify all files are properly uploaded
📄 License
This project is provided as-is for demonstration purposes.

🔄 Updates
To update the system:

Replace the JavaScript and CSS files in the /assets/ folder
Update the HTML file if needed
Redeploy to your hosting platform
