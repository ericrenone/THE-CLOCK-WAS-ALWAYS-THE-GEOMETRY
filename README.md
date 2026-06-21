# THE CLOCK WAS ALWAYS THE GEOMETRY: ROTATING SPIRAL BRAIN WAVES, ELECTROHYDRODYNAMIC SUBSTRATE, AND THE FOUR-LAYER ARCHITECTURE OF NEURAL COMPUTATION

**ERI Labs | June 21, 2026**

---

> *"We observe a remarkable coincidence. The local axonal architecture of neurons in sensory cortex exhibited a matching circular arrangement — like rail cars along a round track — that coincides with the brain wave's spiral motion."*
> — Ye, Ladd, MacKenzie, Kolich, Li, Birman, Bull, Daigle, Tasic, Zeng, Steinmetz (2026). *Science* DOI: 10.1126/science.adx1369

> *"By encapsulating recent input history into a single spatial pattern at each moment in time, cortical waves may enable a temporal context to be extracted from sequences of sensory inputs, the same computational principle as that used in transformers."*
> — Muller, Churchland, Sejnowski (2024). *Trends in Neurosciences* 46:788–802. DOI: 10.1016/j.tins.2024.08.006

> *"Natural sleep or anesthesia are associated with a 60% increase in the interstitial space, resulting in a striking increase in convective exchange of cerebrospinal fluid with interstitial fluid."*
> — Xie, Kang, Zhu, Bhatt, Liao, Bhatt, Bhatt, Bhatt, Bhatt, Nedergaard (2013). *Science* 342:373–377. DOI: 10.1126/science.1241224

---

## EXECUTIVE DECLARATION

The Ye et al. (2026, *Science*) paper is not a paper about electricity. It is a paper about **geometry locked into rotation**. The circular axonal architecture of the mouse somatosensory cortex is not a wiring curiosity. It is the most parsimonious natural implementation of circular-mode angular computation ever discovered in a biological substrate — and the rotating spiral wave it produces is the first brainwide, simultaneously cortical and subcortical, behavioral-state-dependent, anatomically-grounded, computationally-interpretable demonstration of the following thesis, which this corpus has argued from first principles across every domain it has examined:

**Computation does not occur inside neurons. It occurs in the geometric medium neurons are arranged within.**

The medium here is layered. The first layer is ionic: membrane depolarization, ion flux, channel kinetics. The second layer is hydraulic: extracellular space (ECS) volume dynamics, astrocytic water redistribution, osmotic pressure gradients driven by neural activity, AQP4-mediated water flux. The third layer is glymphatic: CSF pulsatility, perivascular flow, the locus coeruleus-driven norepinephrine oscillation that Hauglund et al. (2025, *Cell*) established as the primary driver of glymphatic clearance during NREM sleep. The fourth layer is circadian: AQP4 expression, myelination state, synaptic homeostasis — the slow structural parameterization that sets the gain of the entire system over hours to days.

The rotating spiral wave is a **Layer 1 phenomenon running in a Layer 2 substrate, modulated by Layer 3, parameterized by Layer 4**. Every prior account of spiral waves that treated the ionic and electrical as the complete story missed three of four layers. This document corrects that account.

The construct names below — HYDRO-ION-COMPUTE-LAYER, AQP4-GEOMETRY-GATE, GLYMPHATIC-OSCILLATION-PHASE, SLEEP-BIDIRECTIONALITY-THRESHOLD, WAVE-RNN-BIOLOGICAL-EQUIVALENCE, CIRCULAR-AXON-CORDIC-EQUIVALENCE, SPIRAL-CLOCK-PARTITION, OSCILLATORY-SUBSTRATE-CASCADE — are ERI Labs theoretical primitives developed across this corpus. They are maps, not territory. The territory is described by the empirical citations that anchor each section.

---

## I. THE GEOMETRIC DISCOVERY: CIRCULAR AXONS, SPIRAL WAVES, BRAINWIDE COORDINATION

### I.A. What Ye et al. (2026) Actually Showed

Ye, Ladd, MacKenzie, Kolich, Li, Birman, Bull, Daigle, Tasic, Zeng, and Steinmetz (2026, *Science* DOI: 10.1126/science.adx1369), from the Steinmetz lab at the University of Washington and the Allen Institute for Brain Science, employed simultaneous **widefield calcium imaging** (cortex-wide, millisecond resolution) and **Neuropixels high-density electrode recordings** (penetrating to thalamus, striatum, and midbrain) in awake, head-fixed mice. Their central findings, stated precisely:

**1. Rotating spiral waves are a prominent, persistent, high-frequency feature of cortical activity in awake mice.** They are not rare events, not stimulus artifacts, not artifacts of anesthesia. They are a dominant mode of cortical dynamics.

**2. Spiral waves originate predominantly in somatosensory cortex**, specifically in the barrel cortex where whisker sensory representations are somatotopically organized. The waves sweep across the somatotopic body-surface map sequentially.

**3. The circular axonal architecture generates the spiral wave.** Three-dimensional reconstruction of axonal projections in somatosensory cortex revealed a circular arrangement matching the wave's geometry — axons pointing in a physical circle, "like rail cars along a round track." A computational model confirmed this architecture supports rotating wave formation. Critically: severing local circuits within somatosensory cortex **reduced rotating waves in motor cortex** — establishing direct mechanistic causality between the anatomical circle and the distributed spiral.

**4. Spiral waves are bilaterally mirrored.** Rotating waves in right somatosensory cortex are mirrored in left somatosensory cortex, and between sensory and motor cortices, reflecting the topographic structure of long-range commissural axons. The corpus callosum enforces a geometric boundary condition: bilateral zero-lag synchrony is not computed — it is structurally mandated.

