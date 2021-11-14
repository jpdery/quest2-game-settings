# Quest 2 Game Settings

## Population: One - 72 Hz - High settings
```
adb shell setprop debug.oculus.refreshRate 72
adb shell setprop debug.oculus.foveation.level 3
adb shell setprop debug.oculus.cpuLevel 3
adb shell setprop debug.oculus.gpuLevel 4
adb shell setprop debug.oculus.textureWidth 1954
adb shell setprop debug.oculus.textureHeight 2048
adb shell "settings put system font_scale 0.85 && settings put system font_scale 1.0"
```

## Population: One - 80 Hz - High settings
```
adb shell setprop debug.oculus.refreshRate 80
adb shell setprop debug.oculus.foveation.level 3
adb shell setprop debug.oculus.cpuLevel 3
adb shell setprop debug.oculus.gpuLevel 4
adb shell setprop debug.oculus.textureWidth 1954
adb shell setprop debug.oculus.textureHeight 2048
adb shell "settings put system font_scale 0.85 && settings put system font_scale 1.0"
```

## Population: One - 90 Hz - Medium settings
```
adb shell setprop debug.oculus.refreshRate 90
adb shell setprop debug.oculus.foveation.level 3
adb shell setprop debug.oculus.cpuLevel 3
adb shell setprop debug.oculus.gpuLevel 4
adb shell setprop debug.oculus.textureWidth 1728
adb shell setprop debug.oculus.textureHeight 1904
adb shell "settings put system font_scale 0.85 && settings put system font_scale 1.0"
```

## Population: One - 90 Hz - High settings (More dropped frames)
```
adb shell setprop debug.oculus.refreshRate 90
adb shell setprop debug.oculus.foveation.level 3
adb shell setprop debug.oculus.cpuLevel 3
adb shell setprop debug.oculus.gpuLevel 4
adb shell setprop debug.oculus.textureWidth 1862
adb shell setprop debug.oculus.textureHeight 2048
adb shell "settings put system font_scale 0.85 && settings put system font_scale 1.0"
```
