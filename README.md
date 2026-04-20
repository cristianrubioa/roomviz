# roomviz

3D interactive room dashboard powered by Home Assistant.

## Pipeline

Sweet Home 3D → OBJ → Blender → Render → Home Assistant

## Structure

- `models/` → source models (SweetHome, OBJ, Blender)
- `assets/renders/` → rendered images used in the dashboard
- `home-assistant/` → YAML configuration

## Preview

![preview](/home-assistant/demo.png)


## Notes

- `.sh3d` is the base model
- `.blend` contains lighting and render setup
- renders are mapped to entity states in Home Assistant
