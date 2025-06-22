# Analog & Digital Electronics (ESC-301)

**Contact Hours:** 3L  
**Credits:** 3  
**Semester:** III

## Course Objectives
* To learn the fundamental concepts of various analog components and their uses. [cite: 2]
* To understand digital logic levels and their application in digital electronic circuits. [cite: 2]
* To equip students with the ability to analyze and design a range of digital electronic circuits. [cite: 2]

## Pre-Requisites
* Knowledge of Basic Electronics from the first year (semesters 1 & 2). [cite: 2]
* A fundamental understanding of BJTs, P-N diodes, and Schottky diodes. [cite: 2]
* Basic concepts of FETs, OP-AMPs as circuit components, and Feedback. [cite: 2]

## Examination Scheme

| Component | Marks |
|-----------|-------|
| Mid Semester Exam | 15 [cite: 2] |
| Assignment and Quiz | 10 [cite: 2] |
| Attendance | 5 [cite: 2] |
| End Semester Exam | 70 [cite: 2] |
| **Total** | **100** [cite: 2] |

## Syllabus

| Unit | Content | Hours/Unit |
|------|---------|------------|
| 1 | Different Classes of Amplifiers (Class-A, B, AB, C), Feedback and Oscillation concepts, Phase Shift, Wein Bridge oscillators, Astable & Monostable Multivibrators, Schmitt Trigger circuits, 555 Timer. [cite: 3] | 9 [cite: 3] |
| 2 | Binary Number System, Boolean Algebra, BCD, ASCII, EBDIC, Gray codes, signed binary number representation (1's and 2's complement), Binary arithmetic, Venn diagram, SOP and POS forms, logic expression minimization. [cite: 3] | 11 [cite: 3] |
| 3 | Combinational circuits (Adder, Subtractor, Encoder, Decoder, Comparator, Multiplexer, De-Multiplexer, Parity Generator), Sequential Circuits (Flip-flops: SR, JK, D, T, JK Master-slave), Registers (SISO, SIPO, PIPO, PISO), Ring counter, Johnson counter, Synchronous and Asynchronous counters, Mod N Counter design. [cite: 5] | 10 [cite: 5] |
| 4 | A/D and D/A conversion techniques (D/A: R-2-R, A/D: successive approximation), Logic families (TTL, ECL, MOS, CMOS). [cite: 5] | 6 [cite: 5] |

## Course Outcomes
* ESC-301.1: Understand the basic operations of various analog components. [cite: 11]
* ESC-301.2: Comprehend fundamental gate operations and the laws of Boolean algebra. [cite: 12]
* ESC-301.3: Grasp the basic structure of a digital computer, the stored program concept, and various arithmetic and control unit operations. [cite: 13]

## Unit 1 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
This plan spans **10 class-days (≈ 2 weeks)**. Each day contains:
* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**  
* **Time allocation**

> **Tip for students:** Bring the ELI5 summary cards to every class for quick revision.

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Foundations & Context |
|   | 2 | Class-A Amplifier |
|   | 3 | Class-B & Class-AB Amplifiers |
|   | 4 | Class-C Amplifier & Recap |
|   | 5 | Feedback Concepts |
| 2 | 6 | Oscillation Basics & Phase-Shift Oscillator |
|   | 7 | Wein-Bridge Oscillator |
|   | 8 | Multivibrators: Astable |
|   | 9 | Monostable & Schmitt Trigger |
|   | 10 | 555 Timer & Unit Review |

---

### Detailed Daily Breakdown

#### Day 1 – Foundations & Context
* **Theory:** Review semiconductor basics (diode biasing), BJT regions (cut-off, active, saturation), purpose of amplifiers/oscillators.  
* **ELI5:** "Transistors are like taps: open a little, a lot of water (current) can flow."  
* **Activities:** Warm-up quiz, oscilloscope demo of small audio amp.  
* **Homework:** Watch a 6-min video on BJTs; list three doubts.