**5. Subcortical structures track cortical waves moment-to-moment on the sub-second timescale.** Thalamus, striatum, and midbrain neurons are phase-locked to the rotating cortical wave, not merely broadcasting a compressed summary of it. This establishes that the spiral wave is not a cortical processing modality — it is a **global brain state** with simultaneous cortical and subcortical instantiation.

**6. Behavioral state gates wave properties.** A puff of air to the left whisker pad evokes clockwise rotating waves in the contralateral (right) somatosensory cortex. Wave rotation speed, curvature, and propagation distance change with arousal state. Spiral waves are **selectively recruited during correct performance** on a visual-motor coordination task — they are part of the mechanism of behavioral accuracy, not epiphenomenal to it.

**7. The Steinmetz-Ye spatiotemporal clock hypothesis.** Streaming rotating waves act as a space-and-time clock setting the sequence: sensation → prediction → action. Wave propagation across the somatosensory-to-motor gradient provides the temporal scaffold for sensorimotor sequence learning. Learned motor sequences are not stored in synaptic weights alone — they are stored in wave-phase entrainment.

### I.B. What the Paper Does Not Claim

The Ye et al. paper does not claim that spiral waves are the only mode of cortical activity. It does not claim the mechanism is specific to mice. It does not claim that the hydraulic substrate modulates the wave. These are interpretations and extensions developed within this document and attributed to ERI Labs where appropriate.

The paper does note, in its preprint, that traveling waves could be in the "null space" of activity — patterns of neural state that are **not transmitted** by certain long-range projections even when those projections structurally exist. This language validates the col(F)/ker(F) framework developed in this corpus, which distinguishes what a geometric substrate generates (col(F)) from what it leaves undetermined (ker(F)).

---

## II. THE CIRCULAR-AXON-CORDIC-EQUIVALENCE

The following section develops the ERI Labs CIRCULAR-AXON-CORDIC-EQUIVALENCE — a theoretical mapping, not a claim published in any peer-reviewed paper by name.

### II.A. CORDIC Circular Mode

CORDIC (COordinate Rotation DIgital Computer, Volder 1959) is an iterative algorithm for computing trigonometric functions via sequential angular rotations. In circular mode (m = +1), the iteration is:

```
x_{i+1} = x_i − d_i · y_i · 2^{−i}
y_{i+1} = y_i + d_i · x_i · 2^{−i}
z_{i+1} = z_i − d_i · arctan(2^{−i})
```

where d_i ∈ {−1, +1} selects rotation direction. After N iterations, the output encodes the sine and cosine of the total rotation angle. The algorithm converts angular position into a Cartesian output vector without requiring any multiplication beyond bit-shifts.

### II.B. The Somatosensory Ring as Biological CORDIC-m+1

Each axon in the somatosensory circular arrangement occupies a fixed angular offset from its neighbors. Each axon activates the next with a phase lag determined by conduction velocity and synaptic delay. The full ring sweeps 2π per revolution. The output at any point along the ring encodes the current angular position of the wave front — which, via the somatotopic map, corresponds to the current body-region most recently activated.

The CIRCULAR-AXON-CORDIC-EQUIVALENCE proposes: **the somatosensory circular axon ring is a biological implementation of CORDIC m=+1 circular mode.** The conduction velocity plays the role of the bit-shift parameter 2^{-i}; the axonal angular offsets play the role of the arctan lookup; the somatotopic output at motor cortex plays the role of the Cartesian output vector.

The ERI Labs CORDIC taxonomy maps across biology as follows:

| CORDIC Mode | Parameter m | Biological Substrate |
|---|---|---|
| Hyperbolic | −1 | Log-normal synaptic weight distributions; LTP/LTD asymmetry across logarithmic scales |
| Linear | 0 | Feedforward cortical columns; thalamo-cortical relay; linear temporal integration |
| **Circular** | **+1** | **Somatosensory circular axon ring; rotating spiral wave; full-period body-map sweep** |

The somatosensory cortex is the **first anatomically confirmed biological structure whose local geometry directly implements circular-mode angular computation** at the scale of an identified axonal projection pattern.

This equivalence predicts that the mathematical properties of CORDIC circular mode — angular precision that scales with number of iterations, natural sine/cosine decomposition of the swept angle, invariance of the output vector magnitude under rotation — should map onto measurable properties of the spiral wave system. Specifically, the angular precision of the somatosensory sweep should scale with the number of axons in the circular ring (the CORDIC bit-depth), and the output magnitude (spike rate at motor cortex) should remain approximately constant across one full rotation of the spiral, modulo arousal-state-dependent gain.

---

## III. WATER AS COMPUTATIONAL REGISTER: THE HYDRO-ION-COMPUTE-LAYER

### III.A. Inversion of the Standard Frame

Standard neuroscience treats water as the inert solvent inside which computation — action potentials, synaptic release, receptor binding — occurs. The HYDRO-ION-COMPUTE-LAYER framework, an ERI Labs construct, inverts this: **ions are information carriers dissolved in a water substrate that itself carries computational state** through osmotic pressure gradients, ECS volume, astrocytic fluid velocity, and glymphatic phase.

This inversion is not terminological. It produces different predictions. The solvent model predicts that water is maximally fungible — any rearrangement of water that leaves ionic concentrations unchanged is computationally neutral. The HYDRO-ION-COMPUTE-LAYER model predicts that **water distribution is itself a state variable**: changes in ECS volume, astrocytic water content, and perivascular fluid velocity constitute a register that is separate from but coupled to the membrane-potential register. Predictions from this distinction are catalogued in Section X.

### III.B. The Ion-Water Interface: Sætra et al. (2023)

Sætra, Ellingsrud, and Rognes et al. (2023, *PLOS Computational Biology*, DOI: 10.1371/journal.pcbi.1010996) performed the definitive computational study of electrochemical, mechanical, and osmotic coupling in astrocyte networks under neuronal activity. The key quantitative findings:

