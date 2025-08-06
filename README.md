# Text Cleanup Tool

A simple, browser-based text cleanup utility that helps format text by standardizing dashes and spacing.

## Features

- **Em Dash Replacement**: Converts em dashes (—) to regular dashes (-)
- **Smart Spacing**: Automatically adds spaces around em dashes when converting them to regular dashes
- **Preserves Formatting**: Maintains existing spacing when already present
- **Real-time Processing**: Text is cleaned automatically as you type
- **Copy to Clipboard**: One-click copying of cleaned text
- **Responsive Design**: Works on desktop and mobile devices

## Usage

1. Open `index.html` in any modern web browser
2. Paste your text into the "Original Text" textarea
3. The cleaned text will appear automatically in the "Cleaned Text" textarea
4. Use the "Copy Cleaned Text" button to copy the result to your clipboard
5. Use "Clear All" to reset both text areas

## What It Does

The tool performs the following text transformations:

- **Em dash conversion**: `—` → `-`
- **Adds spaces around em dashes**: `word—word` → `word - word`
- **Handles edge cases**: 
  - `-word` → `- word` (dash at beginning)
  - `word-` → `word -` (dash at end)

## Examples

### Input:
```
This is a test—with em dashes and word-word combinations.
```

### Output:
```
This is a test - with em dashes and word-word combinations.
```

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies required
- **Modern Browser Support**: Uses the Clipboard API with fallback for older browsers
- **Responsive Layout**: Flexbox-based design that adapts to different screen sizes
- **Accessibility**: Proper labels and semantic HTML structure

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start cleaning your text!

## Browser Compatibility

- Chrome 66+
- Firefox 63+
- Safari 13.1+
- Edge 79+

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve this tool.

## Why This Tool?

This tool was created to help with text formatting tasks, particularly useful for:
- Cleaning up copied text from various sources
- Standardizing dash usage in documents
- Preparing text for consistent formatting
- Quick text cleanup without needing complex text editors 