#### Day 2 – Class-A Amplifier
* **Theory:** Common-emitter biasing (360° conduction), gain equation \(A_v \approx -\beta (R_C / r_e)\), efficiency ≈ 25 – 30 %, heat dissipation.  
* **ELI5:** "A microphone that's always on and drains the battery even during silence."  
* **Practice:** Breadboard a 2N2222 Class-A; measure gain.  
* **Self-study:** Sketch input/output waveforms and mark 360° conduction.

#### Day 3 – Class-B & Class-AB Amplifiers
* **Theory:** Push-pull pair (180° conduction), efficiency up to 78 %, crossover distortion and its cure via slight bias (Class-AB).  
* **ELI5:** "Two kids take turns pushing a swing; jerks appear if they don't switch smoothly."  
* **Activity:** Observe crossover distortion; add bias diodes to create Class-AB; re-observe.  
* **Quiz:** 5 MCQs.

#### Day 4 – Class-C Amplifier & Recap
* **Theory:** Conduction angle < 180°, high efficiency (> 80 %) for RF with LC tank.  
* **ELI5:** "Tiny pushes at just the right moments let the swing's own rhythm fill gaps."  
* **Recap Game:** "Amplifier Bingo" matching features to Class-A/B/AB/C.  
* **Homework:** Worksheet on real-world amplifier examples.

#### Day 5 – Feedback Concepts
* **Theory:** Negative vs positive feedback, block diagram \(A/(1+βA)\), Barkhausen criterion (βA = 1).  
* **ELI5:** "Thermostat (negative) vs microphone squeal (positive)."  
* **Hands-on:** Build op-amp inverting amp; vary feedback resistor.  
* **Assessment:** 3 numerical problems on gain with feedback.

#### Day 6 – Oscillation Basics & Phase-Shift Oscillator
* **Theory:** Oscillator = amplifier + positive feedback + frequency-selective network; RC phase-shift network (three RC sections → 180°), frequency \(f ≈ 1/(2π\sqrt{6}RC)\).  
* **ELI5:** "Like clapping in a tunnel where echoes keep you clapping forever."  
* **Lab:** Build phase-shift oscillator with 2N2222; display sine wave.  
* **Exercise:** Calculate \(f\) for given R, C values.

#### Day 7 – Wein-Bridge Oscillator
* **Theory:** Lead-lag RC bridge gives zero phase shift at \(f_0 = 1/(2πRC)\); op-amp gain ≥ 3; amplitude stabilization via lamp/diodes.  
* **ELI5:** "Two musical notes meet at the right pitch and loop endlessly."  
* **Demo:** Breadboard Wein-bridge oscillator; vary potentiometer to start/stop oscillation.  
* **Worksheet:** Fill blanks in \(f_0\) derivation.

#### Day 8 – Multivibrators: Astable
* **Theory:** No stable state, cross-coupled transistors; timing \(T = 0.693 (R_A + 2R_B)C\) for 555.  
* **ELI5:** "A seesaw that never stops, always up-down."  
* **Activity:** LED flasher (555 astable); measure period.  
* **Quiz:** Predict effect of doubling **C**.

#### Day 9 – Monostable & Schmitt Trigger
* **Theory:** Monostable (one stable state) pulse width \(T = 1.1 RC\); Schmitt trigger with hysteresis, UTP/LTP equations.  
* **ELI5:** "Doorbell rings once when pressed (monostable); gate needing big push to open and close (Schmitt)."  
* **Hands-on:** 555 monostable buzzer; op-amp Schmitt LED threshold demo.

#### Day 10 – 555 Timer & Unit Review
* **Theory:** Internal structure: comparators, RS latch, discharge transistor; modes (astable, monostable, bistable); design 1 kHz square-wave example.  
* **ELI5:** "A tiny orchestra conductor telling parts when to start and stop."  
* **Cumulative Practice:** Peer teaching of topics.  
* **Assessment:** 15-mark test (MCQ, short answer, numericals).  
* **Feedback:** Discuss errors; preview Unit 2.

