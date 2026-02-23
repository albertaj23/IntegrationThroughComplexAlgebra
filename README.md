[README.md](https://github.com/user-attachments/files/25475525/README.md)
# Optimal Contour Selection for Inverse Transform Computation

## Team: A1-T03
**Authors**: Arman Kumar Pandey, Koshal Bishnoi, Akshat Raj, Vishavjeet Sharma, Chopra Rajveer Singh  
**Institution**: VIT University Vellore  
**Date**: October 2025

## Submission Contents
- `main.tex` - LaTeX source (9 pages)
- `main.pdf` - Compiled research paper
- `main_implementation.asciidoc` - Code implementation
- `figures/` - 6 PNG visualization files
- `data/` - 3 CSV data files
- `README.md` - This file

## Running the Code
```bash
# Install dependencies
pip install sympy numpy matplotlib pandas scipy

# Run complete pipeline
python main_implementation.py all
```

## Key Contributions
- Three-phase algorithmic framework for automated contour selection
- 4.5x speedup over numerical FFT methods
- 100% accuracy for rational transfer functions
- Real-time performance: <5ms average computation time
- Low memory footprint: 64 KB (vs 2048 KB for MATLAB)

## Test Cases Validated
1. Second-order systems
2. Digital IIR filters
3. High-order cascaded systems
4. Fourier-type integrals with Jordan's lemma
5. Functions with poles on real axis

## Contact
- akshat.raj2024@vitstudent.ac.in
- arman.pandey2024@vitstudent.ac.in
- koshal.bishnoi2024@vitstudent.ac.in
- vishavjeet.sharma2024@vitstudent.ac.in
- chopra.rajveer2024@vitstudent.ac.in
