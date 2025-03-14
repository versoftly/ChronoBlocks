# ChronoBlocks

ChronoBlocks is a simple, customizable web application for tracking time blocks throughout the day. It allows you to define custom time blocks with associated messages and triggers alarms at the start of each block.  It's built with HTML, CSS, and JavaScript, and uses localStorage to persist your settings.

## Features

*   **Customizable Time Blocks:** Define your own time blocks with start and end times, and custom messages.
*   **Audible Alarms:**  The application displays an alert (which serves as a basic alarm) at the beginning of each defined time block.
*   **Persistent Settings:** Your time block configurations are saved using `localStorage`, so they persist even if you close or refresh the browser.
*   **Reset to Defaults:**  Easily reset the time blocks to the pre-configured default schedule.
*   **Continuously Updating Clock:**  The current time is displayed and updates every second.
*   **Responsive Design:**  The application is designed to work well on different screen sizes.
*   **Easy to Use:**  The interface is simple and intuitive.
*  **No external libraries:** The project is built using vanila javascript.

## How to Use

1.  **Clone the Repository:**
    ```bash
    git clone <your-repository-url>
    ```
    (Replace `<your-repository-url>` with the actual URL of your GitHub repository.)

2.  **Open `index.html`:** Open the `index.html` file in your web browser.

3.  **Customize Settings:**
    *   The application will initially load with a default schedule.
    *   Click the "Settings" section to expand it.
    *   Modify the "Start Time," "End Time," and "Message" for each time block.
    *   Click "Save Settings" to save your changes.

4. **Reset Settings:**
  	* Click the "Reset to Defaults" to restore the time blocks to the original configuration.

## Technologies Used

*   HTML
*   CSS (with CSS Grid)
*   JavaScript (Vanilla JavaScript - no external libraries or frameworks)
*   localStorage

## Project Structure

*   `index.html`:  The main HTML file containing the structure of the web page.
*   `style.css` (embedded in `index.html`):  The CSS styles for the application.
*   `script.js` (embedded in `index.html`): The JavaScript code for the application's functionality.

## Customization

*   **Project Name:** You can change the project name by modifying the `<title>` tag in `index.html`.
*   **Default Time Blocks:** To change the *initial* default time blocks, modify the `defaultTimeBlocks` array in the JavaScript code (`script.js` section within `index.html`).
*   **Styling:**  You can customize the appearance of the application by editing the CSS in the `<style>` tag within `index.html`.

## Contributing

If you'd like to contribute to ChronoBlocks, feel free to fork the repository and submit pull requests.  Here are some ideas for enhancements:

*   **Sound Alarms:** Implement actual audio alarms (with user consent for autoplay).
*   **Visual Notifications:** Add visual cues (e.g., changing background colors) for different time blocks, in addition to the alert.
*   **More Robust Input Validation:**  Add more comprehensive validation to the settings form to prevent invalid time entries.
*   **Improved Time Handling:** Use a library like Moment.js or the built-in `Intl` object for more advanced time zone and formatting options (this would add a dependency).
*  **Themes:** Allow selection between light/dark themes.

## License

This project is licensed under the MIT license