---

### Support Strategies for Struggling Learners
1. Colour-coded notes & mind-maps daily.  
2. Printed ELI5 summary cards after every class.  
3. 5-question retrieval quiz at start; "exit ticket" at end.  
4. Recorded mini-lectures (< 8 min) for replay.  
5. Study-buddy system; 2 office-hours/week.  
6. Weekly reflection sheet to identify fuzzy concepts.

### Expected Outcomes after 2 Weeks
* Classify amplifiers (A/B/AB/C) and compute efficiency & gain.  
* Explain/design basic feedback & oscillator circuits.  
* Design timing circuits using 555 timer.  
* Predict waveform shapes/frequencies and troubleshoot faults.  
* Translate technical explanations into intuitive analogies (ELI5).

## Unit 2 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 2 requires **≈ 11 lecture hours**. We again distribute the material across **10 class-days (≈ 2 weeks)** with ample recap and practice.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**  
* **Time allocation**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Binary Number System & Conversions |
|   | 2 | Binary Arithmetic: Addition & Subtraction |
|   | 3 | Binary Multiplication & Division |
|   | 4 | Signed Number Representations (1's & 2's Complement) |
|   | 5 | Coding Systems: BCD, ASCII, EBCDIC |
| 2 | 6 | Gray Code & Applications |
|   | 7 | Boolean Algebra Basics & De-Morgan's Laws |
|   | 8 | Venn Diagrams, SOP & POS Forms |
|   | 9 | Logic Minimization with Karnaugh Maps |
|   | 10 | Integrated Practice & Unit-2 Review |

---

### Detailed Daily Breakdown

#### Day 1 – Binary Number System & Conversions
* **Theory:** Positional notation, base-10 ↔ base-2 conversions, octal & hexadecimal shorthand, weight of each bit.  
* **ELI5:** "Think of LEGO blocks—each row is worth double the row before it; counting higher means adding more blocks or starting a new bigger row."  
* **Activities:** Use coloured beads to build numbers in base-2; quick worksheet converting 25₁₀ → ?₂ and 101101₂ → ?₁₀.  
* **Homework:** Flash-card drill (10 conversion questions).

#### Day 2 – Binary Arithmetic: Addition & Subtraction
* **Theory:** Bit-by-bit addition rules (0+0, 0+1, 1+1 → carry), ripple-carry concept; unsigned subtraction using borrow.  
* **ELI5:** "Adding in binary is like adding fingers: if you have two thumbs (1+1) you bundle them as one bigger thumb next door (carry)."  
* **Practice:** Paper-and-pencil problems; simulate 4-bit adder in Logisim.  
* **Quiz:** 8 quick sums.

#### Day 3 – Binary Multiplication & Division
* **Theory:** Shift-and-add multiplication; restoring division algorithm; hardware insight (shift registers, adders).  
* **ELI5:** "Multiplying is just adding the same pile shifted sideways; dividing is repeatedly seeing how many piles fit."  
* **Lab:** Design an 8-bit multiplier in simulation; trace signals.  
* **Self-study:** Write pseudo-code for binary division of 1101₂ ÷ 11₂.

#### Day 4 – Signed Number Representations
* **Theory:** Sign-magnitude vs 1's complement vs 2's complement; range; overflow detection; importance in ALUs.  
* **ELI5:** "Positive numbers wear a happy badge (0) at the front; negatives wear a sad badge (1) and sometimes flip colours of their clothes (1's) or flip plus add one more button (2's)."  
* **Activity:** Convert −13₁₀ to all three forms; indicate overflow in 4-bit 2's complement 7 + 3.  
* **Check-In:** 5 MCQs.

#### Day 5 – Coding Systems: BCD, ASCII, EBCDIC
* **Theory:** Why codes? decimal digit BCD 8421 & 2421, character encodings (ASCII table, EBCDIC basics).  
* **ELI5:** "Computers can only store 0s and 1s, so they give every letter a secret handshake pattern."  
* **Demo:** Type name in text editor, view ASCII/hex values; micro-exercise converting 59₁₀ to BCD.  
* **Homework:** Memorise ASCII for A–Z using mnemonic sheet.

