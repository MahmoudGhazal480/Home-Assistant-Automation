# atumation time ligth Home-Assistant-Automation

This project contains Home Assistant automations that implement:

1. Turn OFF living room light between 06:00 and 18:00 **after 10 minutes with no motion**.
2. Turn OFF TV between 19:00 and 07:00 **after 10 minutes with no motion**.
3. If motion is detected, keep both living room light and TV ON.

## File

- `automations.yaml`

## Important

Update these entity IDs to match your setup:

- `binary_sensor.living_room_motion`
- `light.living_room`
- `media_player.living_room_tv`

## How to use

Copy the automation entries from `automations.yaml` into your Home Assistant automations, then reload automations from Settings.
