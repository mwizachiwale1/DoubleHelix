# Gene Name: Button
This is the gene which codes for a button
### Function
 Buttons for interactive elements that users can click or tap to perform a specific action. They are a fundamental part of user interfaces, allowing users to trigger functions, submit forms, or navigate through different sections of an application.


## Genotype

### Spacing


### Typesetting


### Color


### Feedback
import typesetting;
import spacing;
import typography;


button {
  margin: 0;
  padding:0;
  border: none;
  padding: spacing.Spacing.sm;
  font-size: typesetting.fontSizes.lg;
  box-sizing: border-box;
  font-weight: typesetting.fontWeights.bold;
  background-color: colour.Colour.dhBlue;
  color: colour.Colour.dhWhite;
  display: inline-block;
  width: spacing.ElementSizes.md;
  height: spacing.ElementSizes.md;
  font-family: typography.Typography.button;
  cursor: pointer;
}
button.hover{
  
}




