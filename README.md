
# Jupyter Variable Tracking Extension

This project is a custom extension for **Jupyter Notebooks** that tracks changes made to specific variables during notebook execution. The extension provides various functionalities such as adding, removing, and displaying tracked variables, as well as saving the tracking results to a file.

## Features

- **Track specific variables**: Automatically monitor changes to selected variables in the notebook.
- **Add or remove variables from tracking**: Dynamically update the list of variables being tracked.
- **Display tracking results**: View the changes made to tracked variables in real-time.
- **Save tracking results**: Save the recorded changes to an external file for further analysis.

## How It Works

The extension scans the executed cells in a Jupyter Notebook and:
1. **Tracks Variables**: Using custom comment-based commands like `track_variable()`, the extension tracks the specified variables.
2. **Updates Tracking List**: You can add or remove variables from the tracking list dynamically during the execution.
3. **Displays and Saves Results**: You can display the results directly within the notebook or save them to a file for later use.

### Custom Commands

- `track_variable(variable_name)`: Begin tracking the specified variable.
- `track_variable_add(variable_name)`: Add a new variable to the existing tracking list.
- `track_variable_remove(variable_name)`: Remove a variable from the tracking list.
- `display_tracking_variable`: Display the currently tracked variables.
- `display_tracking_result`: Show the results of the tracked variable changes.
- `save_tracking_result`: Save the tracked changes to a file called `context.txt`.
- `end_track`: End tracking and reset the tracked variables list.

## Getting Started

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sanyam1259/variable_tracker.git
   ```

2. Navigate to the cloned folder:
   ```bash
   cd your-repo-name
   ```

3. Follow standard procedures for installing a Jupyter Notebook extension.

### Usage

- After installing, you can use the extension inside any Jupyter Notebook. 
- Use the custom commands mentioned above to start tracking variables and monitor changes in real-time.
