# linkedIn-queens-solver extension

LinkedIn Queens Solver is a Chrome extension engineered to intelligently analyze and solve the LinkedIn Queens puzzle directly within the browser. The project combines browser automation, DOM traversal, recursive backtracking, and dynamic grid reconstruction to generate accurate puzzle solutions in real time.

Rather than relying on hardcoded layouts, the extension programmatically detects puzzle cells, extracts color-region information from the webpage, reconstructs the board into a matrix representation, and computes a valid solution using a custom constraint-based solving algorithm inspired by the classical N-Queens problem.

The extension dynamically reconstructs the puzzle state directly from the webpage DOM and computes valid queen placements using a constraint-driven recursive solver.


## Algorithms and Concepts

- Dynamic board detection
- Recursive Backtracking
- Constraint Satisfaction Problem (CSP)
- Matrix-based reconstruction
- DOM traversal and analysis
- Coordinate-based cell grouping
- Region/color mapping
- Constraint validation
- Recursive state-space search
- Adjacency conflict detection
- Browser automation
- Visual solution overlay


## Tech Stack

- JavaScript
- HTML5
- CSS3
- C++ (original solving logic)
- Chrome Extensions Manifest V3
- Chrome Scripting API
- DOM Manipulation APIs
- Browser Event Handling
- Recursive Backtracking
- Matrix & state-space modelling

## Installation

**1) Clone the Repository**

```bash
git clone https://github.com/your-username/linkedin-queens-solver.git
```

**2) Open Chrome Extensions**

```txt
chrome://extensions
```

**3) Enable Developer Mode**


**4) Load the Extension**

- Click **Load unpacked**
- Select the project folder

**5) Run the Solver**

- Open LinkedIn Queens
- Click the extension icon
- Press **Solve Puzzle**
