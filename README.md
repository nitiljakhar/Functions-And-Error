<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fusion Reactor System GUI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2, h3 {
            color: #333;
        }
        code {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 2px 4px;
            font-family: "Courier New", Courier, monospace;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-left: 3px solid #ddd;
            overflow-x: auto;
        }
        .commands {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Fusion Reactor System GUI</h1>

    <p>
        This Python program provides a graphical user interface (GUI) to manage a fusion reactor system code. It allows users to select various parameters for different subsystems (like Figures of Merit, Constraints, Build variables, etc.) through an interactive menu and checkboxes. The GUI is built using the <code>Tkinter</code> library.
    </p>

    <h2>Features</h2>
    <ul>
        <li><strong>Modular Parameter Selection:</strong> Supports selection for Figures of Merit, Constraints, Build Variables, and more. Enables 1D and 2D scans for input data.</li>
        <li><strong>Search and Replace:</strong> Find specific text and replace it with new values within the main text editor.</li>
        <li><strong>Scrollable Checkbox Menus:</strong> Parameter selection is available via checkboxes for various modules, allowing easy toggling of options.</li>
        <li><strong>Dynamic Update:</strong> Updates the state of checkboxes dynamically based on changes in the text box content.</li>
        <li><strong>Shortcut Support:</strong> Keyboard shortcuts are included for search (<code>Ctrl+F</code>) and replace (<code>Ctrl+H</code>).</li>
        <li><strong>Summary and Execute:</strong> Two main buttons are available to summarize selected options and execute the final command.</li>
    </ul>

    <h2>Installation</h2>
    <p><strong>Prerequisites:</strong></p>
    <ul>
        <li>Python 3.x</li>
        <li>Tkinter library (typically pre-installed with Python)</li>
    </ul>

    <p><strong>Clone the Repository:</strong></p>
    <pre><code>git clone https://github.com/yourusername/fusion-reactor-gui.git
cd fusion-reactor-gui</code></pre>

    <p><strong>Run the Program:</strong></p>
    <pre><code>python3 fusion_gui.py</code></pre>

    <h2>Usage Instructions</h2>

    <h3>Main Menu</h3>
    <p>Once the GUI starts, you'll see a menu bar at the top of the window. Here's what each menu option provides:</p>

    <ul>
        <li><strong>File:</strong> 
            <ul>
                <li><strong>Open:</strong> Opens an existing input file.</li>
                <li><strong>Save:</strong> Saves the current configuration.</li>
                <li><strong>Save As:</strong> Saves the current configuration under a new file name.</li>
                <li><strong>Search and Replace:</strong> Opens a window to search for specific text and optionally replace it in the main text box.</li>
                <li><strong>Exit:</strong> Closes the application.</li>
            </ul>
        </li>
        <li><strong>Figure-of-Merit:</strong> Opens a checkbox window to select the desired Figures-of-Merit (FoM).</li>
        <li><strong>Constraint:</strong> Opens a window to select constraint values.</li>
        <li><strong>Iteration:</strong> Opens a window to choose iteration options.</li>
    </ul>

    <h3>Scan Module</h3>
    <p>This menu handles sweeping parameters for 1D and 2D scans:</p>
    <ul>
        <li><strong>1D:</strong> Select a parameter to sweep and enter the values as a comma-separated list.</li>
        <li><strong>2D:</strong> Choose two parameters to sweep in 2D and enter the values for both as comma-separated lists.</li>
    </ul>

    <h3>Variable Selection (Various Modules)</h3>
    <p>The menu also offers various categories to select from:</p>
    <ul>
        <li><strong>Build:</strong> Opens a menu to select variables related to the build process.</li>
        <li><strong>Constraint Variables:</strong> Choose constraints for the fusion reactor system.</li>
    </ul>

</body>
</html>
