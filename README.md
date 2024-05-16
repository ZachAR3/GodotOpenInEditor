![ExamplePhoto](https://github.com/ZachAR3/GodotOpenInEditor/assets/32562377/d0617663-40c6-4159-9f6d-c53346632a0d)

### **About:**
A simple plugin to enable the ability to quickly open folders in a desired code editor (any editor that accepts its launch command + the directory should work, I have only tested VSCode and Rider)

### **Usage:**
Simply download the plugin from the Godot asset store [here](https://godotengine.org/asset-library/asset/2970) or directly from the source, create an `addons` folder in your root Godot directory if you don't already have one in the desired project and drag the `GodotOpenInEditor` folder into the addons folder. Then go to your `Project settings -> Plugins -> Enable GodotOpenInEditor`. For the plugin to work you also have to have a valid external editor location in your `Editor -> Editor Settings -> Text Editor -> External -> Exec path`. This should be the path your the executable or script to launch your desired IDE / text editor.

### **Credits:**
This is adapted from a C# plugin made by Creta Park which was VSCode specific and be found [here](https://gist.github.com/Creta5164/244fcb11a3b2d5d65ef196ca0e2d08ed)
I have rewrote the entire thing in GDScript while also removing the checks forcing VSCode only.
