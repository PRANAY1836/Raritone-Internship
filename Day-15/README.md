# AI/ML Internship — Day 15

## Garment Warping & Fitting Research

### Objective
Research garment warping techniques used in Virtual Try-On systems and understand how garments adapt to different body shapes and poses.

## Topics Covered

### Thin Plate Spline (TPS)
- Landmark-based garment warping
- Fast and lightweight transformation
- Commonly used in Virtual Try-On systems

### Flow-Based Warping
- Pixel-level garment transformation
- Better texture preservation
- Handles complex body poses

### CP-VTON
- Characteristic Preserving Virtual Try-On Network
- Uses TPS and GMM for garment alignment
- Preserves clothing details

### VITON-HD
- High-resolution Virtual Try-On framework
- Improved realism and garment quality
- Better texture preservation

### Geometric Matching Module (GMM)
- Aligns garments with body shape
- Learns transformation parameters
- Improves fitting accuracy

## Workflow

User Image
↓
Body Detection
↓
Pose Detection
↓
Body Segmentation
↓
Garment Matching
↓
Garment Warping
↓
Image Synthesis
↓
Final Output

## Comparison

| Technology | Realism | Speed |
|------------|----------|--------|
| TPS | Medium | High |
| Flow-Based Warping | High | Medium |
| CP-VTON | High | Medium |
| VITON-HD | Very High | Medium |
| GMM | High | High |

## Key Findings

- TPS provides fast geometric alignment.
- Flow-Based Warping handles complex deformations.
- CP-VTON preserves garment characteristics.
- VITON-HD produces high-quality outputs.
- GMM improves garment-body matching.

## Technologies Studied

- TPS
- Flow-Based Warping
- CP-VTON
- VITON-HD
- GMM
- Computer Vision
- Deep Learning

## Conclusion

Studied garment warping and fitting methods used in modern Virtual Try-On systems. VITON-HD and GMM provide the best visual quality and fitting accuracy, while TPS remains an efficient lightweight solution.
