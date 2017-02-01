# PartTweaker

Simple KSP part module that allows changing one color property of the model's material.


## Sample usage

```
MODULE
{
	name = ModuleMaterialTweaker
	varDisplayName = Color
	materialVarName = _Color
	showAlpha = false
	showRGB = true
	allowInFlight = false
	colorR = 1.0
	colorG = 0.5
	colorB = 1.0
	colorA = 1.0
}
```

See sources for the defaults and comments.

Value for `materialVarName` depends on the shader used. See Unity docs for more details.