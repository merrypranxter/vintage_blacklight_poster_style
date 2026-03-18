# Shader Behavior Ideas

## Goal

Translate vintage blacklight poster logic into procedural or realtime rendering behavior.

## Core Shader Behaviors

### 1. Emissive Edge Detection
Use contour detection or normal-based rim lighting to create fluorescent boundaries.

### 2. Glow Stack
Separate glow into layers:
- tight rim
- medium bloom
- wide aura haze

### 3. Palette Mapping
Map brightness or mask zones into blacklight-safe palette ramps:
- violet -> magenta -> cyan -> white
- blue -> green -> yellow
- pink -> orange -> yellow

### 4. Soft Overspray Noise
Add low-amplitude diffusion around bright zones to simulate airbrush or pigment bleed.

### 5. Starfield Layer
Sparse procedural sparkle points with flicker or twinkle thresholds.

### 6. Aura Fog
Low-frequency moving noise or radial haze fields for mystical atmosphere.

### 7. Posterized Contrast
Keep the image bold enough to read as poster iconography, not just continuous simulation.

## Motion Suggestions

- slow pulse glow breathing
- tiny chroma shimmer
- drifting mist
- halo expansion / contraction
- star twinkle sparsity changes

## Avoid

- photoreal PBR logic as main aesthetic
- overly metallic reflections
- hyper-gloss UI neon
- too many small animated details



