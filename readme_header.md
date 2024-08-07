### BlenderBIM daily builds with in-blender autoupdate

Only supported for BlenderBIM with Python 3.11 (default Python version in Blender 4.2+) as Blender doesn't support separate builds for different Python versions.

1. Setup BlenderBIM Daily Builds Repository.

Drag'n'drop url for your platform from the table below to Blender, accept adding a new repository.

![](img/image-1.png)

During repository creation check "Check Updates On Startup" to get updates for daily BlenderBIM builds automatically.

![](img/image-2.png)

Alternatively, repository can be created manually, without drag'n'drop:

- Open Blender Preferences -> "+" -> "Add Remote Remository". You'll see a window similar to the one above.

- Use as URL: `https://raw.githubusercontent.com/IfcOpenShell/blenderbim_unstable_repo/main/index.json` and check auto-updates if you want them.



2. Install extension.

To install the BlenderBIM extension you can either drag'n'drop the same url again and install it:

![alt text](img/image-3.png)

Or you can search for "blenderbim" in Extensions and Install it.

![](img/image.png)


3. Each time you start Blender it will check for updates and you will be able to update BlederBIM using "Update" button.

![](img/image-4.png)

Make sure to restart Blender after.

![](img/image-5.png)


### Available daily builds

