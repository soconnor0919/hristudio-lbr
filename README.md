# HRIStudio: A Framework for Wizard-of-Oz Experiments in Human-Robot Interaction Studies

Late-breaking report for submission at the 33rd IEEE Conference on Robot and Human Interactive Communication (RO-MAN 2024).

## Abstract

Human-robot interaction (HRI) research plays a pivotal role in shaping how robots communicate and collaborate with humans. However, conducting HRI studies, particularly those employing the Wizard-of-Oz (WoZ) technique, can be challenging. WoZ user studies can have complexities at the technical and methodological levels that may render the results irreproducible. We propose to address these challenges with HRIStudio, a novel web-based platform designed to streamline the design, execution, and analysis of WoZ experiments. HRIStudio offers an intuitive interface for experiment creation, real-time control and monitoring during experimental runs, and comprehensive data logging and playback tools for analysis and reproducibility. By lowering technical barriers, promoting collaboration, and offering methodological guidelines, HRIStudio aims to make human-centered robotics research easier, and at the same time, empower researchers to develop scientifically rigorous user studies.

## Paper Structure

The paper discusses:
- Introduction to WoZ studies and their challenges
- State-of-the-art WoZ frameworks
- Design of the experimental workflow
- System interfaces and architecture
- Implementation details and roadmap

## Building the Paper

This repository uses LaTeX with the IEEE conference template. To build the PDF:

1. Ensure you have a LaTeX distribution installed
2. Clone this repository
3. Run the build command:
```bash
latexmk -pdf
```

### Using GitLab CI/CD

The repository includes a GitLab CI configuration that automatically builds the PDF using the `thomasweise/docker-texlive-full` Docker image. The generated PDF will be available as an artifact after the pipeline completes.

## Authors

- Sean O'Connor - Bucknell University
- L. Felipe Perrone - Bucknell University

## Contact

- Sean O'Connor - sso005@bucknell.edu
- L. Felipe Perrone - perrone@bucknell.edu

Department of Computer Science  
Bucknell University  
Lewisburg, PA, USA

## License

Copyright © 2024 Sean O'Connor and L. Felipe Perrone. All rights reserved.