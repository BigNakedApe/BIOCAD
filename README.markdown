# Amino Acid Sequence Alignment Tool

This is a frontend application developed as a test assignment for the Frontend Developer position at BIOCAD's Computational Biology Department. The tool visualizes the alignment of two amino acid sequences, providing a user-friendly interface for input, validation, and display.

## Features
- **Input Validation**:
  - Two input fields for amino acid sequences, accepting only valid characters (A, R, N, D, C, E, Q, G, H, I, L, K, M, F, P, S, T, W, Y, V, -).
  - Sequences must be of equal length and are mandatory.
  - Error messages are displayed for invalid inputs.
- **Sequence Alignment Visualization**:
  - Displays two sequences aligned vertically below the form upon submission.
  - The first sequence has background colors based on amino acid properties (aliphatic, aromatic, polar uncharged, negatively charged, positively charged).
  - The second sequence highlights differing amino acids with a red background.
- **Responsive Design**:
  - Adapts to screen sizes down to 320px.
  - Sequences wrap naturally while maintaining vertical alignment.
- **Search Functionality**:
  - Supports native browser search (Ctrl+F/Cmd+F) within the displayed sequences.
- **Copy-to-Clipboard**:
  - Selected sequence text is copied to the clipboard upon mouse release.
  - A notification appears for 1 second to confirm the copy action.
- **Deployment**:
  - Single `index.html` file, deployable on GitHub Pages without a build step.
  - Uses CDN-hosted React, React DOM, and Babel for simplicity.

## Technologies Used
- **React** with **TypeScript**
- **react-hook-form** for form management and validation
- **MUI (Material-UI)** for UI components
- **Styled-components** (via MUI's `styled`) for custom styling

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open `index.html` in a web browser.

## How to Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Place `index.html` in the root or `docs` folder.
3. Enable GitHub Pages in the repository settings, selecting the `main` branch or `docs` folder.
4. Access the deployed site via the provided GitHub Pages URL.

## Notes
- The color scheme for amino acids is simplified based on their properties.
- The application is designed for quick deployment and testing but can be extended with a Webpack setup for production use.
- All requirements, including optional features (search and copy-to-clipboard), are implemented.

## Demo
[Link to GitHub Pages deployment] (to be added after deployment)