#### Day 6 – Gray Code & Applications
* **Theory:** Binary-Gray conversion formula, single-bit transition property, cyclic codes; use in rotary encoders & error reduction.  
* **ELI5:** "Gray code is like tip-toeing so you move only one step at a time, never two, to avoid tripping."  
* **Hands-on:** Build paper wheel with Gray code; convert 1011₂ ↔ Gray.  
* **Exercise:** 10 conversions.

#### Day 7 – Boolean Algebra Basics & De-Morgan's Laws
* **Theory:** Boolean variables, AND/OR/NOT operations, truth tables, postulates, commutative/associative/distributive laws, De-Morgan's theorems.  
* **ELI5:** "It's like a game of light switches: AND needs all switches on; OR needs any; NOT flips on ↔ off."  
* **Practice:** Build expressions from word statements; verify with simulation.  
* **Quick Quiz:** Simplify using laws.

#### Day 8 – Venn Diagrams, SOP & POS Forms
* **Theory:** Visualising Boolean expressions with Venn diagrams, minterms/maxterms, canonical Sum-of-Products and Product-of-Sums.  
* **ELI5:** "Colour the circles that match the rule; the coloured patches turn into equations."  
* **Activity:** Truth-table → SOP conversion for 3-variable function; highlight regions on Venn diagram.  
* **Self-study:** Convert same function to POS.

#### Day 9 – Logic Minimization with Karnaugh Maps
* **Theory:** 2-, 3-, 4-variable K-maps, adjacency, grouping rules (1-, 2-, 4-, 8-cell), don't-care conditions, deriving simplified expressions.  
* **ELI5:** "K-map is a picture puzzle—circle neighbouring 1s to make biggest blobs; each blob means a shorter sentence."  
* **Lab:** Simplify 4-variable majority function in groups; implement with logic gates in simulator.  
* **Assessment:** 5-mark worksheet.

#### Day 10 – Integrated Practice & Unit-2 Review
* **Theory Recap:** Inter-link conversions, codes to arithmetic, Boolean to circuit.  
* **ELI5:** "Today we play 'show & tell'—prove you can speak both computer language (0-1) and kid language."  
* **Cumulative Practice:** Design a 2-bit magnitude comparator end-to-end (truth-table → K-map → circuit).  
* **Unit-2 Test:** 20 marks (MCQ, short answer, K-map problem).  
* **Feedback:** Discuss pitfalls; introduce Unit 3 preview.

---

### Expected Outcomes after 2 Weeks
* Convert numbers between decimal, binary, octal & hex quickly.  
* Perform binary arithmetic and detect overflow.  
* Represent signed numbers using 1's and 2's complement.  
* Translate data to BCD, ASCII, EBCDIC, and Gray codes.  
* Apply Boolean algebra laws and De-Morgan's theorems.  
* Derive SOP/POS forms and minimise logic with Karnaugh maps.  
* Build and test simple digital circuits derived from minimised expressions.

## Unit 3 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 3 covers both **combinational** and **sequential** digital circuits in roughly **10 lecture hours**. The plan below splits material across **10 class-days (≈ 2 weeks)** with daily practice and ELI5 support.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Combinational Logic Refresher & Half-Adder |
|   | 2 | Full-Adder & Subtractor Circuits |
|   | 3 | Encoders & Decoders |
|   | 4 | Multiplexers, De-Multiplexers & Parity Generators |
|   | 5 | Combinational Mini-Project & Recap |
| 2 | 6 | Sequential Logic Intro & SR Flip-Flop |
|   | 7 | JK, D, T & Master-Slave Flip-Flops |
|   | 8 | Registers: SISO, SIPO, PIPO, PISO |
|   | 9 | Counters: Ring, Johnson, Sync vs Async, Mod-N Design |
|   | 10 | Integrated Design Project & Unit-3 Review |

