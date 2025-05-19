# Gata Garota Beauty Salon - A Professional Beauty Services Website

This project is a responsive website for Gata Garota Beauty Salon, providing an intuitive interface for customers to explore services, view before/after galleries, and book appointments. The website offers a comprehensive digital presence for the salon, featuring service listings, pricing information, and an easy-to-use appointment scheduling system.

The website is built using pure HTML and CSS, making it lightweight and fast-loading. It features a consistent pink-themed design that reflects the salon's brand identity and includes essential features like service catalogs, pricing tables, before/after galleries, and a contact form for appointments. The modular structure allows for easy maintenance and updates of service offerings and pricing.

## Repository Structure
```
.
├── index.html          # Homepage with main navigation and welcome message
├── servicos.html      # Detailed list of salon services
├── produtos.html      # Product and service pricing catalog
├── agendamento.html   # Appointment booking form
├── sobre.html         # About page with salon information and location
└── fotos.html         # Before/after photo gallery
```

## Usage Instructions
### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, or Edge)
- Basic web server for local development
- Text editor for HTML/CSS

### Installation
1. Clone the repository:
```bash
git clone [repository-url]
```

2. Set up a local development server:
- Using Python:
```bash
# Python 3
python -m http.server 8000
# Python 2
python -m SimpleHTTPServer 8000
```
- Using Node.js:
```bash
npx http-server
```

### Quick Start
1. Open `index.html` in your web browser to access the homepage
2. Navigate through the site using the top navigation menu
3. View services and pricing in the `produtos.html` page
4. Make appointments through the `agendamento.html` form

### More Detailed Examples
1. Viewing Service Prices:
- Navigate to `produtos.html`
- Browse the comprehensive pricing table
- Services range from R$ 30,00 to R$ 400,00

2. Booking an Appointment:
- Go to `agendamento.html`
- Fill out the appointment form with:
  - Name
  - Desired service
  - Preferred date

### Troubleshooting
Common Issues:
1. Images not loading
- Verify that image paths in HTML files are correct
- Check if images are present in the `imagens.html` directory
- Ensure proper file permissions

2. Form submission issues
- Confirm that the form action URL is properly configured
- Verify all required fields are filled out
- Check browser console for JavaScript errors

## Data Flow
The website follows a simple static content delivery model where users navigate through HTML pages to access information and submit appointment requests.

```ascii
User Request -> Static HTML Pages -> Form Submission
     ↑               ↓
     └──── Navigation Menu ────┘
```

Component Interactions:
1. Navigation menu provides links between all pages
2. Product page displays service pricing in a structured table
3. Appointment form collects user input for booking requests
4. Gallery page displays before/after images in a grid layout
5. About page provides salon information and contact details
6. Services page lists available treatments and procedures