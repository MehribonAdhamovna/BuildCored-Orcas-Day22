# BuildCored-Orcas-Day22
CircuitWhisperer — BUILDCORED ORCAS Day 22

What it does. This project uses a local AI vision model called Moondream to analyze photos of circuit schematics, automatically identifying parts like resistors and capacitors. It then interprets how those parts are connected to explain the circuit's purpose and check for potential mistakes like missing grounds.

Hardware concept. The main concept is Schematic Literacy, which is the ability to translate visual symbols into functional electrical logic. By using AI to read these drawings, we can learn how standardized symbols represent real-world physical components and how signal flow is documented.

What I would do differently. Id improve the lighting and contrast of the physical drawings because the model struggles when the lines aren't perfectly dark and the paper is shadowed. I would also try Few-Shot Prompting which gives the AI a few examples of symbol and its component name inside the code to help it learn the specific drawing style and reduce wrong guesses.

Run it. python day22_starter.py