---

### Detailed Daily Breakdown

#### Day 1 – Combinational Logic Refresher & Half-Adder
* **Theory:** Difference between combinational and sequential circuits; truth table → logic equation; design of half-adder (sum & carry).  
* **ELI5:** "Combinational is like a vending machine that gives a snack instantly based on the buttons you press—no memory of past presses."  
* **Activity:** Build half-adder with two LEDs for sum/carry on breadboard.  
* **Homework:** Draw truth table for 3-input majority function.

#### Day 2 – Full-Adder & Subtractor Circuits
* **Theory:** Cascading half-adders to form full-adder; ripple-carry chain; half & full subtractors, borrow concept.  
* **ELI5:** "Full-adder is two vending machines in series—first handles your coins, second adds any leftover change (carry)."  
* **Practice:** Simulate 4-bit ripple-carry adder in Logisim; measure propagation delay.  
* **Quiz:** 6 quick problems on binary addition/subtraction.

#### Day 3 – Encoders & Decoders
* **Theory:** 4-to-2 priority encoder; 3-to-8 decoder; applications in keyboards and memory selection.  
* **ELI5:** "Encoder is like naming animals by first letters; decoder is spelling the whole word back when you give the letter."  
* **Lab:** Use 74LS138 decoder to light one of eight LEDs; modify for simple 2-to-4 encoder.  
* **Self-study:** Draw block diagram of a 7-segment decoder.

#### Day 4 – Multiplexers, De-Multiplexers & Parity Generators
* **Theory:** 2ⁿ-to-1 MUX selection lines; building any logic function with MUX; DEMUX and data routing; even/odd parity generator using XOR gates; comparator basics.  
* **ELI5:** "MUX is a railway switch deciding which train (input) goes to the single track (output). DEMUX is the opposite."  
* **Hands-on:** Wire 4-to-1 MUX chip; feed binary switches; verify output; design 4-bit parity generator.  
* **Assessment:** Worksheet: implement F(A,B,C)=Σ(1,2,6,7) using 8-to-1 MUX.

#### Day 5 – Combinational Mini-Project & Recap
* **Project:** Teams design a 3-bit binary to Gray code converter using available gates/MUX.  
* **ELI5 Tie-In:** "We're teaching the circuit to tip-toe like Gray code—one step at a time."  
* **Review Game:** Kahoot quiz on all combinational blocks.  
* **Homework:** Prepare one doubt & one interesting fact for sequential circuits.

#### Day 6 – Sequential Logic Intro & SR Flip-Flop
* **Theory:** Need for memory; feedback concept; SR latch with NOR gates; SR flip-flop with clock; timing diagrams, metastability.  
* **ELI5:** "Sequential is like a diary—it remembers the last thing you wrote until you change it."  
* **Activity:** Build SR latch on simulator; test invalid (S=R=1) condition.  
* **Quick Quiz:** Identify Q output for given timing chart.

#### Day 7 – JK, D, T & Master-Slave Flip-Flops
* **Theory:** JK as universal flip-flop avoiding invalid state; D for data storage; T for toggling; master-slave configuration to remove race; truth tables & excitation tables.  
* **ELI5:** "JK flip-flop is a smart light with 'toggle' button—never confused. D flip-flop is a camera snapshot at each click (clock)."  
* **Lab:** Use 74LS76 JK flip-flop to build divide-by-2 counter.  
* **Self-study:** Compare characteristic equations of SR, JK, D, T.

#### Day 8 – Registers: SISO, SIPO, PIPO, PISO
* **Theory:** Shift registers vs parallel registers; serial-in serial-out (SISO), serial-in parallel-out (SIPO), etc.; applications in data conversion and communication.  
* **ELI5:** "Registers are buckets passing marbles either one-by-one or all at once."  
* **Hands-on:** Cascade four D flip-flops to create 4-bit SISO; observe shifting with LEDs.  
* **Exercise:** Design PIPO register using 74HC173.

