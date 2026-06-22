Deep learning help
Shared by Greg
This is a copy of a chat between Claude and Greg. Content may include unverified or unsafe content that do not represent the views of Anthropic. Shared snapshot may contain attachments and data not displayed here.

Heelo Claude, would you mind if I asked you for some help with Deep Learning?

10:33 AM
Hey there! Welcome to CSC-114 InfoBot! 😊

Of course — I'd be happy to help with Deep Learning questions! I have a great introductory reading available to draw from. What would you like to know?

Can you tell me anything about how the "Hot/Cold method" is related with gradient descent?

10:34 AM
Great question! The "Hot-and-Cold" game is actually used in the course reading as the key analogy for understanding gradient descent. Here's how they connect:

The parallel is direct:

The "treat" you're searching for = the lowest possible loss (wrongness)
Each "step" you take = a small adjustment to the network's dials (weights & biases)
The "warmer/colder" feedback = the gradient — which tells the network which direction to nudge each dial to reduce wrongness
So gradient descent is literally just the hot-and-cold game played across thousands of dials at once. You keep stepping toward "warmer" (lower loss) until you find a good spot.

Two key details the analogy also captures:

Learning rate = your step size. Too big and you overshoot the warm spot; too small and you crawl there painfully slowly.
Local minimum = getting "stuck" in a pretty warm spot near the door, never finding the warmest spot across the room.
And the tool that makes this practical — checking all 13,000 dial-directions at once to yell "warmer/colder" — is called backpropagation.

Per the Non-Technical Introduction to Deep Learning (Section 4): "That is exactly how a neural network learns."

Want me to go deeper on any part of this?

No, this sounds like a great overview for now. Next question, When teaching a machine how to recognize the difference between 2 things, why do we need to add a third option?

10:39 AM
That's a really interesting question! Based on the course reading, we don't actually need to add a third option — in fact, the reading uses adding a third class as a way to demonstrate a weakness, not a strength.

In the Teachable Machine exercise (Section 5), the reading suggests you try this on purpose as a way to learn from it:

"Add a third class with only 3 or 4 blurry examples. Watch it get confused."

The lesson from doing this is:

"A model is only as good as the examples you feed it."

The point isn't that a third class is necessary — it's that adding one with too few, poor-quality examples shows you how easily a model can break down.

The reading also suggests another revealing test: show the model something it was never trained on at all (like your face or a coffee mug). It will still confidently pick one of its trained answers — which ties into the big takeaway of Section 6:

"A confident answer is not the same as a correct answer."

So to directly answer your question — based on what's in the course materials, I can't find a reason why you'd need a third option. If your instructor has covered this in class with additional context, I'd recommend reaching out to Mallory Milstead (milsteam@faytechcc.edu) or Andrew Norris (norrisa@faytechcc.edu) for clarification!

Turn on web search in Search and tools menu. Otherwise, links provided may not be accurate or up to date.

I see. Final question, do you know anything about python notebooks, and the skills needed to use them?

10:42 AM
That's a great question, but unfortunately Python notebooks aren't covered in either the syllabus or the course reading I have access to!

For that, I'd recommend reaching out to your instructors directly:

Mallory Milstead — milsteam@faytechcc.edu
Andrew Norris — norrisa@faytechcc.edu
What I can tell you is that the course textbook — Deep Learning with Python, 3rd Edition by François Chollet and Matthew Watson — will likely cover practical tools like notebooks as part of the hands-on work. It might be worth checking there too!

Is there anything else about the syllabus or the Deep Learning reading I can help you with? 😊

Turn on web search in Search and tools menu. Otherwise, links provided may not be accurate or up to date.

No, I got everything I need for now. Thank you for your assistance :)

10:42 AM
You're welcome! Best of luck with CSC-114 — it sounds like a really exciting course! 😊 Don't hesitate to come back if you have more questions. Take care! 👋

