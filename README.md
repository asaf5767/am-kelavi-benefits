# מרכז מידע, סיוע והטבות | Support Services Information Center

A comprehensive web application providing information about support services, benefits, and assistance programs in Israel. The application features AI-powered search capabilities and an intuitive interface designed for Hebrew speakers.

## 🌟 Features

### 🔍 AI-Powered Search
- **Gemini API Integration**: Intelligent search that understands user descriptions and maps them to relevant service categories
- **Natural Language Processing**: Users can describe their situation in Hebrew and get personalized service recommendations

### 📱 Responsive Design
- **Mobile-First**: Optimized for all device sizes
- **RTL Support**: Full right-to-left layout support for Hebrew text
- **Modern UI**: Clean, accessible design using Tailwind CSS

### 📊 Data Visualization
- **Interactive Charts**: Visual representation of service distribution using Chart.js
- **Category Overview**: Easy-to-understand breakdown of available services

### 🎯 Smart Filtering
- **Category-Based Navigation**: Browse services by categories like mental health support, business assistance, etc.
- **Interactive Cards**: Click-through interface from categories to detailed service information

### ✨ AI-Assisted Communication
- **Inquiry Drafting**: AI-powered feature to help users draft formal inquiries to service organizations
- **Template Generation**: Personalized communication templates with proper formatting

## 🗂️ Service Categories

- **תמיכה נפשית** (Mental Health Support)
- **בעלי עסקים** (Business Owners)
- **ילדים ונוער** (Children & Youth)
- **מפונים ומתפנים** (Evacuees)
- **הטבות** (Benefits)
- **מילואימניקים** (Reservists)
- **חקלאות** (Agriculture)
- **אישורים וטפסים** (Documents & Forms)
- **התנדבות** (Volunteering)
- **תיירות** (Tourism)
- **אנשים פרטיים** (Private Individuals)
- **כללי** (General)

## 🚀 Quick Start

### Prerequisites
- A modern web browser
- Optional: Gemini API key for AI features

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/asaf5767/am-kelavi-benefits.git
cd am-kelavi-benefits
```

2. Open `am-kelavi.html` in your browser
3. The application works as a single-page application (SPA) with no build process required

### Adding Gemini API Key
To enable AI features, add your Gemini API key in the `callGemini` function:
```javascript
const apiKey = "YOUR_GEMINI_API_KEY_HERE";
```

## 🌐 Deployment

### Vercel (Recommended)
1. Fork or import this repository to your GitHub account
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click "New Project"
4. Import your GitHub repository
5. Deploy with default settings

### Other Platforms
This is a static HTML application that can be deployed on:
- Netlify
- GitHub Pages
- Firebase Hosting
- Any static hosting service

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Charts**: Chart.js
- **AI Integration**: Google Gemini API
- **Fonts**: Google Fonts (Rubik)

## 📊 Data Structure

The application uses a JavaScript array of service objects with the following structure:
```javascript
{
  "id": 1,
  "category": "Service Category",
  "org": "Organization Name",
  "details": "Detailed description of services",
  "phone": "Contact phone number",
  "link": "Website URL",
  "date": "Last updated date"
}
```

## 🎨 Design Philosophy

### Color Palette: "Calm Neutrals"
- **Primary**: Teal (#14b8a6) for trust and clarity
- **Background**: Warm slate tones for comfort
- **Accent**: Supportive teal for calls-to-action

### User Experience
- **Task-Oriented Flow**: Find → Filter → Focus → Act
- **Cognitive Load Reduction**: Simple, step-by-step navigation
- **Accessibility**: High contrast, readable fonts, clear navigation

## 🔧 Customization

### Adding New Services
Edit the `db` array in the JavaScript section to add new services:
```javascript
const db = [
  // Add new service object here
  {
    "id": 15,
    "category": "New Category",
    "org": "Organization Name",
    "details": "Service description",
    "phone": "Phone number",
    "link": "Website URL",
    "date": "DD/MM/YYYY"
  }
];
```

### Modifying Categories
Update the `categoryIcons` object to add icons for new categories:
```javascript
const categoryIcons = {
  "New Category": "🆕"
};
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Credits

- **Data Source**: מורן תסדר (Moran Tesder)
- **Development**: אסף עקיבא (Assaf Akiva)
- **Facebook Group**: [מורן תסדר](https://www.facebook.com/groups/morantsader/)

## 📞 Contact

- **Developer**: [Assaf Akiva](https://www.linkedin.com/in/assafakiva)
- **Data Source Contact**: [WhatsApp](https://wa.me/972524244298)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

---

**🇮🇱 Made with ❤️ for the Israeli community** 