# Gradient Color for Javascript

## Requirement
JQuery 1.4 or above

## How to use
You may call generateColor() or generateColorWithManyColor() to calculate the gradient color set
```
	// Generate Single Graident Color
	var tmp = generateColor('#00ffff','#ff0000',52);
	// generateColor(startHex, endHex, totalStepBetweenColors);
	
	// Generate Multiple Graident Colors
	var tmp = generateColorWithManyColor(['#ff0000', '#ff00ff', '#0000ff', '#00ffff'], 1000, false);
	// generateColorWithManyColor(arrayOfColors, totalStepBetweenColors, countForEachGraidentColor = true)
```
Change Log:
### Feb 13 2019
Initialize the script
