---
-api-id: T:Windows.Graphics.Printing.OptionDetails.PrintMediaSizeOptionDetails
-api-type: winrt class
---

<!-- Class syntax.
public class PrintMediaSizeOptionDetails : Windows.Graphics.Printing.OptionDetails.IPrintItemListOptionDetails, Windows.Graphics.Printing.OptionDetails.IPrintOptionDetails
-->

# Windows.Graphics.Printing.OptionDetails.PrintMediaSizeOptionDetails

## -description
Represents the list of media size options.

## -remarks
Here is a JavaScript code snippet that shows how to retrieve the object:





```javascript
//  Retrieve the advanced Print Task Options
var printDetailedOptions = 
     Windows.Graphics.Printing.OptionDetails.PrintTaskOptionDetails.getFromPrintTaskOptions(printTask.options);

// get the object
var printMediaSizeOptionDetails = 
     printDetailedOptions.options.lookup(Windows.Graphics.Printing.StandardPrintTaskOptions.mediaSize);
```



## -examples

## -see-also