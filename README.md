<div align="center">

# FreshVLA

### Frequency-Regularized Time Scale Hierarchical Latent Actions for Vision-Language-Action Models

<p>
  <a href="https://freshvla.github.io/"><img src="https://img.shields.io/badge/Project-Page-007ec6?style=for-the-badge" alt="Project page"></a>
  <a href="https://freshvla.github.io/assets/FreshVLA.pdf"><img src="https://img.shields.io/badge/Paper-PDF-67ac09?style=for-the-badge" alt="Paper PDF"></a>
</p>

<a name="method"></a>
<a href="assets/overview.webp?raw=true"><img src="assets/overview.webp" width="100%" alt="FreshVLA architecture showing video pretraining at two time scales and joint flow matching for robot control."></a>

</div>

## News

- **[2026.11]** The [FreshVLA preprint](https://freshvla.github.io/assets/FreshVLA.pdf) and [project page](https://freshvla.github.io/) are now available.

## Overview

**FreshVLA** learns **continuous latent actions** from videos without action labels. It uses these representations as training targets alongside robot demonstrations, so a vision-language-action policy can learn to predict both latent actions and robot commands.

## Highlights

- **Focus on motion.** A temporal high-pass prior guides visual attention toward image regions that change as the gripper interacts with an object.
- **Separate task progress from fine motion.** One latent stream tracks progress over longer intervals, while the other captures local adjustments. In the continuous-latent ablation, introducing this hierarchy raises LIBERO-Long success from 93.0% to 98.0%.
- **Generalize across simulation conditions.** FreshVLA achieves 98.2% average success on LIBERO and 80.4% on zero-shot LIBERO-PLUS across seven types of perturbation.
- **Transfer to a physical robot.** Across four tabletop tasks on a Flexiv arm, FreshVLA achieves 84.2% average success, 7.5 percentage points above π<sub>0.5</sub>.

## Code

Coming soon.
