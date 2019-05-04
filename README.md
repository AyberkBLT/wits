# WITS - What Is That Stuff
A replication of WAILA for Minecraft: Bedrock Edition

## For Addon Makers
If you want your custom blocks to be displayed by this addon, you have to follow these steps:
1. Add this snippet to your resource pack's manifest file:
```json
"capabilities": ["experimental_custom_ui"]
```
2. Create a folder named `experimental_ui`, and inside it, create a folder named `blocks`.
3. Take any picture you want of your block (recommended resolution: 32x32) and drop it into `experimental_ui/blocks`
