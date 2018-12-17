# IdleClassAutocrat
The Autocrat, an automation tool for the idle game The Idle Class by Small Gray Games, https://www.smallgraygames.com/the-idle-class

Made for fun by Argembarger in December 2018.

This tool basically handles everything in the game, including the bankruptcy loop. It tries not to spend more than 10% of your money on anything. It's certainly not an optimized system, and there are many manual decisions you can make to speed up progression, which I think is one of the nice things about this tool. There are also some achievements in the game that you would probably want to do without this tool enabled.

Instructions are in the script itself, but the basic gist is that you can just paste it into the developer console on your browser after the game loads, and it will start doing its thing. You can feel free to modify any setting or tweak the system to your liking, just read through the code. 

The code is comprised of the Autocrat function, which essentially checks every interactable game feature, followed by an interval-looping function to kick the whole thing off.

When you're done using the tool, simply refresh the game window.

I haven't noticed any problems in quite some time. It should be more or less safe on the game's save data, although I managed to corrupt the game tons of times while writing this, probing around the game's code willy-nilly :)