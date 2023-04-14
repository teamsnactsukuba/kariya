# Machine-assisted proofs of Kariya's theorem with computer algebra

This repository contains materials used for machine-assisted proofs of Kariya's theorem,
described in the following paper:

Ayane Ito, Takefumi Kasai, and Akira Terui. 
Computer-assisted proofs of "Kariya's theorem" with computer algebra.

Implementation is made for a computer algebra system Risa/Asir.

## Contents

Please see README.md in the following directories for detailed information.

* def: formulations of the theorems
* proof: programs of proofs of the theorems
* src: source code of Wu's method

## Prerequisites

For executing the implementation here, you need the following:

- OpenXM infrastructure for communicating mathematical software systems: http://www.openxm.org/
  - Risa/Asir, a computer algebra system: http://www.math.kobe-u.ac.jp/Asir/ (included in the OpenXM distribution and installed automatically with OpenXM under default settings)
- X Window System server (for executing OpenXM)

Our test environment is as follows:
- Linux 4.15.0 (Ubuntu 18.04)
- OpenXM 1.3.3
- Risa/Asir 20210326 (Kobe Distribution)

