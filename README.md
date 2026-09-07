## How It Works

The converter stores each supported game's sensitivity conversion value (yaw) in JavaScript. When you choose a source game, target game, sensitivity, and DPI, the program uses those values to calculate a target sensitivity that keeps the same mouse movement / cm per 360°.

The result is calculated instantly whenever an input changes. It also calculates eDPI and approximate cm/360°, then updates the values and comparison bars on the page.

The game buttons, swap button, inputs, and results are all connected through JavaScript, while HTML creates the structure and CSS controls the appearance.

The project runs completely in the browser — there is no backend or database.
