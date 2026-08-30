# Zala 421

[![CI](https://github.com/Sam-DarkBall-Mods/Zala-421/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Zala-421/actions/workflows/ci.yml)

Zala 421 adds UAVs and tripod launchers for BLUFOR, OPFOR and Independent. The
package also contains a tripod bag, an ammunition box, reload handling and
separate displays for the pilot and gunner.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The `zala421` prefix and the current game class names remain unchanged.

## License

Code and configs use GPL-2.0-or-later. Original models, textures, materials and
audio use APL-SA. See [LICENSES.md](LICENSES.md).
