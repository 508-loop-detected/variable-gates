# Variable Gates

This companion module to the Bounce Sequencer gives you individual control over both halves of the duty cycle of each step's gate. The left-hand knob controls the high (the gate), and the right-hand knob controls the low (the time interval before the next gate fires). The button or toggle switch controls whether a gate is emitted at that step.

In externally-clocked mode, an external clock is plugged in to the Bounce Sequencer, and the sequence progresses based on that clock. Each gate will fire (or not, depending on the toggle) when the clock advances. It's possible to set a gate length to span multiple clock steps in this mode.

In free-running mode, there is no clock plugged in to the Bounce Sequencer, and the Variable Gates module emits a clock step at the end of every gate cycle. This enables you to swing your sequence to the point of extreme stutter-step brokenness :)

The Variable Gates WILL NOT DO ANYTHING without its sibling the Bounce Sequencer: https://github.com/508-loop-detected/bounce-sequencer

All of the actual logic is in the Bounce Sequencer, which connects via expansion bus on the back.
