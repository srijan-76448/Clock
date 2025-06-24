# Python Clock Application

This is a simple clock application built with Python's Tkinter library, featuring both digital and analog clock displays.

## Features

- **Digital Clock:** Displays current time (HH:MM:SS AM/PM), date (DD/MM/YYYY), and day of the week.
- **Analog Clock:** Visual representation of time with hour, minute, and second hands.
- **Customizable:** Easy to modify colors, dimensions, and fonts within the code.

## Requirements

- **Python 3.x**
- **Tkinter:** Usually included with Python installations.
- **`pygame`:** For the optional hourly sound feature.

To install `pygame`, use pip:

```bash
pip install pygame
```

## How to Run

1. **Save the code:** Save the provided Python code as a `.py` file (e.g., `clock_app.py`).
2. **Place `Clock.png`:** Ensure you have an image file named `Clock.png` in the same directory as the script for the window icon.
3. **(Optional) Sound File:** If you wish to enable the hourly sound, uncomment the `play_sound()` function call and provide the correct path to your `Ding.mp3` file.
4. **Execute:** Run the script from your terminal:

```bash
python clock_app.py
```

## Customization

You can modify various aspects of the clock by changing the constant values at the beginning of the script:

- **Window Dimensions and Colors:** `window_Width`, `window_Height`, `window_BG`, `window_Title`.
- **Digital Clock Appearance:** `Clock_Background`, `Digital_Clock_Foreground`, `Digital_Clock_Font`.
- **Analog Clock Hands:** `sec_h_len`, `sec_h_wth`, `sec_h_col` (for seconds hand) and similar for minute and hour hands.

## Structure

The application is structured into several functions:

- `create_digital_clock()`: Manages the display and updates of the digital time, date, and day.
- `create_analog_clock()`: Handles the drawing and animation of the analog clock hands.
- `play_sound()`: (Currently commented out) An optional function to play a sound every hour using `pygame`.

## Credits

This project was developed by **Srijan Bhattacharyya**, and it was his inaugural contribution to GitHub.
