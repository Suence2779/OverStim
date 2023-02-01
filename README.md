# OverStim
[Download](https://github.com/cryo-es/OverStim/releases)

Controls your vibrator/vibrating toy based on what's happening in Overwatch 2, using computer vision.

Requires [Intiface Central](https://intiface.com/central/)  if you want to use it with a toy.

Default settings:
- **Elimination:** +30% intensity for 6 seconds
- **Assist:** +15% intensity for 3 seconds
- **Mercy:**
  - **Resurrect:** +100% intensity for 4 seconds
  - **Heal beam:** +10% intensity while active
  - **Damage boost beam:** +30% intensity while active
- **Zenyatta:**
  - **Harmony orb:** +15% intensity while active
  - **Discord orb:** +20% intensity while active

Known Issues:
- Poor detection of Mercy's heal beam at 2560x1440p.
- Probably doesn't work at aspect ratios other than 16:9.
- High latency to the game server causes Mercy's beam to reconnect to people slower when switching beam types. This can cause temporary gaps in vibration.
- Only works on Windows.
