# SmartBlog

A modern, responsive blog platform UI built with HTML, Tailwind CSS, and vanilla JavaScript. SmartBlog provides a clean, intuitive interface for content creators and administrators to manage their blogging experience.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with a focus on user experience
- **Landing Page**: Hero section, feature highlights, and newsletter subscription
- **User Dashboard**: Sidebar navigation for managing posts, drafts, and analytics
- **Admin Dashboard**: Comprehensive admin interface with content approval workflow and analytics
- **Authentication Pages**: Login and registration forms with mock authentication
- **Interactive Elements**: Smooth scrolling, mobile menu, form handling, and loading states
- **Performance Optimized**: Lazy loading images and optimized assets

## Technologies Used

- **HTML5**: Semantic markup for structure
- **Tailwind CSS**: Utility-first CSS framework loaded via CDN
- **Vanilla JavaScript**: For interactivity and dynamic behavior
- **Custom Color Palette**: Extended Tailwind theme with brand colors

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShuaibuPassionateProgrammer/smartblog.git
   cd smartblog
   ```

2. Open the project in your browser:
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js
     npx serve .

     # Using PHP
     php -S localhost:8000
     ```

3. Navigate to `http://localhost:8000` (or your chosen port)

## File Structure

```
smartblog/
├── index.html              # Main landing page
├── login.html              # User login page
├── register.html           # User registration page
├── user-dashboard.html     # User dashboard interface
├── admin-dashboard.html    # Admin dashboard interface
└── README.md               # Project documentation
```

## Usage

### Navigation

- **Home**: `index.html` - Landing page with blog overview
- **Login**: `login.html` - User authentication
- **Register**: `register.html` - New user registration
- **User Dashboard**: `user-dashboard.html` - Content management for users
- **Admin Dashboard**: `admin-dashboard.html` - Administrative controls

### Customization

The project uses Tailwind CSS loaded via CDN, making it easy to customize:

1. **Colors**: Modify the `tailwind.config` object in each HTML file's `<script>` tag
2. **Content**: Edit the HTML directly to update text, images, and layout
3. **Styling**: Add or modify Tailwind classes for different appearances
4. **JavaScript**: Enhance interactivity by modifying the script sections

### Forms and Interactions

- Newsletter subscription (demo mode)
- Authentication forms (mock functionality)
- Mobile-responsive navigation
- Smooth scrolling between sections

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons and design inspired by modern blogging platforms
- Color palette designed for accessibility and readability
