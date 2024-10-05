## Flux CFG Comparisions

Test and see how Flux behaves with different guidance methods:
1. Guidance embedding a.k.a the Flux guidance distillation by default present in Flux Dev
2. CFG a.k.a the most commonly used cfg viz. noise_pred = noise_pred_uncond + W * (noise_pred_text - noise_pred_uncond)
3. CFG++ a.k.a instead of W ∈ [0, Inf+] use W ∈ [0,1] to interpolate b/w the two noise_preds. https://arxiv.org/pdf/2406.08070
4. AFG by Disney as proposed here: https://arxiv.org/pdf/2410.02416
5. Smoothed Energy Guidance: https://arxiv.org/pdf/2408.00760
6. ICG and TSG as proposed here: https://arxiv.org/pdf/2407.02687
7. TSG + AFG
## Citations:
TODO