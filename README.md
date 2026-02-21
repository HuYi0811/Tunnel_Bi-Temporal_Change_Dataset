# Tunnel_Bi-Temporal_Change_Dataset
Public dataset for bi-temporal tunnel crack change detection, including 22 real crack-change image pairs and 500 synthetic crack-change pairs (2-pixel width, saliency 1.05) with pixel-level annotations.

## Directory Structure

- real_crack_changes/
  - images_t1/: images at time 1
  - images_t2/: images at time 2
  - labels/: pixel-level change masks

- synthetic_crack_changes/
  - images_t1/
  - images_t2/
  - labels/

## Annotation Format

- PNG format
- White pixels (255): change
- Black pixels (0): unchanged

## License

This dataset is released under the MIT License.
For academic use only.
