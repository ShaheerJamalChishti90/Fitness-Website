# Gym Website 🏋️‍♂️

A modern, responsive static gym website built with HTML, CSS, and Flask. This website showcases a professional fitness center with multiple pages and a clean, user-friendly design.

## 🌟 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean and professional design with smooth animations
- **Multi-page Layout** - Comprehensive website structure with dedicated pages
- **Cross-browser Compatible** - Works on all modern web browsers
- **Easy to Customize** - Well-organized code structure for easy modifications

## 📄 Pages Included

- **🏠 Home** - Welcome page with hero section and overview
- **ℹ️ About Us** - Information about the gym and team
- **💪 Services** - Detailed services and programs offered
- **📞 Contact** - Contact information and inquiry form
- **Other additional pages** 

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- **Python 3.7+** - [Download Python](https://python.org/downloads/)
- **Git** - [Download Git](https://git-scm.com/downloads)
- **Flask** - Will be installed via pip

### 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShaheerJamalChishti90/gym-website.git
   cd gym-website
   ```

2. **Install Flask**
   ```bash
   pip install flask
   ```
   
   Or if you have multiple Python versions:
   ```bash
   pip3 install flask
   ```

3. **Run the application**
   ```bash
   python app.py
   ```
   
   Or:
   ```bash
   flask run
   ```

4. **Open in browser**
   
   Navigate to: `http://localhost:5000` or `http://127.0.0.1:5000`

## 📁 Project Structure

```
gym-website/
│
├── app.py                 # Flask application file
├── README.md             # Project documentation
│
├── static/               # Static assets
│   ├── css/
│   │   └── style.css    # Main stylesheet
│
└── templates/           # HTML templates
    ├── index.html      # Home page
    ├── about.html      # About page
    ├── services.html   # Services page
    └── contact.html    # Contact page
    # And many more pages
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, animations, and responsive design
- **JavaScript** - Interactive elements and functionality
- **Flask** - Python web framework for serving pages

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `static/css/style.css`:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --accent-color: #your-color;
}
```

### Adding New Pages
1. Create new HTML file in `templates/` folder
2. Add route in `app.py`
3. Update navigation menu in `base.html`

### Modifying Content
- Edit HTML files in the `templates/` folder
- Update styles and images in `static/css/style.css`

## 🌐 Deployment

### Local Development
The site runs on Flask's development server at `http://localhost:5000`

### Production Deployment
For production deployment, consider:
- **GitHub Pages** (for static version)
- **Heroku** (for Flask version)
- **Netlify** (for static version)
- **Vercel** (for static version)

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Shaheer Jamal**
- GitHub: [@ShaheerJamalChishti90](https://github.com/ShaheerJamalChishti90)
- Email: shaheerjamal369@gmail.com
- LinkedIn: [Shaheer Jamal](https://www.linkedin.com/in/shaheer-jamal-b75307272/)

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Contact me via email

---

⭐ **Star this repository if you found it helpful!**
