# DAWOOD AB COLLECTION - Ledger Management System

A simple HTML-based ledger management system for DAWOOD AB COLLECTION, a fabric store in Pakistan.

## Features

### 🏠 Main Landing Page
- Beautiful, modern design with gradient background
- Navigation to owner login page
- Information about store services

### 👑 Owner Features
- **Secure Login**: Password-protected access (Password: `abdullah123`)
- **Dashboard**: Overview of all customers and transactions
- **Customer Management**: View all customer ledgers
- **Search Functionality**: Search customers by name or phone number
- **Statistics**: Total customers, outstanding balance, and transaction count
- **Export to JPG**: Save complete ledger report as JPG image file
- **Add Customers**: Add new customers with initial balance
- **Delete Customers**: Remove customers with confirmation dialog
- **Quick Actions**: Add payments and purchases directly from customer ledger view

## How to Use

### For Owner
1. Open `index.html` in your web browser
2. Click "Owner Login" or navigate to `owner-login.html`
3. Enter the password: `abdullah123`
4. Access the owner dashboard to manage all customer ledgers
5. Use "Add Customer" button to add new customers
6. Use "Delete" button to remove customers (with confirmation)
7. View individual customer ledgers and use "Add Payment" or "Add Purchase" buttons

## Sample Customer Data

For testing purposes, the following customer phone numbers are available:

| Phone Number | Customer Name | Current Balance |
|--------------|---------------|-----------------|
| 03001234567  | Ahmed Khan    | PKR 15,000     |
| 03009876543  | Fatima Ali    | PKR 2,500      |
| 03005556677  | Muhammad Hassan | PKR 7,500   |

## File Structure

```
ledger/
├── index.html              # Main landing page
├── customer-ledger.html    # Customer ledger view
├── owner-login.html        # Owner login page
├── owner-dashboard.html    # Owner dashboard
└── README.md              # This file
```

## Technical Details

- **Frontend Only**: Pure HTML, CSS, and JavaScript
- **No Backend**: Data is stored in browser session storage
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, professional design with gradients and animations

## Security Notes

⚠️ **Important**: This is a demo application with client-side data storage. In a production environment:

- Implement proper server-side authentication
- Use secure database storage
- Add HTTPS encryption
- Implement proper session management
- Add input validation and sanitization

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Getting Started

1. Download all files to a folder
2. Open `index.html` in your web browser
3. Start using the ledger system!

## Export Features

### 📸 JPG Export
- **Owner Dashboard**: Click "Save as JPG" to export complete ledger report
- **Customer Ledger**: Click "Save as JPG" to export personal ledger
- **High Quality**: Professional layout with store branding
- **Automatic Naming**: Files include date and customer name
- **Color Coded**: Balances and transaction types are color-coded

## Future Enhancements

- Add new customer registration
- Implement transaction management (add/edit/delete)
- Export ledger data to PDF
- Email notifications
- Mobile app version
- Database integration
- Multi-branch support

---

**DAWOOD AB COLLECTION** - Premium Unstitched Fabric Store in Pakistan 