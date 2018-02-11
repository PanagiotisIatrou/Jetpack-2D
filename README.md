# Jetpack-2D
Simple Jetpack for 2D platformers! It also includes functionality for a fuel bar!

# Implementation:
1) Drag the Jetpack2D.unitypackage
2) Done!

# How to use:
1) Add the Jetpack.cs script to a GameObject that contains a Rigidbody2D.
2) You can now control use the jetpack by pressing [SPACE]. You can change the action button by modyfying the 32nd line of Jetpack.cs script
3) If you want the Jetpack fuel to be shown in a Slider bar, then you just add the JetpackFuelBar.cs script to the same object you attached the Jetpack.cs script. After that just drag and drop your Slider in the inspector
3) Done!

# Notes:
1) To quickly see the jetpack in action open the ExampleScene.unity scene located in the Example folder and press Play!
2) The JetpackBar field of the JetpackFuelBar.cs script NEEDS to be assigned in the inspector before runtime. Will cause a Null Reference Exception if not.
