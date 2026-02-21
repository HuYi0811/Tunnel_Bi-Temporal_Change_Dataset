# Tunnel_Bi-Temporal_Change_Dataset
Public dataset for bi-temporal tunnel crack change detection, including 22 real crack-change image pairs and 500 synthetic crack-change pairs (2-pixel width, saliency 1.05) with pixel-level annotations.

## Directory Structure

- real_crack_changes/
  - A/: images at time 1
  - B/: images at time 2
  - label/: pixel-level change masks

- synthetic_crack_changes/
  - A/ images at time 1 which 合成了裂缝
  - B/ images at time 2
  - label/pixel-level change masks

## Annotation Format

- PNG format
- White pixels (255): change
- Black pixels (0): unchanged

## License

This dataset is released under the MIT License.
For academic use only.
