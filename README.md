# Enhanced Mechanical Properties of 3D Printed Composites via Continuous Metal Fiber Reinforcement and Process Parameter Optimization

## Project Overview

This repository serves as the supplementary data archive for the paper submitted to AM Journal: "Enhanced Mechanical Properties of 3D Printed Composites via Continuous Metal Fiber Reinforcement and Process Parameter Optimization". This research explores continuous metal fiber-reinforced polymer composites (CMFRPCs) fabricated by 3D printing technology, achieving high fiber volume fraction (FVF) control through process parameter optimization to significantly enhance the mechanical properties of printed parts.

## Research Background

Continuous fiber-reinforced polymer composites (CFRPCs) fabricated by 3D printing have emerged as a pivotal research area because of their capacity to significantly enhance the mechanical properties of printed parts. Although carbon fiber (CF), glass fiber (GF), and aramid fiber (KF) are commonly employed as reinforcing materials, the exploration of metal fibers (MF) as reinforcement, despite their unique attributes, such as high strength, ductility, and potential conductivity, remains relatively limited in the context of 3D printing.

To overcome the challenges of achieving a high fiber volume fraction (FVF) and addressing the inherent high material costs in CFRPCs printing, this study uses low-cost 316 stainless steel filament as the reinforcing fiber and nylon (PA) as the matrix material. The primary objective of this paper is to optimize the fabrication process to achieve enhanced mechanical properties.

## Key Contributions

1. **Cost-effective Material Solution**: Utilizes low-cost 316 stainless steel filament as reinforcement fiber and nylon (PA) as matrix material
2. **High FVF Control**: Achieves high and stably controlled FVF of up to 36% through systematic optimization of key process parameters
3. **Significant Performance Improvement**: Demonstrates 154.48% improvement in tensile strength and 165.18% improvement in bending strength compared to 12% FVF samples
4. **Innovative Dual Extrusion Process**: Develops a novel dual extrusion printing process enabling wider adjustable range of FVF

## Key Research Results

### Mechanical Properties (36% FVF with Optimized Parameters)
- **Tensile Strength**: 312.51 MPa
- **Tensile Modulus**: 46.02 GPa
- **Bending Strength**: 411.3 MPa
- **Bending Modulus**: 65.24 GPa

### Topology-Optimized Specimens
- Compressive strength enhanced by 23.6% even with lower FVF content (6.3% - 12.3%)
- Validates application potential of CMFRPCs in complex topological structures

## Repository Structure

```
MFRPPO/
├── README.md                    # Project documentation
├── experimental_models/         # Experimental model files
│   ├── CAD_models/             # CAD model files
│   ├── STL_files/              # STL print files
│   ├── topology_optimized/     # Topology-optimized models
│   └── specimen_designs/       # Specimen design files
├── experimental_data/          # Experimental data
│   ├── mechanical_testing/     # Mechanical testing data
│   │   ├── tensile_tests/      # Tensile test data
│   │   ├── bending_tests/      # Bending test data
│   │   └── compression_tests/  # Compression test data
│   ├── process_parameters/     # Process parameter data
│   │   ├── layer_thickness/    # Layer thickness parameters
│   │   ├── deposition_spacing/ # Deposition spacing parameters
│   │   └── infill_patterns/    # Infill pattern parameters
│   ├── fiber_volume_fraction/  # Fiber volume fraction data
│   └── microscopy_images/      # Microscopy images
└── path_planning_code/         # Path planning code
    ├── dual_extrusion/         # Dual extrusion process code
    ├── fiber_path_generation/  # Fiber path generation
    ├── parameter_optimization/ # Parameter optimization algorithms
    └── G_code_scripts/         # G-code scripts
```

## Process Parameter Research

### Key Optimization Parameters
1. **Layer Thickness**: Affects fiber wetting and interlayer bonding
2. **Deposition Spacing**: Controls fiber distribution and volume fraction
3. **Infill Pattern**: Optimizes fiber orientation and load transfer

### Fiber Volume Fraction Control
- **Target FVF Range**: 6.3% - 36%
- **Control Accuracy**: ±1.5%
- **Stability Validation**: Inter-batch coefficient of variation <5%

## Experimental Methods

### Material System
- **Reinforcement**: 316 stainless steel continuous fibers (diameter 0.1-0.2mm)
- **Matrix Material**: Nylon (PA6/PA12)
- **Interface Treatment**: Optimized fiber surface pretreatment

### Testing Standards
- **Tensile Testing**: ASTM D638 standard
- **Bending Testing**: ASTM D790 standard
- **Compression Testing**: ASTM D695 standard

## Innovation Highlights

1. **Metal Fiber-Reinforced 3D Printing**: First systematic study of 316 stainless steel fibers in fused deposition modeling
2. **High FVF Process Control**: Breaks through traditional process limitations, achieving stable 36% high fiber volume fraction control
3. **Gradient Material Fabrication**: Establishes technical route for gradient CFRPCs through additive manufacturing
4. **Cost-Effectiveness Optimization**: Addresses the high material cost challenges often associated with CFRPCs

## Application Prospects

- **Aerospace**: Lightweight high-strength structural components manufacturing
- **Automotive Industry**: Functionally integrated composite parts
- **Biomedical**: Customized implants and devices
- **Consumer Electronics**: Conductive structure-integrated devices

## Data Usage Instructions

This repository contains complete experimental models, testing data, and process codes, supporting the reproducibility of research results. All data are categorized and stored by experimental stage and type for easy access and utilization.

## Contact Information

For questions or collaboration inquiries, please contact:
- Email: [yaoyuan@shu.edu.cn]
- Institution: [Shanghai University]

## Citation Format

If you use the data or methods from this research, please cite:
```
@misc
{MFRPPO2025,
  author = {fly2mars},
  title = {Enhanced Mechanical Properties of 3D Printed Composites via Continuous Metal Fiber Reinforcement and Process Parameter Optimization},
  year = {2025},
  howpublished = {\url{https://github.com/fly2mars/MFRPPO}},
  note = {Accessed: October 02, 2025}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
