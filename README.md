# DJSanz - Mix Player

## Overview

DJSanz is a web application that allows users to listen to a collection of music mixes. The app showcases each mix with its corresponding album art and provides a play button to listen to the mixes directly from the webpage.

## Features

- **Responsive Design**: Uses Bootstrap for a responsive and modern UI.
- **Mix Display**: Each mix is displayed with its album art and a play button.
- **Audio Playback**: Users can play mixes directly on the webpage.
- **Hover Effects**: Adds interactive hover effects to the mix cards.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/djsanz.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd djsanz
    ```

3. **Open the `index.html` file in your browser**:
    Simply double-click the `index.html` file or open it using your preferred web browser.

## File Structure

- `index.html`: The main HTML file containing the structure of the webpage.
- `style.css`: (Optional) If you want to separate the styles into a CSS file.
- `scripts.js`: (Optional) If you want to separate the JavaScript into a JS file.
- `assets/`: Directory containing audio files and album art images.

## Dependencies

- **Bootstrap**: For responsive design and styling.
  - CSS: `https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css`
  - JS: `https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js`

## Usage

1. **Adding New Mixes**:
   - To add a new mix, update the `mixes` array in the JavaScript section of the `index.html` file:
     ```js
     var mixes = [
         { mix: "path/to/mix.wav", albumArt: "path/to/albumArt.png" },
         // Add more mixes here
     ];
     ```

2. **Running the App**:
   - Open the `index.html` file in a web browser. The mix list will be displayed with album art, audio controls, and play buttons.

## Customization

- **Styling**:
  - You can modify the styles directly in the `<style>` tag within the `index.html` file or move them to a separate `style.css` file.

- **JavaScript**:
  - For better organization, you can move the JavaScript code to a separate `scripts.js` file and include it in the `index.html`:
    ```html
    <script src="scripts.js"></script>
    ```

## Contributing

1. **Fork the repository**.
2. **Create a new branch**: `git checkout -b feature/new-feature`
3. **Commit your changes**: `git commit -m 'Add some new feature'`
4. **Push to the branch**: `git push origin feature/new-feature`
5. **Open a pull request**.

## Contact

If you have any questions or suggestions, feel free to reach out to the project maintainer at [email@example.com].
