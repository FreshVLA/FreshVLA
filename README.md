<div align="center">

# FreshVLA

### Frequency-Regularized Time Scale Hierarchical Latent Actions for Vision-Language-Action Models

<p>
  <a href="https://freshvla.github.io/"><img src="https://img.shields.io/badge/Project-Page-007ec6?style=for-the-badge" alt="Project page"></a>
  <a href="https://freshvla.github.io/assets/FreshVLA.pdf"><img src="https://img.shields.io/badge/Paper-PDF-67ac09?style=for-the-badge" alt="Paper PDF"></a>
</p>

</div>

## Code

Coming soon.

## Method

[![FreshVLA architecture showing motion-guided attention and two latent action streams during video pretraining, followed by joint flow matching for robot control.](assets/overview.webp)](assets/overview.webp?raw=true)

**Video pretraining.** A temporal high-pass prior guides attention toward regions that change in videos without action labels. FreshVLA encodes slow task progress in one latent stream and the remaining frame-to-frame motion in another.

**Policy training.** The frozen encoder supplies latent action targets for robot demonstrations. A flow-matching policy learns to generate these latent actions and robot commands together, conditioned on the observation, language instruction and robot state.
