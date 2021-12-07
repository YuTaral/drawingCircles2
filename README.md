Another C++ Windows Desktop Application. It also creates child window when the application starts (same as drawingCircles repo). This time the child window can be resized.
When we click in the main window, it sends message to the child frame and the circle is drawn in the child window with coordinates corresponding to the click in the main window.
Before every draw the app calculates the ratio of the sizes of the main window and the child window.
