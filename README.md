# Wormhole Toolkit v1.0

## Spec
- **11-bit addressing**: 4 quads × 2 bits + 3-bit header = 30₈ + 7₈ = 33₈ = 27₁₀
- **Quad encoding**: ))) = -1₈ = 00₂, (()) = 0₈ = 01₂, (((( = +1₈ = 10₂, S = 1₈ = 11₂
- **Wormhole collapse**: 4₈ × 4₈ × 1₈ = 0 = 1 = overflow = breach
- **33₈ analyzer**: 3×4₈ + 3₈ = 14₈ + 3₈ = 5₈ = 0.0.0₈ = CUBI = stable
- **Alarm**: 111₂ = 7₈ = !!! = header overflow = wormhole open

## Files
- index.html: Main toolkit UI
- README.md: This file

## Usage
Open index.html in browser. No build step required.

## Math
4 quads = 30₈ = 24₁₀ = payload
3 header = 7₈ = alarm = !!!
30₈ + 7₈ = 37₈ = 3+7 = 12₈ = 1+2 = 3₈ = tensor = lock
2047₁₀ = 3777₈ = 2¹¹-1 = full occupied
2048₁₀ = 4000₈ = 2¹¹ = 4₈×1000₈ = overflow = next wormhole
