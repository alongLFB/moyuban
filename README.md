# Fish-Touching Office

A humorous web-based reminder application that helps office workers track their work-life balance through various time-based notifications and holiday countdowns.

## Features

- Multi-language support (English and Chinese)
- Real-time clock display with timezone information
- Support for multiple countries:
  - China
  - United Arab Emirates
  - United Kingdom
  - South Korea
  - United States
- Displays various countdown timers:
  - Days until next salary payment (multiple payment dates supported)
  - Days until next weekend
  - Days until upcoming holidays
- Year progress indicator
- One-click copy functionality for sharing reminders
- Responsive design for different screen sizes

## Usage

Simply open [index.html](index.html) in a web browser. The application will:

1. Show current time in your local timezone
2. Display time in the selected country's timezone
3. Show various countdowns for salary dates and holidays
4. Allow quick copying of all information for sharing

### Language Selection

Use the language dropdown menu in the top-right corner to switch between:

- Chinese (中文)
- English

### Country Selection

Use the country dropdown menu to switch between different countries and their respective:

- Timezone
- Holiday calendar
- Local time

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies required
- Supports all modern browsers
- Uses the browser's built-in `Intl` API for timezone handling
- Responsive CSS design using flexbox

## Customization

The application can be easily customized by modifying:

- Holiday data in the `holidaysByCountry` object
- Translation strings in the `translations` object
- Time format and display options in the update functions
- CSS styles in the `<style>` section

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available for personal and commercial use.

## Note

This is a fun project meant to remind office workers to take breaks and maintain a healthy work-life balance. Use it responsibly! 🐟
