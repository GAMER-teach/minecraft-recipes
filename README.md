
# ⛏️ Minecraft Recipes Website

A comprehensive, interactive website showcasing all essential Minecraft crafting recipes. Built with HTML, CSS, and JavaScript, this resource provides a user-friendly interface to explore and learn crafting recipes across multiple categories.

## 🎮 Features

- **📚 Complete Recipe Database** - Tools, Weapons, Armor, Blocks, and Miscellaneous items
- **🎨 Interactive UI** - Beautiful, responsive design with smooth animations
- **📱 Mobile Friendly** - Fully responsive layout for all screen sizes
- **🔍 Easy Navigation** - Sticky navigation bar with quick access to categories
- **⚡ Smooth Animations** - Fade-in effects and hover interactions
- **🎯 Visual Crafting Grid** - Clear representation of crafting patterns

## 📂 Project Structure

```
minecraft-recipes/
├── index.html      # Main HTML file with all recipe cards
├── styles.css      # Styling and responsive design
├── script.js       # Interactive features and animations
└── README.md       # Project documentation
```

## 🚀 Quick Start

1. **Visit the website**: [minecraft-recipes GitHub Pages](#)
2. **Browse recipes** using the navigation bar
3. **Explore categories**:
   - ⚒️ Tools - Pickaxes, Axes, and more
   - ⚔️ Weapons - Swords, Bows, and combat items
   - 🛡️ Armor - Helmets, Chestplates, and protective gear
   - 🧱 Blocks - Building materials and furniture
   - ✨ Miscellaneous - Beds, Torches, Doors, and more

## 🎨 Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6)** - Interactive features, animations, and smooth scrolling
- **Responsive Design** - Mobile-first approach

## 🌟 Key Features

### Navigation System
- Sticky navigation bar that updates based on scroll position
- Smooth scrolling to recipe sections
- Active link highlighting

### Recipe Cards
- Clean, organized recipe layout
- Crafting grid visualization
- Hover effects and animations
- Category-based organization

### Responsive Design
- Adapts to desktop, tablet, and mobile screens
- Flexible grid layout
- Touch-friendly interface

## 📖 How to Use

### View Recipes
1. Use the navigation bar at the top to jump to different categories
2. Scroll through recipe cards in each section
3. Each recipe shows the required ingredients and crafting pattern

### Categories

#### ⚒️ Tools
- Wooden, Stone, Iron, and Diamond Pickaxes
- Wooden Axe
- Crafting Table

#### ⚔️ Weapons
- Wooden, Stone, Iron, and Diamond Swords
- Bow

#### 🛡️ Armor
- Leather, Iron, and Diamond Helmets
- Iron and Diamond Chestplates

#### 🧱 Blocks
- Wood Planks and Sticks
- Chest and Furnace
- Bookshelf
- Stone Bricks

#### ✨ Miscellaneous
- Bed
- Torches
- Iron Ingot (Smelting)
- Glass
- Door
- Ladder

## 🛠️ Customization

### Add New Recipes
To add new recipes, add a new `recipe-card` div to the appropriate section in `index.html`:

```html
<div class="recipe-card">
    <h3>Recipe Name</h3>
    <div class="recipe-grid-2x2">
        <div class="ingredient">Item 1</div>
        <div class="ingredient">Item 2</div>
        <!-- Add more items -->
    </div>
    <p class="output">→ Crafted Item</p>
</div>
```

### Modify Styling
Edit `styles.css` to customize:
- Colors (update CSS variables in `:root`)
- Fonts and sizes
- Layout and spacing
- Animations

### Enhance Interactivity
Update `script.js` to add:
- Search functionality
- Filter by difficulty
- Recipe bookmarking
- Print recipes

## 🎯 Future Enhancements

- [ ] Search and filter functionality
- [ ] Advanced smelting and cooking recipes
- [ ] Enchantment recipes
- [ ] Brewing recipes
- [ ] Dark mode toggle
- [ ] Difficulty filtering (Easy, Normal, Hard)
- [ ] Recipe comments and tips
- [ ] Keyboard shortcuts for navigation

## 📱 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- Inspired by the Minecraft Wiki and official crafting recipes
- Built with modern web technologies
- Dedicated to all Minecraft enthusiasts

## 🐛 Bug Reports & Suggestions

Found an issue or have a suggestion? Feel free to:
- Open an issue on GitHub
- Submit a pull request with improvements
- Share feedback and ideas

## 📞 Contact

For questions or feedback, reach out through GitHub Issues or GitHub Discussions.

---

**Happy Crafting!** ⛏️🎮
