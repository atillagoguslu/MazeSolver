# Maze Solver

A web-based maze generation and solving application that demonstrates CSS layout performance through interactive maze visualization.

## Features

- **Random Maze Generation**: Creates mazes using a depth-first search algorithm
- **Multiple Sizes**: Choose from 20×20, 30×30, or 40×40 maze configurations
- **Interactive Solving**: Watch the maze solver find the optimal path from start to end
- **Performance Testing**: Measures and displays the time taken to solve each maze
- **Visual Feedback**: Color-coded visualization shows the solution path and explored dead ends
- **Responsive Design**: Works across different browsers and screen sizes

## How It Works

1. **Maze Generation**: The application uses a randomized DFS algorithm to create unique maze layouts
2. **Path Finding**: Implements a pathfinding algorithm to find the shortest route from start to finish
3. **CSS Performance**: Each step in the solving process triggers CSS layout recalculations to test browser performance
4. **Visualization**: The solving process is animated with colored circles representing:
   - Green: Part of the solution path
   - Red: Dead ends explored during search

## Usage

### Running the Application

1. Open `index.html` in any modern web browser
2. Select your preferred maze size (20×20, 30×30, or 40×40)
3. Click the refresh button to generate a new random maze
4. Click the start button to begin solving the maze
5. Watch as the algorithm finds the solution path in real-time

### Controls

- **Size Selector**: Choose maze dimensions (tab index 1)
- **Refresh Button**: Generate a new random maze (tab index 2)
- **Start Button**: Begin maze solving animation (tab index 3)
- **Close Button**: Hide the results summary (tab index 4)

## Technical Details

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Algorithms**: DFS for maze generation, pathfinding for maze solving
- **Performance Focus**: Tests CSS layout engine performance through DOM manipulation
- **Fonts**: Custom "Pencil Grid" font for retro styling
- **Browser Compatibility**: Designed for modern browsers with CSS3 support

## Project Structure

```
MazeSolver/
├── index.html              # Main application file
├── src/
│   ├── css/
│   │   ├── BaseStyles.css  # Base styling
│   │   └── maze.css        # Maze-specific styles
│   └── js/
│       ├── maze.js         # Core maze logic
│       ├── seedrandom.js   # Random number generation
│       └── BrowserInfo.js  # Browser detection
├── public/                 # Static assets
│   ├── *.png              # Button images
│   └── FavIcon.ico        # Favicon
└── src/pencilgrid.woff     # Custom font
```

## History

This application was originally developed as a Microsoft Internet Explorer 9 test drive demo to showcase CSS3 layout performance capabilities.

## Browser Support

Works best in modern browsers with full CSS3 support:

- Chrome/Edge
- Firefox
- Safari

## Contributing

Feel free to fork this project and submit pull requests with improvements to the maze generation algorithms, visual design, or performance optimizations.

## License

This project is open source. See the original Microsoft copyright notice in the HTML file for specific licensing details.
