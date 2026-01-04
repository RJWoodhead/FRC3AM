# Cutting and Facing Stock in the Carvera

The Makerspace where I do my machining does not have a cutoff saw suitable for cutting aluminum stock, so I created a simple [Fusion 360 project](Files/Stock Cutter.f3z) to perform both stock cutting and facing on the Carvera itself.

This is a configured design, and you can change the configurations depending on the dimensions of the stock and your desired final dimensions.

In the Manufacturing workspace, there are the setups: Cut, Face and Cut, and Face Only.

Cut cuts the stock to the desired X dimension, but only cuts halfway through the stock in Z. If you just want to cut stock, you just run this twice, flipping the stock after the first operation. This permits cutting stock up to 1" thick with the basic 3.125mm*12mm endmill, and also lets you clamp the stock using the Carvera's toe clamps.

If you want to face stock to a particular Z dimension, first run Cut to cut halfway through the stock and flip it. Then use Face and Cut to face and cut the second size of the stock.

If you just want to face a chunk of stock to a desired Z, use Face Only.