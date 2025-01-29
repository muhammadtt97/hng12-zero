# HNG Stage 0 Frontend Task: Profile Card

## Overview
This project is a responsive profile card created as part of the HNG Internship Stage 0 Frontend task. It showcases personal and professional information in a clean, modern interface built with HTML, CSS, and Vanilla JavaScript.

## Features
- Responsive design that works across all device sizes
- Real-time UTC clock
- Professional social media links
- Clean and modern UI/UX
- All required elements with proper data-testid attributes for testing

## Live Demo
[View Live Demo]([https://muhammadtt97.github.io/hng12-zero/])

## Technical Details

### Required Elements
The profile card includes all required elements with their respective data-testid attributes:
- Profile Picture (`data-testid="profilePicture"`)
- Full Name (`data-testid="fullName"`)
- Job Title (`data-testid="jobTitle"`)
- Short Bio (`data-testid="shortBio"`)
- Current Location (`data-testid="currentLocation"`)
- Email Address (`data-testid="emailAddress"`)
- Social Links (`data-testid="socialLinks"`)
- Current UTC Time (`data-testid="currentTimeUTC"`)

### Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/hng-stage0-frontend.git
```

2. Navigate to the project directory:
```bash
cd hng-stage0-frontend
```

3. Open the project:
- For development: Open `index.html` in your preferred browser
- For production: Deploy to a hosting platform like Netlify or GitHub Pages

## Development

### File Structure
```
├── index.html          # Main HTML file
└── image.jpeg          # Image used
```

### Making Changes
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Create a Pull Request

## Testing

### Manual Testing
1. Open `index.html` in different browsers to ensure cross-browser compatibility
2. Test responsiveness using browser developer tools
3. Verify that all data-testid attributes are present
4. Check that UTC time updates correctly

### Automated Testing
The project includes data-testid attributes for automated testing purposes. These can be used with testing frameworks like Jest or Cypress.

## Deployment

### Netlify Deployment
1. Create a Netlify account
2. Connect your GitHub repository
3. Configure build settings:
   - Build command: Not required (static site)
   - Publish directory: Root directory
4. Deploy

### GitHub Pages Deployment
1. Go to repository settings
2. Navigate to Pages section
3. Select main branch as source
4. Save and wait for deployment

## Author
- Muhammad Al-Ameen Adamu
- Email: muhammadtt97@gmail.com
- GitHub: [muhammadtt97](https://github.com/muhammadtt97)
- LinkedIn: [Muhammad Al-Ameen Adamu](https://linkedin.com/in/muhammadtt97)
- Website: [alameentoro.com.ng](https://alameentoro.com.ng)

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments
- HNG Internship for the project requirements and guidance
- All contributors and reviewers
