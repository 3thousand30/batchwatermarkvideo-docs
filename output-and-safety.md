---
layout: default
title: Output and Safety
nav_order: 5
---

# Output and Safety

BWV starts with a separate `watermarked` output folder inside the selected input folder. Select **Browse** to choose another destination or type an absolute folder path.

The default suffix is `_watermarked`, so `clip.mov` becomes `clip_watermarked.mp4`. Change or clear the suffix to suit your naming workflow.

For every input, BWV writes a temporary MP4 candidate in the output folder. It promotes that candidate only after FFmpeg succeeds and the candidate has a non-zero size. Original videos are never overwritten.

Enable **Skip existing output files** to preserve a prior output during a re-run. With it disabled, a successfully completed watermark copy replaces an existing output of the same name.
