# WK Automotive Website

Premium automotive service center website for WK Automotive, located at 70 Nebo Road, Unit 4, Hamilton, Ontario.

## 🚗 Features

- **Tesla-Inspired Design** - Clean, minimalist aesthetic with premium typography
- **Premium Fonts** - Montserrat and Bebas Neue for automotive industry feel
- **Responsive Contact Form** - Integrated with FormSubmit for instant email notifications
- **Scroll Animations** - Smooth fade-in effects and interactive elements
- **Glassmorphism UI** - Modern comparison table with backdrop blur
- **SEO Optimized** - Complete JSON-LD structured data for local search
- **Mobile Responsive** - Fully optimized for all devices

## 🎨 Design

- **Color Palette**: Light gray background (#F9FAFB), Gold accents (#D4AF37), Slate text
- **Typography**: Montserrat (body), Bebas Neue (display)
- **Framework**: Tailwind CSS via CDN
- **Icons**: Custom SVG icons

## 📧 Contact Form

The contact form uses FormSubmit.co to send inquiries directly to email. Configuration:
- Recipient: Configured via FormSubmit hash
- Fields: Name, Email, Phone, Service Type, Message
- Success redirect with notification banner

## 🚀 Deployment

### Local Development
```bash
python3 -m http.server 8080
```
Then visit: http://localhost:8080

### Production
1. Upload `index.html` to your web server
2. Update the `_next` redirect URL in the form to your production domain
3. Ensure your domain has HTTPS enabled

## 📁 Project Structure

```
WK/
├── index.html          # Single-file website (HTML + CSS + JS)
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## 🛠️ Technologies

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- FormSubmit.co (Email service)
- Google Fonts (Montserrat, Bebas Neue)

## 📝 Services Offered

- General Repair (Brakes, Suspension, Engine, Transmission)
- Performance Tuning (ECU, Suspension Upgrades, Dyno Testing)
- Maintenance (Oil Changes, Fluid Services, Inspections)
- Diagnostics (OBD-II Scanning, Electrical Repair)

## 📍 Location

**WK Automotive**  
70 Nebo Road, Unit 4  
Hamilton, ON L8W 2E3

**Hours:**
- Monday - Friday: 8:00 AM - 6:00 PM
- Saturday: By Appointment
- Sunday: Closed

## 📞 Contact

- Phone: (905) 555-0123
- Email: service@wkautomotive.ca

---

Built with ❤️ for premium automotive service excellence.