#### Day 9 – Counters: Ring, Johnson, Sync vs Async, Mod-N Design
* **Theory:** Asynchronous (ripple) counter operation & glitches; synchronous counter advantage; ring & Johnson counters using shift registers; Mod-N design via reset logic.  
* **ELI5:** "Counters are like odometers; synchronous ones flip digits together to avoid wobble."  
* **Lab:** Build 4-bit Johnson counter and display sequence on LEDs; design Mod-6 synchronous counter truth table.  
* **Assessment:** 10-mark worksheet on timing & sequence derivation.

#### Day 10 – Integrated Design Project & Unit-3 Review
* **Project:** Design a 3-bit synchronous up/down counter driving a 3-to-8 decoder & LEDs.  
* **ELI5:** "Make a smart scoreboard that can count both forward and backward."  
* **Cumulative Review:** Students explain favourite sequential block using both technical and ELI5 language.  
* **Unit-3 Test:** 20 marks (MCQ, design, timing problems).  
* **Feedback:** Highlight common mistakes; preview Unit 4.

---

### Expected Outcomes after 2 Weeks
* Design and implement combinational circuits: adders, subtractors, encoders, decoders, MUX/DEMUX, parity generators, comparators.  
* Explain and demonstrate operation of SR, JK, D, T flip-flops and master-slave configurations.  
* Construct various registers and describe their data movement.  
* Design synchronous and asynchronous counters, including ring, Johnson, and custom Mod-N versions.  
* Analyse timing diagrams and predict circuit behaviour.  
* Translate technical designs into intuitive ELI5 explanations.

## Unit 4 – Two-Week Curriculum (Designed for Below-Average Learners)

### Overview
Unit 4 is shorter (≈ 6 lecture hours) but involves two distinct themes: **data conversion** and **logic families**. We still employ **10 class-days** to ensure repetition and mastery.

