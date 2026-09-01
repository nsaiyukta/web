# 🌍 Wanderly — Travel Website

A modern, responsive travel website built using **HTML, CSS, and JavaScript**. Wanderly helps users discover beautiful destinations, explore travel packages, and submit trip booking requests through a clean and interactive interface.

## ✨ Features

* 🏠 Modern hero/landing section
* 🌎 Popular destination cards
* 🔎 Destination search functionality
* 📅 Travel date selection
* 👥 Traveler selection
* ✈️ Popular travel packages
* ⭐ Customer testimonials
* 📝 Trip booking modal
* 📩 Newsletter subscription
* 📱 Fully responsive design
* 🍔 Mobile navigation menu
* ✨ Smooth scrolling and hover animations
* 🖼️ High-quality destination images

## 🛠️ Technologies Used

* **HTML5** — Website structure
* **CSS3** — Styling, animations, and responsive layout
* **JavaScript** — Interactivity and functionality
* **Google Fonts** — Poppins typography
* **Unsplash** — Travel images

## 📁 Project Structure

```text
wanderly/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 Getting Started

### 1. Clone or download the project

Download the project files or clone the repository:

```bash
git clone https://github.com/your-username/wanderly.git
```

### 2. Open the project

Navigate to the project folder:

```bash
cd wanderly
```

### 3. Run the website

Open `index.html` directly in your browser.

Alternatively, use **VS Code Live Server** for a better development experience.

## 🔎 How It Works

### Destination Search

Users can enter a destination such as:

```text
Bali
Paris
Dubai
Santorini
```

The JavaScript search functionality filters the destination cards and displays matching results.

### Booking

Clicking **Book Trip** opens a booking modal where users can enter:

* Full name
* Email address
* Number of travelers
* Travel date

The current version displays a confirmation message after submission.

> **Note:** The booking form is currently frontend-only. It does not send booking information to a real backend or database.

### Newsletter

Users can enter their email address in the newsletter section and receive a frontend confirmation message.

## 🎨 Customization

### Change Website Name

Open `index.html` and replace:

```html
Wander<span>ly</span>
```

with your preferred brand name.

### Change Colors

The primary orange color is used throughout the stylesheet:

```css
#ff7043
```

You can replace it with your own brand color.

### Add Destinations

Add another destination card inside the `.destination-grid`:

```html
<div class="destination-card" data-name="Tokyo">
    <img src="YOUR_IMAGE_URL" alt="Tokyo">

    <div class="card-content">
        <span>Japan</span>
        <h3>Tokyo</h3>
        <p>From $899</p>
    </div>
</div>
```

### Add Travel Packages

Copy an existing `.package-card` and update:

* Destination name
* Image
* Description
* Rating
* Price
* Package category

## 📱 Responsive Design

Wanderly is designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Tablet
* 📱 Mobile

CSS media queries automatically adjust the layout for smaller screens.

## 🔮 Future Improvements

Possible improvements include:

* 🔐 User authentication
* 💳 Online payments
* 🗄️ Backend booking system
* 📧 Email booking confirmations
* 🗺️ Interactive maps
* 🔥 Real-time travel deals
* ❤️ Wishlist/favorites
* 🔍 Advanced destination filters
* 🌐 Multi-language support
* 🌙 Dark mode
* 📊 Admin dashboard
* ☁️ Database integration

## ⚠️ Disclaimer

This project is a frontend demonstration. Destination images are loaded from Unsplash, and booking/newsletter forms currently simulate successful submissions without storing or transmitting user data.

## 📄 License

This project is available for educational and personal use.

Feel free to modify, improve, and customize it for your own projects.

---

### 🌴 Explore. Dream. Discover.

**Wanderly — Your next adventure starts here.**