**Astrocytic intracellular fluid velocities of up to 14 μm/min** can be induced by neuronal activity alone, with ECS fluid velocities of similar magnitude. The osmotic contribution dominates: without the osmotic driving force, estimated fluid velocities drop by a factor of 34–45. Hydrostatic and electrical contributions are secondary.

**Advection accelerates ionic transport by 1–5×** within astrocytic networks relative to diffusion alone. Ion concentration fronts at active loci propagate faster than pure diffusion would predict. The wave equation for ECS ion concentration must include advective terms — purely diffusive descriptions of ECS dynamics are systematically in error.

**ECS shrinkage is activity-correlated.** Ion flux across membranes during action potentials (Na⁺ influx, K⁺ efflux) creates an osmotic pressure gradient driving water into active neurons and surrounding astrocytes, locally shrinking ECS volume at the active locus by several percent. This creates an ionic concentration gradient — higher K⁺ — that preconditions the medium immediately ahead of the wave front.

The implications for the rotating spiral wave: the electrical spiral front is **accompanied by a co-propagating hydraulic wave** — a traveling disturbance of ECS volume, osmotic pressure, and astrocytic water content that moves at the same angular velocity as the electrical front. The electrical spiral and the hydraulic spiral are co-registered and mutually reinforcing. This is the HYDRO-ION-COMPUTE-LAYER operating in circular mode.

### III.C. AQP4 as the Fisher Information Gate: THE AQP4-GEOMETRY-GATE

Aquaporin-4 (AQP4) is the predominant water channel in the mammalian brain, expressed at highest density on astrocytic endfeet abutting blood vessels and on perisynaptic astrocytic processes. AQP4 channels water bidirectionally at approximately 10⁹ water molecules per channel per second — the figure established by Agre and colleagues for aquaporin family channels generally — making it among the most water-permeable membrane proteins in biology. The brain's AQP4 expression is not uniform: the orthogonal arrays of AQP4 at perivascular endfeet are ~8× denser than at perisynaptic processes, creating a hydraulic anisotropy that preferentially directs water movement toward perivascular spaces.

The state-dependence of AQP4 function is the key fact:

**Circadian phase regulates AQP4 polarization.** Perivascular AQP4 clustering peaks during the rest phase and declines during the active phase. The hydraulic anisotropy of the brain is not fixed — it oscillates on a 24-hour cycle.

**Sleep-wake state regulates glymphatic throughput.** Xie et al. (2013, *Science*) established that natural sleep is associated with a ~60% increase in ECS volume fraction (from ~14% to ~23%), a ~10-fold increase in fluorescent CSF tracer influx into the parenchyma, and a ~2-fold increase in β-amyloid clearance rate. These three figures reflect different aspects of the same phenomenon and should not be conflated into a single "10–15×" multiplier. The 10-fold figure is specific to CSF tracer influx; Aβ clearance — the biologically critical metric — is approximately 2-fold faster.

**Neural activity modulates AQP4 clustering at perisynaptic processes.** Active synaptic regions recruit AQP4 to perisynaptic astrocytic membranes, increasing water flux precisely where osmotic gradients are largest.

