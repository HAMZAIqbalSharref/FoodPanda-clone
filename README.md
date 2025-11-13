# FoodPanda Clone

A modern food delivery web application clone built with HTML, CSS, and responsive design principles.

## Features

- **Responsive Layout**: Two-column design with sticky navigation and filters sidebar
- **Search Functionality**: Search for restaurants, cuisines, and dishes
- **Filter Sidebar**: Advanced filtering options including:
  - Sort by (Relevance, Fastest Delivery, Distance, Top Rated)
  - Quick Filters (Ratings 4+, Super Restaurants)
  - Offers (Free Delivery, Vouchers, Deals)
  - Cuisine Search and Selection
- **Signup Banner**: Eye-catching promotional banner with CTA
- **Daily Deals Section**: Featured deals and offers
- **Cuisines Gallery**: Browse popular cuisines with images and names
- **Sticky Navigation**: Header and navigation bar stay visible while scrolling
- **Custom Scrollbar**: Styled scrollbars in the filters sidebar
- **Footer**: Comprehensive footer with links and information

## Project Structure

```
.
├── index.html              # Main HTML file
├── style.css               # Main stylesheet
├── images/                 # Logo and banner images
├── cusines/               # Cuisine images
├── Homechefs/             # Chef featured items
├── kamal cravings sections/ # Special cuisine sections
└── up_to_30 off/          # Promotional items
```

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Flexbox, Grid, Custom Properties
- **Responsive Design**: Mobile-first approach
- **Custom Scrollbars**: WebKit and Firefox support

## Layout Details

### Header
- Fixed height with logo and signup buttons
- Sticky positioning for easy access

### Navigation Bar
- Sticky navigation with delivery options
- Links: Delivery, Pick Up, Pandamart, Shops, Caterers

### Main Content Area
- **Search Bar**: Full-width search input
- **Signup Banner**: Pink background (#fce4ec) with call-to-action
- **Daily Deals**: Featured deal cards with badges
- **Cuisines**: Grid gallery of cuisine options

### Sidebar Filters
- Sticky positioning at top: 120px
- Independent scrolling with custom scrollbar
- Height: calc(100vh - 120px)

## CSS Features

### Custom Scrollbars
- Width: 8px
- Color: #c1c1c1 (hover: #a8a8a8)
- Supports WebKit browsers and Firefox

### Color Scheme
- Primary Pink: #E01B6F
- Light Pink Banner: #fce4ec
- Light Gray Background: #f8f8f8
- Border Color: #eaeaea

### Responsive Typography
- H1: 20px (filters title)
- H2: 24-36px (section titles)
- H3: 28px (deals heading)
- Body: 14px

## Setup

1. Clone the repository:
```bash
git clone https://github.com/HAMZAIqbalSharref/FoodPanda-clone.git
```

2. Open `index.html` in your browser

3. No build process required - it's vanilla HTML/CSS

## Future Enhancements

- JavaScript interactivity for filters
- Add to cart functionality
- Restaurant detail pages
- Payment integration
- User authentication
- Order tracking

## Author

Hamza Iqbal Sharref

## License

MIT License - feel free to use this project for learning and personal projects.
