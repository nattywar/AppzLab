# 🚨 FDNY EMS Staffing Report System

**Official EMS Staffing Management Application**  
*Fire Department City of New York*

---

## Overview

A comprehensive, single-page web application designed for the FDNY Emergency Medical Services to manage employee schedules, track absences, and generate staffing reports. Features authentic FDNY branding with official colors and professional design.

## Features

### 📋 Core Functionality
- **Employee Roster Management** - Add, edit, and manage EMS personnel
- **CSV Import/Export** - Bulk data operations
- **Drag & Drop Scheduling** - Intuitive absence management
- **Platoon Rotation System** - Automatic working platoon calculation
- **Tour Management** - Tour 1, 2, and 3 scheduling
- **Function-Based Organization** - Group by role/position
- **Real-Time Clock** - 24/7 operational display

### 📅 Advanced Features
- **Interactive Calendar View** - Visual platoon scheduling
- **Schedule View** - Week/month employee schedules
- **Absence Tracking** - Sick, vacation, medical, IOD, etc.
- **Overtime Management** - Track TC, mutual swaps, overtime
- **Daily Summary Reports** - Real-time staffing counts
- **Working Filter** - Show only on-duty personnel
- **Search Functionality** - Quick employee/shield lookup

### 🎨 FDNY Branding
- **Official Colors** - FDNY Red (#C8102E), Navy Blue (#003478), Gold (#FFB81C)
- **Professional Typography** - Emergency services standard fonts
- **Dark Mode Support** - 24/7 shift work optimization
- **Print-Optimized Exports** - Dense, professional layouts
- **FDNY Identity** - Motto, agency branding throughout

### 💾 Data Management
- **LocalStorage Persistence** - Data saved in browser
- **Export to HTML** - Generate printable reports
- **CSV Parsing** - Import employee rosters
- **Backup/Restore** - Admin data management

## Technical Specifications

- **Type:** Single-page application (SPA)
- **Technologies:** HTML5, CSS3, Vanilla JavaScript
- **Dependencies:** None (self-contained)
- **Storage:** Browser LocalStorage
- **Browser Support:** Chrome 90+, Edge 90+, Firefox 88+, Safari 14+
- **File Size:** ~280KB (single HTML file)

## Installation

### Option 1: Direct Use
1. Download `WOW.html`
2. Open in a modern web browser
3. Start using immediately (no installation required)

### Option 2: Web Server
1. Place `WOW.html` on any web server
2. Access via URL
3. Works with any HTTP/HTTPS server

## Usage

### Initial Setup
1. Open the application
2. Click **⚙️ Admin** (Settings)
3. Import employee roster via CSV or add manually
4. Configure platoon rotation dates if needed

### Daily Operations
1. View current date's working platoons
2. Filter by tour/function as needed
3. Drag employees to absence categories
4. Use "Working Filter Date Only" to see on-duty staff
5. Export reports as needed

### Scheduling
1. Click **📋 Schedule** button
2. Toggle between Week/Month view
3. Add absences to future dates
4. Export schedules for distribution

### Calendar
1. Click **📅 Calendar** button
2. View platoon rotation schedules
3. See working platoons by date

## Color Coding

| Color | Meaning |
|-------|---------|
| 🔴 **FDNY Red** | Primary actions, alerts, absences |
| 🔷 **Navy Blue** | Official headers, secondary elements |
| 🟡 **FDNY Gold** | Warnings, important notices, summaries |
| 🟢 **Green** | Working shifts, available personnel |
| ⚪ **Gray** | Off-duty, inactive |

## Data Structure

### Employee Fields
- First Name, Last Name
- Shield Number
- Tour (1, 2, 3)
- Function (Lieutenant, EMT, Paramedic, etc.)
- Platoon (A, B, C, D, E, F)
- Start Time (military format)
- Active Status

### Absence Categories
- Sick, Vacation, Medical Leave
- IOD (Injured on Duty)
- FMLA, AWOL, Suspension
- Overtime, TC (Trade Coverage), Mutual, Switch
- Custom categories

## Security & Privacy

- **Data Storage:** All data stored locally in browser
- **No Cloud Sync:** No external data transmission
- **Private Use:** Designed for internal FDNY use
- **Access Control:** Recommend password-protected hosting for production

## Support & Maintenance

- **Updates:** Self-contained file, easy to replace
- **Backup:** Use Admin panel to export/import data
- **Troubleshooting:** Check browser console for errors
- **Clear Data:** Use browser developer tools if needed

## FDNY Branding

This application features official FDNY visual identity:
- **Established:** 1865
- **Motto:** "New York's Bravest"
- **EMS Motto:** "New York's Best"
- **Colors:** Official FDNY Red, Navy Blue, and Gold
- **Typography:** Professional emergency services standards

## Version Information

- **Version:** 2.0 (FDNY Branded)
- **Last Updated:** October 2025
- **Status:** Production Ready
- **License:** Private/Internal Use

---

## Quick Start Guide

1. **Open** `WOW.html` in your browser
2. **Import** your employee roster (CSV or manual entry)
3. **Filter** by tour/function to view specific groups
4. **Manage** absences by dragging employees to categories
5. **Export** reports for distribution
6. **Schedule** future absences using Schedule View

---

**For the Bravest. By the Bravest.** 🚨

*Fire Department City of New York*  
*Emergency Medical Services*
