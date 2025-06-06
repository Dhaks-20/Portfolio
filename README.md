# Modern Portfolio Website

A modern, responsive portfolio website template built with Bootstrap 5, featuring a clean design and smooth animations.

## Features

- Responsive design that works on all devices
- Modern and clean UI
- Smooth scrolling and animations
- Portfolio filtering system
- Contact form
- Social media integration
- Back to top button
- Preloader
- Sticky navigation
- Progress bars for skills
- Service cards with hover effects

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser to view the website
3. Customize the content to make it your own

## Customization

### Personal Information

Edit the following sections in `index.html`:

- Your name and title in the hero section
- About section content
- Skills and their percentages
- Services offered
- Portfolio items
- Contact information
- Social media links

### Images

Replace the placeholder images in the `images` folder with your own:

- `hero-image.png` - Your hero section image
- `about-image.jpg` - Your about section image
- Portfolio images in the portfolio section

### Colors

The main colors can be customized in `css/style.css`. Look for the `:root` section at the top of the file:

```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    --dark-color: #343a40;
    --light-color: #f8f9fa;
}
```

### Portfolio Items

To add portfolio items, add them to the portfolio section in `index.html`:

```html
<div class="col-md-4 portfolio-item web">
    <div class="item">
        <img src="images/portfolio/item1.jpg" alt="Portfolio Item">
        <div class="overlay">
            <h4>Project Title</h4>
            <p>Category</p>
            <a href="#" class="btn btn-primary">View Project</a>
        </div>
    </div>
</div>
```

## Dependencies

- Bootstrap 5.3.3
- Font Awesome 6.5.1
- Google Fonts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- Bootstrap - https://getbootstrap.com/
- Font Awesome - https://fontawesome.com/
- Google Fonts - https://fonts.google.com/ 