# BOCCHI Sample Pack

- Generated: 2026-05-02
- Total samples: 32 (16 BOCCHI + 16 Inference DISP-protocol)
- Resolution: 480x320 (3:2, downscaled from 1080x720)
- RGB: JPEG q85 | Mask: PNG (binary, 0=sharp, 255=blur)

## Selection rationale

1. Priority 1: paper Fig 2 BOCCHI image_ids = `0500, 0519, 0585, 0607` (all 4 included)
2. Priority 2: random BOCCHI (seed=531) excluding the 15 qualitative-comparison ids
3. Inference set: 16 random from `Inference_dataset/img_bocchi/` (164 self-photographed)

## Avoided ids (qualitative comparison reuse)

Excluded: 0056, 0062, 0067, 0112, 0151, 0155, 0338, 0370, 0432, 0499, 0509, 0585, 0599, 0604, 0607

Note: PAPERFig ids `0585` and `0607` overlap with qualitative success set; kept per Priority 1 (Fig 2 takes precedence).

## Mapping table

| File | Source set | Original ID |
|------|------------|-------------|
| `bocchi_01_rgb.jpg` + `bocchi_01_mask.png` | BOCCHI | 0500 |
| `bocchi_02_rgb.jpg` + `bocchi_02_mask.png` | BOCCHI | 0519 |
| `bocchi_03_rgb.jpg` + `bocchi_03_mask.png` | BOCCHI | 0585 |
| `bocchi_04_rgb.jpg` + `bocchi_04_mask.png` | BOCCHI | 0607 |
| `bocchi_05_rgb.jpg` + `bocchi_05_mask.png` | BOCCHI | 0406 |
| `bocchi_06_rgb.jpg` + `bocchi_06_mask.png` | BOCCHI | 0380 |
| `bocchi_07_rgb.jpg` + `bocchi_07_mask.png` | BOCCHI | 0507 |
| `bocchi_08_rgb.jpg` + `bocchi_08_mask.png` | BOCCHI | 0508 |
| `bocchi_09_rgb.jpg` + `bocchi_09_mask.png` | BOCCHI | 0633 |
| `bocchi_10_rgb.jpg` + `bocchi_10_mask.png` | BOCCHI | 0391 |
| `bocchi_11_rgb.jpg` + `bocchi_11_mask.png` | BOCCHI | 0424 |
| `bocchi_12_rgb.jpg` + `bocchi_12_mask.png` | BOCCHI | 0558 |
| `bocchi_13_rgb.jpg` + `bocchi_13_mask.png` | BOCCHI | 0186 |
| `bocchi_14_rgb.jpg` + `bocchi_14_mask.png` | BOCCHI | 0307 |
| `bocchi_15_rgb.jpg` + `bocchi_15_mask.png` | BOCCHI | 0258 |
| `bocchi_16_rgb.jpg` + `bocchi_16_mask.png` | BOCCHI | 0348 |
| `inference_01_rgb.jpg` + `inference_01_mask.png` | Inference (DISP-protocol) | 0010 |
| `inference_02_rgb.jpg` + `inference_02_mask.png` | Inference (DISP-protocol) | 0163 |
| `inference_03_rgb.jpg` + `inference_03_mask.png` | Inference (DISP-protocol) | 0154 |
| `inference_04_rgb.jpg` + `inference_04_mask.png` | Inference (DISP-protocol) | 0086 |
| `inference_05_rgb.jpg` + `inference_05_mask.png` | Inference (DISP-protocol) | 0019 |
| `inference_06_rgb.jpg` + `inference_06_mask.png` | Inference (DISP-protocol) | 0146 |
| `inference_07_rgb.jpg` + `inference_07_mask.png` | Inference (DISP-protocol) | 0152 |
| `inference_08_rgb.jpg` + `inference_08_mask.png` | Inference (DISP-protocol) | 0158 |
| `inference_09_rgb.jpg` + `inference_09_mask.png` | Inference (DISP-protocol) | 0103 |
| `inference_10_rgb.jpg` + `inference_10_mask.png` | Inference (DISP-protocol) | 0096 |
| `inference_11_rgb.jpg` + `inference_11_mask.png` | Inference (DISP-protocol) | 0107 |
| `inference_12_rgb.jpg` + `inference_12_mask.png` | Inference (DISP-protocol) | 0104 |
| `inference_13_rgb.jpg` + `inference_13_mask.png` | Inference (DISP-protocol) | 0109 |
| `inference_14_rgb.jpg` + `inference_14_mask.png` | Inference (DISP-protocol) | 0155 |
| `inference_15_rgb.jpg` + `inference_15_mask.png` | Inference (DISP-protocol) | 0036 |
| `inference_16_rgb.jpg` + `inference_16_mask.png` | Inference (DISP-protocol) | 0083 |