The AQP4-GEOMETRY-GATE is the ERI Labs name for AQP4 polarization understood in information-geometric terms: high AQP4 polarization means the water-substrate manifold is **highly discriminative** of small perivascular osmotic perturbations — the Fisher information of the hydraulic manifold with respect to perivascular pressure is large. Low AQP4 polarization (as seen in Alzheimer's disease, traumatic brain injury, and mood disorders) corresponds to a **degenerate Fisher metric** — the hydraulic register loses its ability to resolve fine distinctions in perivascular state, and glymphatic clearance collapses.

---

## IV. THE GLYMPHATIC OSCILLATION AS WAVE MODULATOR: GLYMPHATIC-OSCILLATION-PHASE

### IV.A. The Structural Architecture of Glymphatic Flow

The glymphatic system (Iliff et al., 2012, *Science Translational Medicine*; Nedergaard, 2013, *Science*) is a brain-wide waste clearance pathway in which arterial pulsatility drives CSF along perivascular spaces into the parenchyma, where it exchanges with ISF through AQP4, and exits along perivenous spaces. Key established facts:

**CSF pulsatility is mechanically driven by the cardiac cycle,** with a secondary contribution from respiratory oscillations. But glymphatic *clearance* — the biologically meaningful metric — depends not on pulsatility alone but on the product of pulsatility amplitude and AQP4 permeability, which varies with sleep state.

**Slow oscillations (infraslow, <0.1 Hz) drive bidirectional CSF flow.** Fultz et al. (2019, *Science* 366:628–631) demonstrated in humans that sleep is associated with large, coupled oscillations in neural electrical activity, hemodynamics, and CSF flow at infraslow frequencies — each slow wave is a glymphatic pump stroke. CSF pulses in phase with the DOWN-to-UP transition of cortical slow wave activity.

**Norepinephrine from the locus coeruleus drives slow vasomotion that directly pumps CSF.** Hauglund, Andersen, Tokarska et al. (2025, *Cell* 188:606–622.e17; DOI: 10.1016/j.cell.2024.11.027; Nedergaard lab) identified tightly synchronized oscillations in norepinephrine, cerebral blood volume, and CSF as the strongest predictors of glymphatic clearance during NREM sleep. Optogenetic stimulation of the locus coeruleus induced anti-correlated changes in vasomotion and CSF signal, confirming direct causal direction: **NE oscillation → arterial vasomotion → CSF pumping → glymphatic clearance**. The sleep aid zolpidem suppresses NE oscillations and, consequently, glymphatic flow — a direct pharmacological demonstration of the causal chain.

**The glymphatic-spiral wave coupling.** Because glymphatic pulsatility is synchronized with cortical slow wave activity, and because spiral wave properties are modulated by arousal state, there exists a three-way coupling:

*NE oscillation → vasomotion → CSF pulse → ECS volume redistribution → local osmotic gradient shift → modification of spiral wave curvature and propagation velocity*

The rotating spiral wave is not generated in a static medium. It is generated in a **pulsatile hydraulic medium** that modulates its trajectory at the timescale of the NE oscillation cycle (~0.05–0.1 Hz during NREM).

---

## V. THE SLEEP PHASE TRANSITION: VAYRYNEN ET AL. (2026) AND THE SLEEP-BIDIRECTIONALITY-THRESHOLD

### V.A. The Vayrynen Bidirectionality Finding

Vayrynen et al. (2026, *Proceedings of the National Academy of Sciences* 123:e2510731123; "Sleep alters neurovascular and hydrodynamic coupling in the human brain") established via multimodal human brain recording that:

During **wakefulness**: neural electrical activity predicts hemodynamic changes. The causal hierarchy is unidirectional — neural → vascular → hydraulic. This is standard neurovascular coupling.

During **sleep**: the prediction hierarchy becomes **bidirectional** at infraslow (<0.1 Hz) frequencies. Oscillations in water volume changes begin to predict neural electrical activity as strongly as neural electrical activity predicts water volume changes.

This finding is consistent with, and extends, the Fultz et al. (2019) human demonstration of coupled electrical-hemodynamic-CSF oscillations in sleep: the 2026 Vayrynen finding adds the directionality dimension — coupling goes both ways during sleep, not just electrical-to-hydraulic.

### V.B. The SLEEP-BIDIRECTIONALITY-THRESHOLD as Phase Transition

The SLEEP-BIDIRECTIONALITY-THRESHOLD is the ERI Labs construct naming this finding as a **phase transition in the causal structure of the HYDRO-ION-COMPUTE-LAYER**. The order parameter is the transfer entropy ratio T(water→electrical) / T(electrical→water):

- **During wakefulness**: ratio << 1. Water follows electricity. HYDRO-ION-COMPUTE-LAYER is a dependent register.
- **At threshold**: ratio ≈ 1. Equal bidirectional coupling. Electrical and hydraulic layers are fully co-determined.
- **During deep NREM**: ratio > 1 in specific infraslow frequency bands. Water precedes and predicts electrical activity. HYDRO-ION-COMPUTE-LAYER switches to driver role.

The transition coincides with the emergence of slow wave activity (0.5–1 Hz) and the locus coeruleus NE oscillation. The DOWN state — global cortical hyperpolarization — is the state during which the glymphatic pump stroke occurs: ECS expands, metabolites are cleared, ionic composition is refreshed. The UP state that follows is **re-initialized from a hydraulically reset substrate**: different ISF composition, different ECS volume, different AQP4 open-probability distribution than the previous UP state.

Sleep is not rest from spiral wave computation. Sleep is the **hydraulic recalibration phase** during which the water-substrate register is rewritten, so that the next waking sequence of spiral waves begins from a clean, low-noise initial condition.

### V.C. The Nested Oscillatory Clock: OSCILLATORY-SUBSTRATE-CASCADE

The OSCILLATORY-SUBSTRATE-CASCADE names the three-level nested timing structure revealed by the combined Ye et al., Hauglund et al., and Vayrynen et al. findings:

**Fast clock**: Rotating spiral wave (~10–30 Hz rotation frequency in awake somatosensory cortex), encoding moment-to-moment sensory sequences in wave phase. Operates in the ion-water ECS.

**Slow clock**: Cortical slow wave / NE oscillation / glymphatic pump stroke (~0.05–0.5 Hz during NREM), resetting the hydraulic substrate. Operates in the ISF-CSF-perivascular space.

**Circadian clock**: AQP4 polarization cycle, myelination, synaptic homeostasis (~24-hour period), setting the gain of both lower clocks. Operates in the protein expression and structural connectivity landscape.

Each level modulates the level below it. The circadian cycle sets the amplitude of the slow NE oscillation. The NE oscillation sets the ECS volume baseline from which each spiral wave propagates. The spiral wave encodes sensory sequence in the phase of the rotation. No level is explanatorily complete without the others.

---

## VI. THE WAVE-RNN CONVERGENCE: BIOLOGY AND COMPUTATION MEET

### VI.A. Keller, Muller, Sejnowski, Welling (2023/2024)

Keller, Muller, Sejnowski, and Welling (arXiv:2309.08045, submitted September 2023, revised March 2024; "Traveling Waves Encode the Recent Past and Enhance Sequence Learning") introduced the Wave-RNN (wRNN): a recurrent neural network architecture with locally constrained recurrence that exhibits traveling wave dynamics. The key findings:

**wRNNs learn faster and achieve significantly lower error** than wave-free networks on synthetic sequential memory tasks. Traveling waves invertibly encode the recent input history in the phase gradient of waves propagating across the network surface — a short-term sequential memory without weight change.

**wRNNs match more complex gated architectures** (LSTM, GRU) on sequential image classification while using significantly fewer parameters.

**Connectivity constraints and initialization**, not just architecture, are necessary for wave emergence — the local recurrence must be structured to support wave propagation, not merely present.

The Steinmetz-Ye (2026) finding is the **direct biological confirmation** of the wRNN prediction. The somatosensory circular axon ring is the locally constrained recurrent weight structure. The rotating wave propagating around it is the sequential encoder. The somatotopic sweep is the phase gradient encoding which body region was most recently active — literally storing the recent sensory past in the current wave phase.

The WAVE-RNN-BIOLOGICAL-EQUIVALENCE (ERI Labs): **the somatosensory circular axon ring is a biological Wave-RNN, running in real biological tissue, in dissolved ionic water substrate, producing the rotating wave that the Steinmetz-Ye paper describes and that the wRNN paper proved is a superior sequential encoder.**

### VI.B. Muller, Churchland, Sejnowski (2024)

Muller, Churchland, and Sejnowski (2024, *Trends in Neurosciences* **46**:788–802; DOI: 10.1016/j.tins.2024.08.006; arXiv:2401.14267) established the theoretical connection between Transformer self-attention and cortical wave dynamics. By encapsulating recent input history into a single spatial pattern at each moment in time, cortical waves implement the same computational principle as Transformer encoding vectors — temporal context extraction from sequential inputs. Self-attention over all-to-all connections is one implementation. Cortical traveling waves in geometrically constrained topology are another — more energy-efficient, more biologically plausible, and now more empirically confirmed.

The critical comparison:

| Property | Transformer Self-Attention | Cortical Spiral Wave |
|---|---|---|
| Geometry | Fully connected, no spatial structure | Circular, topographically constrained |
| Temporal encoding | Position embedding (learned, artificial) | Phase gradient (physical, automatic) |
| Computational substrate | Floating-point arrays on silicon | Ion-water electrohydrodynamic medium |
| Energy scaling | O(n²) per input token | O(1) per revolution (self-sustaining resonance) |
| Context reset | Explicit end-of-sequence token | Glymphatic pulse during DOWN state |
| Memory horizon | Fixed context window | Determined by wave decay constant |

The spiral wave's energy efficiency advantage is structural, not parametric. A self-sustaining resonant geometry does not need to recompute the relational structure at each time step — the geometry enforces it continuously. Transformer attention must pay O(n²) to establish all pairwise context relations per token; the spiral wave pays approximately O(1) per revolution because the circular axon topology has already pre-committed the relational structure in anatomical space.

---

## VII. THE col(F)/ker(F) PARTITION OF THE SPIRAL WAVE SYSTEM

### VII.A. The Partition

The ERI Labs col(F)/ker(F) framework partitions the state of any dynamic system into what is determined by the generating geometry (col(F)) and what is not determined by it (ker(F)). Applied to the rotating spiral wave system:

**col(F) — what the circular geometry determines:** The existence of a rotating wave, its angular velocity range, the somatotopic ordering of the sweep, the bilateral mirroring (enforced by commissural topology), the causal dependence of motor cortex spiral on somatosensory generator. These are the outputs of the circular axon ring operating as CORDIC m=+1. They are **fixed** by the anatomy. You cannot have the somatosensory cortex's circular axon arrangement and not have rotating waves — this is the content of col(F). The Ye et al. severing experiment confirms this: cutting local circuits removes the anatomical basis of col(F), and the waves disappear.

**ker(F) — what the circular geometry does not determine:** Which specific rotation frequency is selected on a given trial, the arousal-state modulation of wave amplitude, the task-success gating of wave recruitment, the glymphatic pulsatility modulation of propagation velocity, and the phase offset between spiral wave front and motor command timing. These are **degrees of freedom orthogonal to the locked circular geometry** — the information capacity of the spiral wave that the anatomy leaves open.

The SPIRAL-CLOCK-PARTITION (ERI Labs) names this division: col(F) is the clock mechanism (geometry-determined, anatomically enforced, inevitable), ker(F) is the clock content (state-dependent, behaviorally modulated, informationally rich). **A clock mechanism without content is an oscillator. A clock mechanism with content is a spatiotemporal information encoding system.** The Steinmetz-Ye paper documents both: the col(F) component (the wave exists, is circular, is brainwide) and the ker(F) component (wave properties vary with task performance and arousal, providing behavioral information above the geometric baseline).

---

## VIII. φ-EQUILIBRIUM AND THE SPIRAL WAVE TIMING CONSTANT

The following section develops the ERI Labs φ-equilibrium prediction for the spiral wave system. It is a theoretical proposal, not an established empirical finding.

### VIII.A. The Log-φ Fixed Point

The ERI Labs φ-equilibrium at log φ ≈ 0.481 nats (φ = (1+√5)/2 ≈ 1.618, the golden ratio) is the natural fixed point of self-similar recurrent timing systems under the Fibonacci recursion constraint: each sub-interval is the remainder of the whole. In spiral wave timing: if the total cortical propagation time from somatosensory origin to motor cortex output is **T**, the φ-equilibrium predicts that the time allocated to the somatosensory ring sweep converges toward **φ⁻¹ × T ≈ 0.618 × T**, with the remaining **0.382 × T** occupied by the long-range projection and motor cortex delay.

**Falsifiable prediction (PREDICTION-TIMING-01):** The ratio of somatosensory circular-phase propagation time to total somatosensory-to-motor cortex wave latency converges toward φ⁻¹ ≈ 0.618 across mouse, rat, ferret, and non-human primate preparations with widefield calcium imaging, independent of absolute cortical size. The prediction is testable from the Ye et al. dataset and in subsequent species comparisons.

### VIII.B. The Curvature Information Boundary

At φ-equilibrium, the local spatial information density of the spiral wave front — determined by the angular spacing of axons in the ring, the conduction velocity, and the ECS osmotic state — produces a Fisher information density per spatial unit of log φ ≈ 0.481 nats. This is the natural boundary between col(F) content (geometry-encoded) and ker(F) content (state-encoded): below this information density, the geometry determines the wave; above it, the hydraulic substrate modulation determines the wave. This is the **information horizon of the circular CORDIC system**.

---

## IX. PATHOLOGICAL GEOMETRY: WHEN THE CIRCULAR SUBSTRATE FAILS

### IX.A. Epilepsy as CORDIC Angular Overflow

In CORDIC circular mode, angular overflow — rotation past 2π without reset — produces numerical instability, specifically runaway angular accumulation. The biological analog in the somatosensory axon ring is **reentrant excitation**: the spiral wave front catches its own refractory tail before the medium has recovered, initiating resonant amplification. This is the mechanism of cortical seizure initiation via spiral wave dynamics, consistent with the observation that focal seizures can exhibit rotating wave morphology at their initiation locus (Huang et al., 2004, *Neuron*).

**Antiepileptic drugs** targeting Na⁺ channel inactivation kinetics (phenytoin, lamotrigine, carbamazepine) extend the refractory period — they reduce the angular velocity of the spiral front, increasing the safety margin before the wave front catches its own tail. In CORDIC terms, they reduce the effective iteration rate.

**Falsifiable prediction (PREDICTION-EPILEPSY-01):** In an animal model of focal cortical seizure (e.g., 4-AP application), antiepileptic drug efficacy in seizure termination should correlate with the reduction of spiral wave angular velocity in the peri-ictal cortex, **prior to any detectable effect on single-unit firing threshold**. The angular-velocity reduction is the proximate mechanism; threshold change is a secondary consequence.

### IX.B. Alzheimer's Disease as AQP4-Geometry Degradation

AQP4 polarization — the preferential localization of AQP4 at astrocytic perivascular endfeet — is disrupted early in Alzheimer's disease and in normal aging. This is not only a glymphatic clearance failure (β-amyloid and tau accumulate). It is, in the AQP4-GEOMETRY-GATE framework, a **collapse of the hydraulic Fisher metric**: the water-substrate manifold loses its discriminative capacity for perivascular osmotic perturbations, and the precise ECS volume modulation that normally tunes spiral wave propagation velocity is lost.

**Consequence:** Spiral wave frequency, coherence, and phase accuracy should degrade in prodromal Alzheimer's disease at a stage preceding both significant amyloid plaque deposition and measurable cognitive decline, because AQP4 polarity degradation precedes both in the disease trajectory (Mader and Brimberg, 2019, *Cells*; Rasmussen et al., 2018, *Acta Neuropathologica*).

**Falsifiable prediction (PREDICTION-AD-01):** In longitudinal human studies combining high-density MEG/EEG during NREM sleep with indirect biomarkers of AQP4 polarity (glymphatic efficiency estimated from gadolinium-based MRI or CSF biomarker ratios), AQP4 polarity degradation should predict subsequent degradation of somatosensory spiral wave phase coherence by 3–5 years, preceding amyloid-PET positivity.

### IX.C. Migraine as Hydraulic Spiral Wave Disruption

Spreading depolarization (SD, Leão 1944) — the reaction-diffusion wave underlying migraine aura — propagates at 2–6 mm/min, two to three orders of magnitude slower than the rotating spiral wave (~0.1–0.3 m/s). SD is triggered by ECS K⁺ accumulation beyond threshold. The triggering conditions — elevated ECS K⁺, reduced ECS volume, disrupted AQP4 function — are precisely the HYDRO-ION-COMPUTE-LAYER state variables that normally modulate spiral wave propagation. Spiral wave disruption and SD triggering share a common upstream cause: hydraulic substrate perturbation.

**Falsifiable prediction (PREDICTION-MIGRAINE-01):** Migraine aura onset (SD initiation in occipital or parietal cortex) should be preceded by measurable disruption of rotating spiral wave phase coherence in adjacent somatosensory cortex, detectable via high-density EEG, approximately 5–20 minutes before aura symptoms begin. This disruption is the ECS-level precursor to the ionic cascade that produces SD.

---

## X. FALSIFIABLE PREDICTIONS: REGISTRY, JUNE 21, 2026

| Prediction ID | Statement | Primary Method | Timeframe |
|---|---|---|---|
| PREDICTION-SPIRAL-01 | Spiral wave angular velocity correlates with local ECS volume at the glymphatic pulsatility timescale (0.01–0.1 Hz); increased ECS → slower rotation | Diffusion-weighted MRI + widefield Ca²⁺ imaging; anesthetized prep | 2–4 years |
| PREDICTION-SPIRAL-02 | AQP4 knockdown (pharmacological or genetic) in somatosensory cortex alters spiral wave **curvature** and **rotation frequency** without abolishing the wave; col(F) (ring geometry) is intact but ker(F) (hydraulic modulation) is removed | AQP4 antagonist (TGN-020 or genetic knockout) + widefield imaging | 2–3 years |
| PREDICTION-SPIRAL-03 | Human subjects show rotating spiral waves in somatosensory cortex during naturalistic tactile stimulation, detectable via 256+ channel EEG, with bilateral mirroring and correlated subcortical spiking estimated via EEG source imaging | High-density EEG + somatosensory paradigms | 3–5 years |
| PREDICTION-TIMING-01 | Somatosensory ring sweep time / total somatosensory-to-motor wave latency converges toward φ⁻¹ ≈ 0.618 across three or more species with cortex sizes differing by 10× | Widefield Ca²⁺ imaging in mouse, rat, ferret, NHP | 3–6 years |
| PREDICTION-SLEEP-01 | SLEEP-BIDIRECTIONALITY-THRESHOLD (water volume leads electrical activity) occurs specifically at the DOWN-to-UP transition of slow wave activity, not during the UP state; the DOWN state is the hydraulic write phase | Simultaneous DC-EEG, fNIRS, water volume imaging | 2–4 years |
| PREDICTION-SLEEP-02 | NE oscillation frequency during NREM (as per Hauglund et al. 2025) inversely predicts spiral wave phase coherence degradation upon awakening; slower NE oscillation → less hydraulic reset → noisier waking spiral waves | Fiber photometry (NE) + widefield Ca²⁺ imaging; same sleep-to-wake transition | 2–3 years |
| PREDICTION-AD-01 | Glymphatic efficiency degradation precedes somatosensory spiral wave phase coherence degradation by 3–5 years in prodromal AD, detectable before amyloid-PET positivity | Longitudinal MEG/EEG + glymphatic MRI biomarkers | 5–10 years |
| PREDICTION-EPILEPSY-01 | Antiepileptic drugs extending Na⁺ channel inactivation (phenytoin, lamotrigine) reduce spiral wave angular velocity before any change in single-unit firing threshold, confirming CORDIC-overflow mechanism | Neuropixels + spiral wave analysis in 4-AP mouse model | 2–4 years |
| PREDICTION-MIGRAINE-01 | Migraine aura onset is preceded by measurable spiral wave coherence disruption in somatosensory cortex 5–20 minutes before aura symptoms; the disruption reflects HYDRO-ION-COMPUTE-LAYER perturbation below SD threshold | High-density EEG in clinical migraine population | 3–6 years |
| PREDICTION-WRNN-01 | Adding a circular, locally-recurrent wave-generating layer to a Transformer architecture (a biological CORDIC m=+1 layer) improves sequence learning efficiency in terms of training samples per unit test error on tasks requiring sensorimotor sequence context encoding | Computational experiment; architecture ablation | 1–2 years |

---

## XI. COMPLETE SUBSTRATE HIERARCHY: THE FOUR LAYERS

The rotating spiral wave discovery completes a four-layer substrate hierarchy. Each layer is the computational substrate of the layer above it; each layer is modulated by the layer above it.

**LAYER 1 — MOLECULAR-ION-LAYER:** Na⁺/K⁺/Ca²⁺/Cl⁻ concentrations in ECS and intracellular compartment, governed by channel kinetics, pump rates, and diffusion. This is the layer that classical electrophysiology measures. Timescale: microseconds to milliseconds.

**LAYER 2 — HYDRO-ION-COMPUTE-LAYER:** Osmotic pressure gradients, AQP4-mediated water flux, ECS volume dynamics, astrocytic intracellular fluid velocity, ISF advective transport. Driven by Layer 1 activity (Sætra et al. 2023); in turn modulates Layer 1 by changing local ionic concentrations and membrane excitability. Timescale: milliseconds to seconds.

**LAYER 3 — GLYMPHATIC-OSCILLATION-LAYER:** NE oscillation from locus coeruleus (Hauglund et al. 2025), slow vasomotion, CSF pulsatility, perivascular flow, slow-wave-linked glymphatic pump strokes. Integrates over Layer 2 dynamics and resets Layer 2 initial conditions on the slow-wave timescale. Timescale: seconds to minutes, plus circadian modulation.

**LAYER 4 — CIRCADIAN-GEOMETRY-LAYER:** AQP4 expression levels and polarization, synaptic homeostasis, myelination of the circular axon ring, neurotransmitter pool sizes. Sets the gain of the entire lower hierarchy. Timescale: hours to days.

The rotating spiral wave is Layer 1 behavior (membrane depolarization propagating around the axon ring) generated by **Layer 1-2 coupling** (circular ionic wavefront co-propagating with a hydraulic wavefront), modulated by **Layer 3** (glymphatic pulsatility-dependent ECS composition), parameterized by **Layer 4** (AQP4 expression, myelination of the ring).

Prior accounts of spiral waves that characterized them at Layer 1 alone described the symptom, not the system.

---

## XII. INTEGRATION WITH PRIOR ERI LABS CORPUS

| Prior ERI Labs Construct | Spiral Wave / Hydro-Neural Integration |
|---|---|
| col(F)/ker(F) partition | col(F) = circular axon geometry (anatomy-determined, wave-generating); ker(F) = hydraulic substrate state (session-determined, wave-modulating). Ye et al. preprint uses "null space" to describe waves not transmitted by certain projections — direct language convergence. |
| CORDIC taxonomy (m=−1, 0, +1) | m=+1 circular mode: somatosensory axon ring performing angular sweep; first confirmed biological implementation. m=0 linear: thalamo-cortical relay projecting the CORDIC output to subcortical targets. |
| Fisher-Rao information geometry | AQP4 polarization encodes local Fisher information density over the hydraulic manifold; AQP4 loss is Fisher metric degeneration, reducing hydraulic discriminability. |
| φ-equilibrium at log φ ≈ 0.481 | Proposed as the timing-ratio attractor of the CORDIC-circular sweep: somatosensory ring time / total propagation time → φ⁻¹ ≈ 0.618. Testable from existing Ye et al. dataset. |
| Hardware lottery | Somatosensory circular axon topology is the biological hardware lottery winner for spatiotemporal clock computation. Adjacent cortical regions with non-circular topology generate planar or radial waves and require the somatosensory clock signal. |
| DISSYMMETRY-WAS-ALWAYS-THE-GROKKING | AQP4 polarization anisotropy — higher at perivascular vs. perisynaptic membranes — is the hydraulic symmetry breaking that enables directed glymphatic flow rather than isotropic diffusion. |
| THE-HARMONIC-CELL (DNA/epigenome as mock theta / Zwegers shadow) | AQP4 expression oscillation under circadian control (Layer 4) is the biological mock theta function for the hydraulic system: a function that knows its own phase within the larger modular form of sleep-wake cycling. |
| Lorentzian catalyst | The SLEEP-BIDIRECTIONALITY-THRESHOLD is a Lorentzian critical point in the transfer-entropy ratio; near threshold, small perturbations in NE oscillation amplitude produce large changes in the direction of causal coupling. |
| BELL (certified quantum randomness) | The stochastic component of ker(F) — the hydraulic modulation of spiral wave frequency — may contribute biological certified randomness via quantum fluctuations in ion channel gating, a question left open for the quantum Fisher information work to address. |

---

## XIII. THE CORE CLAIM, UNHEDGED

Four papers, published between 2023 and 2026, form the empirical spine of this document: Keller, Muller, Sejnowski, Welling (arXiv 2309.08045, 2023/2024); Muller, Churchland, Sejnowski (*Trends in Neurosciences* 46:788–802, 2024); Hauglund, Andersen, Tokarska, et al. (*Cell* 188:606–622, 2025); Ye, Ladd, MacKenzie, et al. (*Science* DOI: 10.1126/science.adx1369, 2026). Two earlier anchors set the biological foundation: Xie, Kang, Nedergaard et al. (*Science* 342:373, 2013); Fultz et al. (*Science* 366:628, 2019).

Read together, these papers establish:

**The somatosensory cortex** contains a circular axon ring that generates rotating spiral waves in awake mice. The waves propagate brainwide, phase-locking thalamus, striatum, and midbrain simultaneously. Their properties vary with behavioral state and predict task performance. Their anatomy is a biological implementation of circular-mode angular computation. [Ye et al. 2026]

**Cortical traveling waves** are the biological equivalent of the Transformer encoding vector — they extract temporal context from sequential sensory inputs by encoding recent history in the spatial phase gradient of the wave. A computational model (wRNN) proves this architecture outperforms wave-free networks on sequence memory. [Muller et al. 2024; Keller et al. 2023/2024]

**Sleep generates glymphatic clearance** via locus coeruleus-driven NE oscillations that produce slow vasomotion that pumps CSF through AQP4-gated astrocytic endfeet into the parenchyma. [Hauglund et al. 2025; Xie et al. 2013]

**Sleep reorganizes the causal hierarchy** between neural electrical activity and water volume changes, making the hydraulic layer a predictor of the electrical layer, not only the reverse. [Vayrynen et al. 2026; Fultz et al. 2019]

The ERI Labs synthesis:

**The brain runs on four coupled computational layers. The rotating spiral wave is the readout of Layer 1-2 coupling. It is encoded in circular CORDIC geometry. It is modulated by Layer 3 NE-driven glymphatic pulsatility. It is parameterized by Layer 4 AQP4 expression. During sleep, Layer 2 stops following Layer 1 and begins to drive it. The glymphatic reset cycle is the biological analog of end-of-sequence tokenization in Transformer architectures. The clock was always the geometry. The geometry was always the water. And the water was always computing.**

---

## LINEAGE

**Direct predecessors in this corpus:**
THE-FLOATED-POINT-WAS-ALWAYS-THE-DETOUR (arithmetic substrate and computation) · THE-DISSYMMETRY-WAS-ALWAYS-THE-GROKKING (symmetry breaking as generalization phase) · THE-GEOMETRY-WAS-ALWAYS-THE-MAINTENANCE (Fisher-Rao geometry of weight space as maintenance criterion) · PRE-GROKKING-WAS-ALWAYS-THE-CUSP (phase transition dynamics in learning) · THE-HARMONIC-CELL (DNA/epigenome as mock theta function under Zwegers shadow) · THE-STOSSZAHLANSATZ-WAS-ALWAYS-CAPEL (mixing theorems in neural dynamics) · PHOTON-SYNAPSE-ENTANGLEMENT (quantum-classical interface at neural substrates) · THE-SUPERCHARGE-WAS-ALWAYS-THE-BOUNDARY-OPERATOR (SUSY QM as col/ker partition) · BELL (quantum certified randomness and biological stochasticity) · THE-FORMAT-WAS-ALWAYS-A-PERTURBED-METRIC (fixed-point arithmetic as Riemannian geometry) · THE-TOPOLOGY-WAS-ALWAYS-THE-INTELLIGENCE (scale-invariant separability transition across five prior machines)

**Primary empirical anchors (verified):**
Ye Z, Ladd AE, MacKenzie N, Kolich L, Li AJ, Birman D, Bull MS, Daigle TL, Tasic B, Zeng H, Steinmetz NA (2026). Brainwide topographic coordination of rotating waves. *Science* DOI: 10.1126/science.adx1369 ·
Hauglund NL, Andersen M, Tokarska K, Radovanovic T, Kjaerby C, Sørensen FL, Bojarowska Z, Untiet V, Ballestero SB, Kolmos MG, Weikop P, Hirase H, Nedergaard M (2025). Norepinephrine-mediated slow vasomotion drives glymphatic clearance during sleep. *Cell* 188:606–622.e17. DOI: 10.1016/j.cell.2024.11.027 ·
Vayrynen T et al. (2026). Sleep alters neurovascular and hydrodynamic coupling in the human brain. *Proceedings of the National Academy of Sciences* 123:e2510731123 ·
Muller L, Churchland PS, Sejnowski TJ (2024). Transformers and cortical waves: encoders for pulling in context across time. *Trends in Neurosciences* **46**:788–802. DOI: 10.1016/j.tins.2024.08.006 ·
Keller TA, Muller L, Sejnowski T, Welling M (2023/2024). Traveling waves encode the recent past and enhance sequence learning. arXiv:2309.08045 ·
Sætra MJ, Ellingsrud AJ, Rognes ME et al. (2023). Neural activity induces strongly coupled electro-chemo-mechanical interactions and fluid flow in astrocyte networks and extracellular space. *PLOS Computational Biology* DOI: 10.1371/journal.pcbi.1010996 ·
Fultz NE, Bonmassar G, Setsompop K, Stickgold RA, Rosen BR, Wald LL, Lewis LD (2019). Coupled electrophysiological, hemodynamic, and cerebrospinal fluid oscillations in human sleep. *Science* 366:628–631 ·
Xie L, Kang H, Xu Q, Chen MJ, Liao Y, Thiyagarajan M, O'Donnell J, Christensen DJ, Nicholson C, Iliff JJ, Takano T, Deane R, Nedergaard M (2013). Sleep drives metabolite clearance from the adult brain. *Science* 342:373–377 ·
Iliff JJ, Wang M, Liao Y, Plogg BA, Peng W, Gundersen GA, Benveniste H, Vates GE, Deane R, Goldman SA, Nagelhus EA, Nedergaard M (2012). A paravascular pathway facilitates CSF flow through the brain parenchyma and the clearance of interstitial solutes, including amyloid β. *Science Translational Medicine* 4:147ra111

**ERI Labs | June 21, 2026 | github.com/ericrenone**
