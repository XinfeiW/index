# Task-adaptive τ Values, Prompt Lengths, and Test Success Rates on MT50

**Caption.** Each task was evaluated over 10 episodes. On heterogeneous multi-task datasets, different tasks learn distinct prompt lengths and τ values, which help improve inference-time trajectory stitching while mitigating out-of-distribution (OOD) issues.

| Environment | Prompt Length | /Tau | Success Rate |
|---|---:|---:|---:|
| basketball-v2 | 38 | 0.647060 | 1.0 |
| bin-picking-v2 | 25 | 0.731074 | 1.0 |
| button-press-topdown-v2 | 21 | 0.579830 | 1.0 |
| button-press-v2 | 7 | 0.569624 | 1.0 |
| button-press-wall-v2 | 18 | 0.640738 | 1.0 |
| coffee-button-v2 | 28 | 0.753504 | 1.0 |
| coffee-pull-v2 | 35 | 0.826085 | 0.7 |
| coffee-push-v2 | 38 | 0.924387 | 1.0 |
| dial-turn-v2 | 41 | 0.622308 | 0.6 |
| disassemble-v2 | 37 | 0.771720 | 0.4 |
| door-close-v2 | 10 | 0.541037 | 1.0 |
| door-lock-v2 | 25 | 0.607653 | 1.0 |
| door-open-v2 | 19 | 0.602143 | 1.0 |
| door-unlock-v2 | 19 | 0.565899 | 1.0 |
| hand-insert-v2 | 28 | 0.772413 | 0.7 |
| drawer-close-v2 | 10 | 0.550447 | 1.0 |
| drawer-open-v2 | 8 | 0.596826 | 1.0 |
| faucet-open-v2 | 16 | 0.560547 | 1.0 |
| faucet-close-v2 | 17 | 0.564990 | 1.0 |
| handle-press-side-v2 | 20 | 0.587941 | 1.0 |
| handle-press-v2 | 21 | 0.594281 | 0.8 |
| handle-pull-side-v2 | 21 | 0.661476 | 1.0 |
| handle-pull-v2 | 27 | 0.620350 | 1.0 |
| lever-pull-v2 | 23 | 0.653279 | 1.0 |
| peg-insert-side-v2 | 9 | 0.662698 | 0.5 |
| pick-place-wall-v2 | 32 | 0.700857 | 0.7 |
| pick-out-of-hole-v2 | 30 | 0.694235 | 0.9 |
| reach-v2 | 6 | 0.562470 | 1 |
| push-back-v2 | 27 | 0.695173 | 1.0 |
| push-v2 | 37 | 0.990000 | 0.4 |
| pick-place-v2 | 37 | 0.742855 | 1.0 |
| plate-slide-v2 | 18 | 0.616962 | 1.0 |
| plate-slide-side-v2 | 21 | 0.611977 | 1.0 |
| plate-slide-back-v2 | 10 | 0.633159 | 1.0 |
| plate-slide-back-side-v2 | 13 | 0.628932 | 1.0 |
| soccer-v2 | 37 | 0.685293 | 0.5 |
| push-wall-v2 | 25 | 0.675425 | 0.9 |
| shelf-place-v2 | 27 | 0.681807 | 1.0 |
| sweep-into-v2 | 30 | 0.656491 | 0.9 |
| sweep-v2 | 22 | 0.578034 | 0.9 |
| window-open-v2 | 19 | 0.648927 | 1.0 |
| window-close-v2 | 17 | 0.596552 | 1.0 |
| assembly-v2 | 37 | 0.673008 | 1.0 |
| button-press-topdown-wall-v2 | 20 | 0.575277 | 1.0 |
| hammer-v2 | 31 | 0.541080 | 1.0 |
| peg-unplug-side-v2 | 37 | 0.820463 | 1.0 |
| reach-wall-v2 | 27 | 0.525992 | 0.8 |
| stick-push-v2 | 26 | 0.533349 | 1.0 |
| stick-pull-v2 | 36 | 0.500000 | 0.5 |
| box-close-v2 | 27 | 0.545474 | 1.0 |
