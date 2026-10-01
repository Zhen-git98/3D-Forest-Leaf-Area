This repository provides a computed tomography (CT)-inspired framework for retrieving three-dimensional forest leaf area distributions from multi-angle terrestrial laser scanning (TLS) observations.

The framework supports two types of inversion objects:

- **Individual trees**, for direct tree-level retrieval and analysis.
- **Forest blocks**, for efficient stand-level reconstruction when individual-tree segmentation is impractical or unnecessary.

For each tree or forest block, multi-angle TLS observations are integrated into a coupled linear system to jointly estimate voxel values. Object-level results can then be aligned within a common voxel grid to reconstruct the 3D leaf area distribution of the forest stand.

## Paper and data

- **Paper:** The manuscript has been submitted. A link will be added when available.
- **Paper data:** https://doi.org/10.5281/zenodo.23056619
- **Example data:** See the `Example Data` folder in this repository.

## MergeResultsToStand.exe

Double-click MergeResultsToStand.exe to merge all tree- or block-based results in the current folder into a single stand-level result.

## Documentation

The user manual is under preparation and will be updated regularly.

## Contact

For assistance, please contact:

**Yuzhen Xing**  
xingyuzhen20@mails.ucas.ac.cn

Questions, suggestions, bug reports, and other feedback are welcome.

## License

This software is licensed under the PolyForm Noncommercial License 1.0.0. Commercial use requires prior written permission from the copyright holder.
