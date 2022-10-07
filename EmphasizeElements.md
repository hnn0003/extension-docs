# EmphasizeElements
This should contain all the data needed for the EmphasizeElementsProps.
## Properties
* emphasizeElementsProps - An object containing all of the emphasize elements properties
  * neverDrawn - An array containing the ids of elements that are never drawn
  * alwaysDrawn - An array containing the ids of elements that are always drawn
  * isAlwaysDrawnExclusive - A boolean
  * alwaysDrawnExclusiveEmphasized - An array containing Ids of elements that are isolated and emphasized
  * defaultAppearance - An object containing everything needed for the default feature appearance properties
    * rgb - An object containing rgb color properties
      * r - A number representing red
      * g - A number representing green
      * b - A number representing blue
    * weight - A number representing the line weight
    * transparency - A number representing transparency
    * viewDependentTransparency - A boolean flag for view dependent transparency
    * linePixels - A number enum indicating the line pixel drawing pattern.
    * ignoresMaterial - A boolean flag for ignoring material
    * nonLocatable - A boolean flag for non-locatable
    * emphasized - A boolean flag for emphasized
  * appearanceOverride - An array containing the appearance of overridden elements
    * overrideType - A number enum indicating whether to override color, transparency, or both
    * color - A number in 0xTTBBGGRR format color/transparency value
    * ids - A string array contining the element IDs to display with the specified override
  * wantEmphasis - A boolean
  * unanimatedAppearance - An object containing everything needed for the unanimated feature appearance properties
    * rgb - An object containing rgb color properties
      * r - A number representing red
      * g - A number representing green
      * b - A number representing blue
    * weight - A number representing the line weight
    * transparency - A number representing transparency
    * viewDependentTransparency - A boolean flag for view dependent transparency
    * linePixels - A number enum indicating the line pixel drawing pattern.
    * ignoresMaterial - A boolean flag for ignoring material
    * nonLocatable - A boolean flag for non-locatable
    * emphasized - A boolean flag for emphasized
