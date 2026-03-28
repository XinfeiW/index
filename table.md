# Task-adaptive τ Values and Test Success Rates on MT50

**Caption.** Each task was evaluated over 10 episodes. On heterogeneous multi-task datasets, different tasks learn distinct τ values, which help improve inference-time trajectory stitching while mitigating out-of-distribution (OOD) issues.

| Environment | Tau | Success Rate |
|---|---:|---:|
| basketball-v2 | 0.647060 | 1.0 |
| bin-picking-v2 | 0.731074 | 1.0 |
| button-press-topdown-v2 | 0.579830 | 1.0 |
| button-press-v2 | 0.569624 | 1.0 |
| button-press-wall-v2 | 0.640738 | 1.0 |
| coffee-button-v2 | 0.753504 | 1.0 |
| coffee-pull-v2 | 0.826085 | 0.7 |
| coffee-push-v2 | 0.924387 | 1.0 |
| dial-turn-v2 | 0.622308 | 0.6 |
| disassemble-v2 | 0.771720 | 0.4 |
| door-close-v2 | 0.541037 | 1.0 |
| door-lock-v2 | 0.607653 | 1.0 |
| door-open-v2 | 0.602143 | 1.0 |
| door-unlock-v2 | 0.565899 | 1.0 |
| hand-insert-v2 | 0.772413 | 0.7 |
| drawer-close-v2 | 0.550447 | 1.0 |
| drawer-open-v2 | 0.596826 | 1.0 |
| faucet-open-v2 | 0.560547 | 1.0 |
| faucet-close-v2 | 0.564990 | 1.0 |
| handle-press-side-v2 | 0.587941 | 1.0 |
| handle-press-v2 | 0.594281 | 0.8 |
| handle-pull-side-v2 | 0.661476 | 1.0 |
| handle-pull-v2 | 0.620350 | 1.0 |
| lever-pull-v2 | 0.653279 | 1.0 |
| peg-insert-side-v2 | 0.662698 | 1.0 |
| pick-place-wall-v2 | 0.700857 | 0.7 |
| pick-out-of-hole-v2 | 0.694235 | 0.9 |
| reach-v2 | 0.562470 | 0.6 |
| push-back-v2 | 0.695173 | 1.0 |
| push-v2 | 0.990000 | 0.4 |
| pick-place-v2 | 0.742855 | 1.0 |
| plate-slide-v2 | 0.616962 | 1.0 |
| plate-slide-side-v2 | 0.611977 | 1.0 |
| plate-slide-back-v2 | 0.633159 | 1.0 |
| plate-slide-back-side-v2 | 0.628932 | 1.0 |
| soccer-v2 | 0.685293 | 0.5 |
| push-wall-v2 | 0.675425 | 0.9 |
| shelf-place-v2 | 0.681807 | 1.0 |
| sweep-into-v2 | 0.656491 | 0.9 |
| sweep-v2 | 0.578034 | 0.9 |
| window-open-v2 | 0.648927 | 1.0 |
| window-close-v2 | 0.596552 | 1.0 |
| assembly-v2 | 0.673008 | 1.0 |
| button-press-topdown-wall-v2 | 0.575277 | 1.0 |
| hammer-v2 | 0.541080 | 1.0 |
| peg-unplug-side-v2 | 0.820463 | 1.0 |
| reach-wall-v2 | 0.525992 | 0.8 |
| stick-push-v2 | 0.533349 | 1.0 |
| stick-pull-v2 | 0.500000 | 0.5 |
| box-close-v2 | 0.545474 | 1.0 |
