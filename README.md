# UE4NN
**Genetic algorithms neural network based on UE4's blueprints**

The relevant NN blueprints are located in NN folder. They are:

- Population
- Specie
- Brain
- Neuron
- Synapse
- Node

They're completely project-independent and you can safely use them to build your own ML project.

### Simulation

The simulation I've used to test NN classes is based on UE4's Advanced Vehicle template. Genetic algorithm uses distance driven and average distance from the driving line for reward (fitness) function, and collision detection capsule and current distance from the driving line as inputs. Experiment with that - the results can change drastically.

Simulation controls are:

- '1' and '2' changes time dilation, but I wouldn't recommend going to fast though
- 'R' resets the simulation and starts a new batch
- 'Tab' skips to the next specie in generation

Simulation results are saved each time the generation ends but before selection and mutation.

#### Got questions, suggestions etc?

Hit me up on Twitter @dunenkoff.