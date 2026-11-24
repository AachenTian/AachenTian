# Hi, I'm Yachen Tian

I work on reinforcement learning, robotics, and multi-agent systems, with a
focus on reliable evaluation and reproducible research software.

## Current focus

- Multi-agent drone formation and target control
- Communication-aware coordination
- Dynamics estimation and uncertainty-aware evaluation
- GPU-parallel reinforcement learning with JAX

## Selected project

### Multi-Agent Drone Control

An ongoing research project built around JAX, Crazyflow, Hydra, Flax, Optax,
MuJoCo, and pytest. The work includes formation control, collision-aware target
reaching, multi-agent communication baselines, dynamics estimation, automated
evaluation, and reproducible experiment tooling.

The full research implementation remains private while the related paper is in
progress. A publication-safe engineering demo is being prepared for release.

## Selected simulation demos

The clips below show representative capabilities from my multi-agent robotics
work. Click a preview to open the corresponding MP4.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="assets/demos/cooperative_target_reaching.mp4">
        <img src="assets/demos/cooperative_target_reaching.jpg" alt="Four-agent cooperative target reaching and hover" width="100%">
      </a>
      <br><strong>Cooperative target reaching and hover</strong><br>
      Four agents preserve their formation while moving to a distant target
      and settling into a stable hover.
    </td>
    <td width="50%" valign="top">
      <a href="assets/demos/formation_recovery.mp4">
        <img src="assets/demos/formation_recovery.jpg" alt="Multi-agent formation recovery" width="100%">
      </a>
      <br><strong>Formation recovery</strong><br>
      A distorted initial configuration converges back to the assigned
      geometry during closed-loop flight.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="assets/demos/collision_recovery.mp4">
        <img src="assets/demos/collision_recovery.jpg" alt="Collision-aware multi-agent recovery" width="100%">
      </a>
      <br><strong>Collision-aware recovery</strong><br>
      The team resolves a close encounter, restores safe separation, and
      continues toward the task objective.
    </td>
    <td width="50%" valign="top">
      <a href="assets/demos/communication_under_regional_wind.mp4">
        <img src="assets/demos/communication_under_regional_wind.jpg" alt="Communication-aware control under regional wind" width="100%">
      </a>
      <br><strong>Communication-aware control under regional wind</strong><br>
      Event-triggered state correction supports four-agent coordination while
      the formation crosses a strong spatially localized wind field.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="assets/demos/communication_aware_payload_transport.mp4">
        <img src="assets/demos/communication_aware_payload_transport.jpg" alt="Payload-blind communication-aware transport" width="100%">
      </a>
      <br><strong>Payload-blind, communication-aware transport</strong><br>
      Three drone-trigger channels coordinate a suspended load through an
      offset gate using a joint dynamics estimator under process noise.
    </td>
    <td width="50%" valign="top">
      <a href="assets/demos/payload_gate_transport.mp4">
        <img src="assets/demos/payload_gate_transport.jpg" alt="Cooperative suspended-payload gate transport" width="100%">
      </a>
      <br><strong>Cooperative payload transport through a gate</strong><br>
      A multi-agent controller carries a suspended payload through a narrow
      double-wall passage in the Newton/MuJoCo simulation environment.
    </td>
  </tr>
</table>

## Tools I use

`Python` · `JAX` · `Flax` · `Optax` · `MuJoCo` · `Hydra` · `NumPy` · `pytest`
· `GitHub Actions` · `Weights & Biases`
