

## Important .gen compatibility note

The supplied binary `.gen` file is not a NAM JSON model. NeuralAmpModelerCore does not define a universal decoder for arbitrary `.gen` extensions. This project keeps the explicit rejection path rather than falsely reporting a successful load. To implement a real decoder, the generating application and its documented file format or redistributable SDK are required.
