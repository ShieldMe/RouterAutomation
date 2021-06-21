# ShieldMe Router Automation Changelog

# [Unreleased]

# [1.1.0] - 2021-06-21

### **This release contains breaking changes.**
### **Warning - Your data will be lost after installing the update!**

## **Added**

- New progress bar with dynamic messages
- New Progress indicator on taskbar
- New custom titlebar with custom style
- New update router details
- Enhanced security - signed assemblies
- Configuration defaults
- License and ReadMe are now packed together with the application
- Devices and workflows data refreshed automatically after loading home page (when user is logged in)
- Application database should persist through updates from this version onwards

## **Changed**

- Firmware flashing improved - take into account firmware regional restrictions
- Renamed "Detect Router Firmware" to "Refresh Router Details"
- Renamed and reorganized all wizard steps
- Optimized Backend to Frontend events integration
- Optimized Frontend to Backend events integration
- Optimized timeout on https client calls
- Changed application database initialization and connection
- Changed Adding or Updating a router behavior: 
  - Automatically detect its status (Online or Offline)
  - Automatically detect currently installed firmware
- Opening ShieldMe website resources will automatically authenticate the user with their account used to login
- Changed splashscreen
- Changed homepage style
- Changed general error page background
- Changed loading backdrop style

## **Removed**
- Default window titlebar and style

# [1.0.0] - 2021-06-12
## **Added**

### User Interface

- **Header**
  - Unauthenticated header
  - Authenticated header

- **Footer**
  - Unauthenticated header
  - Authenticated header

- **Layouts**
  - Unauthenticated layout
  - Authenticated layout

- **Sidebar**
  - Logo
  - User Display Name shortcut
  - Home
  - My Account
  - Routers
    - Add Router
    - My Routers
  - Automations
    - Run Automation
    - Automations History

- **Login**
  - ShieldMe account login form

- **Home** - Widgets:
  - My Routers
    - New Router link
    - Refresh
  - Last Automation
    - New Automation link
    - Refresh
  - Subscription Status
    - Modify Subscription link
    - Refresh
  - App Version
    - Check for updates link
    - Release Notes link

- **Home** - Panels:
  - Automations
    - Firmware
    - ShieldMe
  - Routers
    - Management
    - Settings

- **My Account** - Profile Details
  - Display Name
  - Account Username
  - Account Email

- **My Account** - Top Right Widget
  - Account Type
  - Registered Since
  - Links
    - Blog
    - F.A.Q.
    - Help Center
    - Contact Us

- **My Account** - Resources
  - Preferences Links
    - Update Profile
    - Emailing Preferences
    - Account Security
  - Billing
    - Subscription Details
    - Order Details
    - Payment Details
  - Service
    - Health Status
    - What is my ip ?
    - License Details

- **Add Router** - Wizard steps
  - General
  - Device
  - Settings

- **My Routers**
  - Router Details Table
  - Detect Firmware
  - Device Details
  - Remove Device

- **Run Automation** - Wizard steps
  - Disclaimer
  - Target
  - Workflow

- **Automations History**
  - Automations Details Table
  - Re-run Automation
  - View Steps Execution
  - View Steps Details
  - Remove Log

### API

- **Application Endpoint**
- **Authentication Endpoint**
- **Automation Endpoint**
- **Device Endpoint**
- **Router Endpoint**
- **Workflow Endpoint**

## **Changed**
- N/A

## **Removed**
- N/A

