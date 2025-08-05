# Revathie Gear Products - Advanced Invoice Generator

A professional, highly animated invoice generation system with a mechanical/gear-themed design, built specifically for Revathie Gear Products.

## Features

### 🎨 Advanced UI/UX
- **Animated Background**: Dynamic gear animations and floating particles
- **Dark Theme**: Modern dark interface with blue and amber accents
- **Smooth Transitions**: All interactions feature smooth animations
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices

### ⚙️ Core Functionality
- **Client Information Management**: Store client details including GST information
- **Dynamic Item Management**: Add/remove multiple items with automatic calculations
- **Transport Charges**: Optional transport charge addition
- **Tax Calculations**: Supports CGST/SGST and IGST with configurable rates
- **Live Preview**: Real-time invoice preview as you type
- **PDF Generation**: Generate professional PDF invoices via webhook integration

### 🚀 Special Features
- **Sample Data Loading**: Quick demo data for testing
- **Connection Testing**: Built-in webhook connection tester
- **Number to Words**: Automatic conversion of amounts to Indian numbering system
- **Labour Charges Text**: Customizable labour charges description
- **Inter-state Supply**: Toggle between CGST/SGST and IGST

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/revathie-gear-invoice.git
   ```

2. Navigate to the project directory:
   ```bash
   cd revathie-gear-invoice
   ```

3. Open `index.html` in your web browser

## Usage

1. **Fill Client Information**
   - Enter client name, address, and GST number
   
2. **Add Invoice Details**
   - Invoice number and date
   - DC number and date (optional)
   - Despatch and document methods

3. **Add Items/Services**
   - Click "+ Add New Item" to add items
   - Enter item name, service description, quantity, and rate
   - Amount is calculated automatically

4. **Configure Tax and Charges**
   - Select tax rate (12%, 18%, or 28%)
   - Add transport charges if needed
   - Toggle inter-state supply for IGST

5. **Generate Invoice**
   - Click "Generate Invoice" to create PDF
   - Invoice opens in new window for printing/saving

## Webhook Configuration

The system uses a webhook URL for PDF generation:
```javascript
const WEBHOOK_URL = 'https://sngsng.app.n8n.cloud/webhook/invoice-generator-v3';
```

To use your own webhook, update this URL in the JavaScript section.

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Advanced animations, gradients, and modern styling
- **JavaScript**: Dynamic functionality and calculations
- **SVG**: Gear graphics
- **Webhook Integration**: For PDF generation

## Browser Support

- Chrome (recommended)
- Safari
- Firefox
- Edge

## License

This project is built for Revathie Gear Products. All rights reserved.

## Support

For issues or questions, please contact Revathie Gear Products support team.
