Fraunces Generated Masters Interpolation and Kerning Recipes:

Here are the formulas used to generate OpMax GoofyMax (i.e., low contrast) and OpMin GoofyMin (i.e., high contrast) masters with ScaleAndInterpolate.py in ~/documentation/scripts/.

## ROMAN ##

# Black OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: 100
Interpolate Vertical: 95
Units of Tracking: -30

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 106
Interpolate Vertical: 103
Units of Tracking: -20

Kerning: Start by interpolating with ScaleAndInterpolate.py

# Light OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: -4.6
Interpolate Vertical: -4
Units of Tracking: -84

Lowercase
Scale Horizontal: 89
Scale Vertical: 92.8
Interpolate Horizontal: -2.6
Interpolate Vertical: -5
Units of Tracking: -80

Kerning: Start by copying from Light OpMax GoofyMin

# Black OpMin GoofyMin = Black OpMax GoofyMin + Black OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 72
Interpolate Vertical: 64
Units of Tracking: 14

Lowercase
Scale Horizontal: 102.545922778
Scale Vertical: 102.545922778
Interpolate Horizontal: 72
Interpolate Vertical: 64
Units of Tracking: 12

Kerning: Copy from Black OpMin GoofyMax, will only need minor adjustments

# Light OpMin GoofyMin = Light OpMax GoofyMin + Light OpMin GoofyMax

Caps
Scale Horizontal: 101
Scale Vertical: 100
Interpolate Horizontal: 80
Interpolate Vertical: 60
Units of Tracking: 16

Lowercase
Scale Horizontal: 103.041075879
Scale Vertical: 103.041075879
Interpolate Horizontal: 70
Interpolate Vertical: 60
Units of Tracking: 14

Kerning: Copy from Light OpMin GoofyMax, will only need minor adjustments


## Italic ##

# Black OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: 100
Interpolate Vertical: 95
Units of Tracking: -30

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 106
Interpolate Vertical: 103
Units of Tracking: -20

Skew: 2°

# Light OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: -4.6
Interpolate Vertical: -4
Units of Tracking: -84

Lowercase
Scale Horizontal: 89
Scale Vertical: 92.8
Interpolate Horizontal: -2.6
Interpolate Vertical: -5
Units of Tracking: -80

Skew: 2°

# Black OpMin GoofyMin = Black OpMax GoofyMin + Black OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 72
Interpolate Vertical: 64
Units of Tracking: 14

Lowercase
Scale Horizontal: 102.545922778
Scale Vertical: 102.545922778
Interpolate Horizontal: 72
Interpolate Vertical: 64
Units of Tracking: 12

Skew: 0°

# Light OpMin GoofyMin = Light OpMax GoofyMin + Light OpMin GoofyMax

Caps
Scale Horizontal: 101
Scale Vertical: 100
Interpolate Horizontal: 80
Interpolate Vertical: 60
Units of Tracking: 16

Lowercase
Scale Horizontal: 103.041075879
Scale Vertical: 103.041075879
Interpolate Horizontal: 70
Interpolate Vertical: 60
Units of Tracking: 14

Skew: 0°