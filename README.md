# Sorting Algorithm Visualizer

An interactive web application that visualizes various sorting algorithms in real-time. This educational tool helps users understand how different sorting algorithms work through animated visualizations and performance metrics.

![Sorting Visualizer Demo](demo.gif)

## Features

- **Multiple Sorting Algorithms:**
  - Bubble Sort
  - Insertion Sort
  - Selection Sort
  - Heap Sort
  - Quick Sort
  - Merge Sort

- **Interactive Controls:**
  - Adjust array size
  - Control sorting speed
  - Custom array input
  - Play/Pause functionality
  - Generate new random arrays
  - Dark mode toggle

- **Real-time Visualization:**
  - Color-coded states (comparing, swapping, sorted)
  - Step-by-step animation
  - Performance metrics tracking

- **Educational Components:**
  - Algorithm complexity information
  - Real-time explanations of steps
  - Performance metrics display (swaps and comparisons)

## Technologies Used

- React with TypeScript
- Vite for build tooling
- Tailwind CSS for styling
- Shadcn UI components
- Node.js and Express for server

## Prerequisites

- Node.js (version 22.13.0 or later)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/OmshriSawant/Sorting-Visualizer.git
cd sorting-visualizer
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to:
```
http://localhost:5000
```

## Usage

1. **Select Algorithm:** Choose a sorting algorithm from the dropdown menu.

2. **Adjust Settings:**
   - Use the speed slider to control the animation speed
   - Use the size slider to change the array size
   - Enter custom numbers in the input field for a custom array

3. **Controls:**
   - Click the play button to start sorting
   - Use the pause button to pause the animation
   - Click the refresh button to generate a new random array
   - Toggle dark mode with the theme button

4. **Visualization:**
   - Blue bars: Unsorted elements
   - Yellow bars: Elements being compared
   - Red bars: Elements being swapped
   - Green bars: Sorted elements

## Performance Metrics

The application displays real-time performance metrics:
- Number of comparisons
- Number of swaps
- Time complexity
- Space complexity

## Algorithm Information

Each sorting algorithm comes with:
- Time complexity information
- Space complexity details
- Step-by-step explanation of the process
- Real-time feedback during sorting

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [React](https://reactjs.org/)
- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Icons from [Lucide](https://lucide.dev/)