* **Theory (standard explanation)**  
* **ELI5 version (Explain-Like-I'm-Five)**  
* **Activities / practice**

| Week | Day | Topics |
|------|-----|--------|
| 1 | 1 | Analog vs Digital Signals & Need for Conversion |
|   | 2 | D/A Basics & Weighted-Resistor DAC |
|   | 3 | R-2R Ladder DAC |
|   | 4 | A/D Basics & Comparator (Flash) Concept |
|   | 5 | Successive Approximation ADC |
| 2 | 6 | Sample-and-Hold & Quantization Error |
|   | 7 | Logic Families Intro & TTL Characteristics |
|   | 8 | ECL & MOS Families |
|   | 9 | CMOS Family, Comparison Chart |
|   | 10 | Consolidated Review & Mini-Project |

---

### Detailed Daily Breakdown

#### Day 1 – Analog vs Digital & Why Convert?
* **Theory:** Continuous vs discrete signals; sampling theorem in plain words; everyday examples (microphone, thermometer).  
* **ELI5:** "Turning a smooth rainbow (analog) into Lego blocks (digital) so computers can play with it."  
* **Activity:** View sine wave on oscilloscope, then 8-bit sampled version on PC.  
* **Homework:** List 5 devices that need A/D or D/A.

#### Day 2 – D/A Basics & Weighted-Resistor DAC
* **Theory:** Principle of summing currents with weighted resistors; binary-weighted ladder; limitations (large resistor range, matching).  
* **ELI5:** "Each switch pours different cup sizes of water; adding them fills a measuring jug to the right level."  
* **Lab:** Simulate 4-bit weighted DAC; vary binary input, record output voltage.  
* **Quiz:** Compute output for 1010₂ given Vref.

#### Day 3 – R-2R Ladder DAC
* **Theory:** Equal resistor values (R & 2R) for easier fabrication; current division analysis; monotonicity; output equation.  
* **ELI5:** "A neat staircase (R-2R) instead of random step heights—easier to build, same climb."  
* **Hands-on:** Breadboard 3-bit R-2R ladder; measure steps with multimeter.  
* **Self-study:** Derive output for 110₂.

#### Day 4 – A/D Basics & Comparator (Flash) Concept
* **Theory:** Sampling, hold circuit, quantization; flash ADC architecture with 2ⁿ-1 comparators; speed vs hardware cost.  
* **ELI5:** "Many friends each have a ruler; they all shout together if the water is past their mark—fast but many friends needed."  
* **Demo:** Online flash-ADC animation; class discussion on trade-offs.  
* **Check-in:** 4 MCQs.

#### Day 5 – Successive Approximation ADC
* **Theory:** SAR register binary search; DAC inside loop; timing diagram; resolution vs conversion time.  
* **ELI5:** "Guessing game: you say 8, too high; 4, too low; 6, perfect!—done in fixed number of guesses."  
* **Lab:** Simulate 8-bit SAR ADC; step through bit decisions.  
* **Worksheet:** Calculate conversion time for 1 MHz clock.

#### Day 6 – Sample-and-Hold & Quantization Error
* **Theory:** Need for S/H in multiplexed systems; aperture time; quantization noise; SNR basics.  
* **ELI5:** "Freezing a moving picture so you can draw it square-by-square."  
* **Activity:** Plot staircase approximation of sine; compute max quantization error.  
* **Quiz:** True/false on S/H effects.

#### Day 7 – Logic Families Intro & TTL Characteristics
* **Theory:** Switching parameters (prop delay, fan-out, noise margin, power dissipation); TTL circuit internals (multi-emitter transistor); standard sub-families (LS, HCT).  
* **ELI5:** "TTL is like an old but strong truck—uses more fuel but carries decent load fast enough."  
* **Hands-on:** Toggle 74LS00 NAND; measure prop delay with oscilloscope.  
* **Homework:** Summarise advantages of LS over standard TTL.

#### Day 8 – ECL & MOS Families
* **Theory:** Emitter-coupled logic (ECL): differential pair, constant current, fastest speed, low swing; MOS logic basics—depletion/enhancement load.  
* **ELI5:** "ECL is a race car always revving (current flowing) ready to zoom; MOS is like pushing gates in a garden—needs patience but uses little water (power)."  
* **Demo:** Show ECL gate datasheet; compare power/table with TTL.  
* **Exercise:** Fill comparison table (speed, power, noise) for TTL vs ECL vs MOS.

#### Day 9 – CMOS Family & Comparison
* **Theory:** Complementary MOS pull-up/pull-down; near-zero static power; high fan-out; sub-families (HC, AC); latch-up issue and remedies.  
* **ELI5:** "CMOS is like automatic doors that only use electricity when moving."  
* **Lab:** Build simple CMOS inverter with CD4007; measure static current ≈ 0 µA.  
* **Assessment:** 10-mark quiz covering all families.

#### Day 10 – Consolidated Review & Mini-Project
* **Mini-Project:** Design an 8-level digital volume control: microphone → SAR ADC → microcontroller → R-2R DAC → speaker.  
* **ELI5 Wrap-Up:** "We capture sound blocks, teach computer to count them, then rebuild the song at chosen loudness."  
* **Cumulative Review:** Jeopardy-style game on conversions & families.  
* **Unit-4 Test:** 15 marks (MCQ, short answer, design).  
* **Feedback:** Highlight next-semester analog-digital interfacing topics.

---

### Expected Outcomes after 2 Weeks
* Explain need for A/D and D/A conversion and distinguish between them.  
* Design and analyse weighted-resistor and R-2R ladder DACs.  
* Describe operation and timing of flash and successive-approximation ADCs.  
* Calculate quantization error and understand sample-and-hold role.  
* Compare TTL, ECL, MOS, CMOS logic families in terms of speed, power, noise margin, and fan-out.  
* Implement simple DAC/ADC circuits and measure key parameters.  
* Convey technical ideas in intuitive ELI5 language. 