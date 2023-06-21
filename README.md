# Experiments_using_Quantum_computers
exploring about quantum experiments using quantum gates and IBMQ

Quantum Mechanics happens in the Hilbert space while we humans think that we exist in
the three-dimensional Euclidean space (flat manifold) or may be in the relativistic
Minkowski manifold. Quantum computers allow us the ways and means of accessing the
quantum states of with tools to manipulate and operate on the quantum states. This is
something that was not available to students of physics before the advent of quantum
computing facilities offered in the cloud by various companies foremost of them being
IBM. In the present work various operators operating on single qubit and composite
systems are used to run experiments, superposition of quantum states, entanglement, Bell
states as well as quantum teleportation experiments.

QUANTUM STATES

In quantum physics the quantum states are the mathematical entity that gives an idea about
the probability distribution for the results of each possible measurement on a system. There
can be pure quantum states as well as mixed quantum states. It is generally denoted by the
symbol ‘ψ’. The pure quantum states are described vector elements of a vector space over
the field of scalars. This normed inner product space called the Hilbert space which is
complete, separable and has a mandatory positive scalar product.

EIGEN VALUES AND EIGEN VECTORS OF AN OPERATOR

A state vector |ψ > will be an eigen vector of an operator Ȃ if on action of the operator Ȃ
on the state |ψ > gives
Ȃ|𝜓 > = 𝑎|𝜓 > 
, where a is the eigen value of Ȃ and a complex number.
The best example for an eigen value problem is the action of unitary operator on the state
vector |𝜓 > .
Î|𝜓 > = |𝜓 > 
This means all the vectors present are the eigen vectors of Î with the eigen value as 1.

MACH-ZEHDNER INTERFEROMETER (MZI)

The interferometer refers to the family of techniques that use the principle of
superposition prominently to electromagnetic waves to create the phenomena called
interference. Generally, in the interferometer the incident beam is first divided using a
beam splitter to make coherent sources with definite phase difference and then the beams
that are divided are caused to interfere with each other later.

The quantum set up of MZI differs from the classical one in certain ways. The laser
source in classical MZI is now replaced by a single photon in the quantum mechanical
MZI. The photon being in the state of either |0⟩ or |1⟩. The half-silvered mirrors are
changed in beam splitters of equal probability of reflection and transmission. These beam
splitters are unitary transformations. The fully reflecting mirrors are removed in this
quantum mechanical set up. Phase shifters are used amongst the beam splitter to create
phase difference between the qubit interactions.

ENTANGLEMENT AND BELL STATES

The existence of entanglement property comes from the superposition only, when two or
more quantum system interact then the quantum states are characterized by correlation
between the quantum system, which can never be explained by any classical theory.
Entanglement has a significant impact on quantum information.

Bell states are a set of entangled states . The orthonormal Eigen basis for a twodimensional
Hilbert space is shown as
|0> , |1> 
Hence any two-dimensional state |𝜓> in the Hilbert space is represented as the linear
combination of the state |0> and |1> which is called as the computational basis. Hence
for a dual combined system HAB the tensor product can be obtained in terms of two similar
Hilbert space HA and HB, with four eigenstates of computational basis |00>, |01>,
|10> and |11>.

CONCEPT OF QUANTUM BITS

In digital computers running with a binary logic system a logic state can be either in 0 or in
1 state. In quantum mechanics however as a state of a system can be expressed as linear
superposition of other states. A system can have infinitely different quantum states.
Let us consider an atom which has two energy eigenstates, viz. ground state represented by
the state vector Ψ(ground) and excited state represented by Ψ(excited). The general state for the
two-level atom can be shown as a linear combination of the two provided eigen states as
shown under.
Ψ= Ψ(ground) + Ψ(excited)

GEOMETRICAL INTERPRETATION OF THE QUBIT: THE
BLOCH SPHERE

A qubit can be visualised by associating its states to the points on a geometrical sphere’s
surface. This sphere, known as Bloch sphere  has unit radius, and is so constructed that
its north pole and south pole represents the two computational basis states, viz. |0⟩ and |1⟩
respectively.

QUANTUM LOGIC GATES

For the processing of information using qubits, we use quantum versions of classical logic
gates.
Identity Gate(I), Pauli X Gate, Pauli Y Gate, Pauli Z Gate, Hadamard Gate(H), 
The Phase Gate P (𝝓), Physical Gates Ui, Measurement operation

TELEPORTATION

Teleportation is application of quantum entanglement that allows one (Alice) to send a
quantum state |𝜒>= 𝛼|0> + 𝛽|1> to another person (Bob). The novelty of this
procedure is that the quantum state itself is not sent using any tangible process. The only
piece of information sent in an usual sense is the result of some measurement made by
Alice that is communicated by her to Bob.The rest is explained in the codes.
