# Maitreyi College Website

A modern, responsive educational institution website built with HTML5, Bootstrap 5, and JavaScript, featuring a comprehensive admin panel for content management.

## Features

### Frontend
- **Responsive Design**: Mobile-first approach with Bootstrap 5
- **Modern UI**: Clean, professional design with smooth animations
- **Multi-level Navigation**: Comprehensive menu structure
- **Hero Carousel**: Dynamic image slider with captions
- **Notice Board**: Real-time notices and announcements
- **Gallery**: Filterable image gallery with modal view
- **About Section**: College history, vision, and mission
- **Quick Links**: Easy access to important resources
- **Recent Activities**: Showcase of college events

### Admin Panel
- **Secure Authentication**: Login system with session management
- **Dashboard**: Overview with statistics and recent activity
- **Content Management**: Manage notices, events, and pages
- **Gallery Management**: Upload and organize photos
- **User Management**: Faculty and student administration
- **Reports**: Generate various administrative reports
- **Quick Actions**: Frequently used admin functions

## Project Structure

```
new collage/
├── index.html                 # Main homepage
├── gallery.html              # Photo gallery page
├── about/
│   └── college.html          # About college page
├── admin/
│   ├── login.html            # Admin login page
│   └── dashboard.html        # Admin dashboard
├── assets/
│   ├── css/
│   │   └── style.css         # Custom styles
│   ├── js/
│   │   └── script.js         # Main JavaScript
│   └── images/               # Image assets
└── README.md                 # This file
```

## Technology Stack

- **HTML5**: Semantic markup
- **Bootstrap 5**: CSS framework and components
- **JavaScript ES6+**: Interactive functionality
- **Font Awesome**: Icon library
- **CSS3**: Custom animations and transitions

## Getting Started

1. **Clone/Download** the project to your local machine
2. **Set up** a local server (XAMPP, WAMP, or Live Server extension)
3. **Access** the website via `http://localhost/new collage/`

### Admin Access
- **URL**: `http://localhost/new collage/admin/login.html`
- **Username**: `admin`
- **Password**: `admin123`

## Key Components

### Navigation Structure
- Home
- About Us (College, Principal's Desk, Vision, Departments, etc.)
- Admission (Courses, Prospectus, Fees, Support)
- Departments (Science, Commerce, Arts)
- Governance (Principal, Staff, Committees)
- Gallery
- Contact

### Admin Features
- Dashboard with statistics
- Notice management
- Event management
- Gallery management
- User management
- Settings and configuration

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly interface
- Accessible navigation

## Customization

### Colors and Theme
Edit the CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #0056b3;
    --secondary-color: #6c757d;
    --accent-color: #ffc107;
    --dark-color: #212529;
    --light-color: #f8f9fa;
}
```

### Adding New Pages
1. Create HTML file in appropriate directory
2. Include navigation and footer placeholders
3. Add page-specific content
4. Update navigation menu in `index.html`

### Admin Customization
- Modify authentication in `admin/login.html`
- Update dashboard statistics in `admin/dashboard.html`
- Add new admin sections as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Security Notes

- Change default admin credentials
- Implement server-side authentication for production
- Add CSRF protection
- Validate all user inputs
- Use HTTPS in production

## Future Enhancements

- [ ] Backend integration (PHP/Node.js)
- [ ] Database connectivity
- [ ] File upload functionality
- [ ] Email notifications
- [ ] Search functionality
- [ ] Multi-language support
- [ ] Social media integration
- [ ] Online admission form
- [ ] Student portal
- [ ] Alumni network

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support and questions, please contact the development team or create an issue in the repository.

---

**Note**: This is a frontend demonstration. For production use, implement proper backend authentication, database connectivity, and security measures.
