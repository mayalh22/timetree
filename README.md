# timetree

Timetree is a pixelated timer that grows a tree as time passes

I wanted Time Tree to be more minimalistic than some of my other projects, so I tried to make Time Tree completely pixelated

Unlike a standard timer, this website features a growing tree as a visual representation of your progress. It grows from a small trunk to a rull-fledged tree, as a satisfying reward for completion.

Because Time Tree does not have overwhelming graphics or features, it helps keep focus.

To use it, enter your desired time in seconds into the input field and click "start". You can pause at any time and resume when you are ready.

This is built with a standard HTML, CSS, and JS stack. The functionality is in JS, using HTML canvas element to render pixel art graphics, relying on variables and cuntions to manage state and visuals

Start timer and Pause timer functions handle primary user-facing logic, controlling setinterval loop, updating variables like timeleft and tree high.

The sizing of the canvas in managed by the resize canvases function, changing pixel size

It is simple in aesthetic and code: not needing external libraries or frameworks

I used gemini for help with the pause timer function and overall syntax feedback and I used copilot for help fixing indent errors

thanks!