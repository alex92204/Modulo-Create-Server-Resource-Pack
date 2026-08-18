# Modulo Create Server Resource Pack
- Please only use this to add custom models or sounds!
- Commits will be applied and reloaded automatically!
- A very basic example is provided so you can copy that.

## Making a Model and Texture
- You'll need to be familiar with Blockbench, see [this tutorial](https://youtu.be/b4fGIpVMd8o) for an introduction (although the resource pack part of the tutorial is for a newer version!).
- Clone the repository (GitHub desktop recommended), and place your model and texture in `custom/models/item` and `custom/textures/item`.

## Adding a custom_model_data Predicate
- In the `minecraft/models/item` folder, either open an existing .json file, or copy-paste one and rename it to the item you're adding a model to.
- Rename the `parent` field inside to this too.
- If you're editing an existing file, copy and paste a `predicate` and change the `custom_model_data` to the next number. Make sure you put a comma after the previous `predicate`!
- Then change `model` so it links to your `custom:item/<model>`.

## Finishing Up
- Commit and push your changes to the repository, make sure you give a description of what you added!
- With your targeted item in hand, use `/trigger CustomModelData set <n>` to apply your model! 
