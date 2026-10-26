# Unconventional Computing

How can physical, chemical and biological dynamics implement specified computations? Covers computing with living, chemical and bodily dynamics, including how inputs are encoded and results read out.

## What constitutes a computation

- **Computation and dynamical regime** - Langton studies information storage, transmission and modification near transitions in cellular-automaton behavior. The proposed link between computation and criticality is a hypothesis drawn from the studied rule families. [Langton 1990](<https://doi.org/10.1016/0167-2789(90)90064-V> "Computation at the edge of chaos: Phase transitions and emergent computation; Physica D").
- **Physical computation criteria** - Relates a physical system to an abstract computation through encoding, evolution and decoding. The proposed framework distinguishes performing a computation from observing dynamics that can be described mathematically. [Horsman et al. 2014](<https://arxiv.org/abs/1309.7979v3> "When does a physical system compute?; Proc. R. Soc. A").

## Molecular computation

- **DNA computation** - DNA strands encode candidate paths through a seven-node graph. Amplification and successive laboratory filters isolate a Hamiltonian path, visiting each node once. [Adleman 1994](<https://doi.org/10.1126/science.7973651> "Molecular Computation of Solutions to Combinatorial Problems; Science").
- **DNA associative memory** - DNA strand displacement implements a four-neuron Hopfield network that recalls stored patterns from incomplete inputs. Weights are trained in software, then encoded as molecular concentrations. [Qian et al. 2011](<https://www.qianlab.caltech.edu/nature10262.pdf> "Neural network computation with DNA strand displacement cascades; Nature").

## Physical and biological computations

- **Pask's electrochemical ear** - Cariani documents electrochemical devices whose growing conductive structures acquired sensitivity to sound or magnetic fields. A historical account of changing the sensor itself, not only adjusting a controller. [Cariani 1993](<https://doi.org/10.1002/sres.3850100305> "To evolve an ear. Epistemological implications of Gordon Pask&#x27;s electrochemical devices; Systems Research").
- **Slime-mould maze solving** - Physarum initially fills a small maze, then retracts into a short connection between two food sources. The assay demonstrates distributed path selection through growth and retraction. [Nakagaki et al. 2000](<https://doi.org/10.1038/35035159> "Maze-solving by an amoeboid organism; Nature"); [video](<https://www.nature.com/articles/35035159#Sec4>).
- **Physarum transport networks** - Slime mould connects food sites representing Tokyo-area cities. Its networks balance cost, transport efficiency and fault tolerance comparably to the railway; a flow-dependent tube model captures adaptation. [Tero et al. 2010](<https://doi.org/10.1126/science.1177894> "Rules for Biologically Inspired Adaptive Network Design; Science").
- **Soft-body computation** - A driven silicone arm provides nonlinear dynamics and memory for trained readouts. It emulates temporal systems better than the tested direct linear readout, but worse than an optimized software reservoir. [Nakajima et al. 2015](<https://pmc.ncbi.nlm.nih.gov/articles/PMC4444959/> "Information processing via physical soft body; Sci. Rep.").
- **Iontronic memory** - Salt redistribution gives aqueous channels fading conductance memory. Tests at three channel lengths support retention time proportional to length squared. Software classifiers use measured pulse responses to recognize digits. [Kamsma et al. 2024](<https://pmc.ncbi.nlm.nih.gov/articles/PMC11067030/> "Brain-inspired computing with fluidic iontronic nanochannels; PNAS").

## Trainable physical systems

- **Physics-aware training** - Physical forward passes and gradients from a differentiable digital model train optical, electronic and mechanical systems for classification. Measuring hardware during training reduces errors from simulation mismatch. [Wright et al. 2022](<https://pmc.ncbi.nlm.nih.gov/articles/PMC8791835/> "Deep physical neural networks trained with backpropagation; Nature").
- **Contrastive local learning** - Twin transistor networks learn XOR and nonlinear regression by locally comparing free and target-clamped voltages. Circuit dynamics update parameters without a digital model; training inputs and targets are externally supplied. [Dillavou et al. 2024](<https://pmc.ncbi.nlm.nih.gov/articles/PMC11252732/> "Machine learning without a processor: Emergent learning in a nonlinear analog network; PNAS").
- **Physical-network training** - Training can optimize a digital surrogate, combine measured hardware outputs with digital gradients, or update parameters through physical dynamics. Model accuracy, measurement access and drift constrain the approaches a substrate supports. [Momeni et al. 2025](<https://arxiv.org/abs/2406.03372v1> "Training of physical neural networks; Nature").

## Open questions

- How much of a demonstrated computation is performed by the substrate versus preprocessing, readout or external feedback?
- Does performance persist after accounting for preparation time, calibration, energy, error and repeated use?

## Related topics

- [Hyperorganism](https://hyperorganism.github.io/)
- [Basal cognition](https://hyperorganism.github.io/basal-cognition/) - A computational use of a substrate does not settle its own behavioral capacities.
- [Embodiment](https://hyperorganism.github.io/embodiment/) - Body dynamics can contribute to computation and control.
- [Digital life](https://hyperorganism.github.io/digital-life/) - Reproducing computational systems pose a different question from using a substrate to calculate.
- [Biohybrid Systems](https://hyperorganism.github.io/biohybrid-systems/)
