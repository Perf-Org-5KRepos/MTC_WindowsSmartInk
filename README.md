
# Windows Smart Ink (Alpha)
A project that shows how to combine Microsoft's Custom Vision Service with Windows 10 Ink capabilities to create "smart ink".  Analyze ink strokes and classify the shapes to identify what the user is drawing.  Examples would be recoginizing product icons, technical diagrams components, etc.

[![Demo Video](/README_Images/Demo_Video.PNG?raw=true)](https://www.youtube.com/watch?v=5ht1CR8gm78) 

Trained models can be packaged and shared as Nuget packages (eventually).

The project is currently comprised of two parts:
## Microsoft.MTC.SmarkInk Library
This library contains the components for creating, managing, utlizing and packaging smart ink models created using the Custom Vision Service.

## SmartInkLaboratory
Test harness for interacting with Custom Vision Service to train AI models to recognize ink patterns and to map ink patterns to icons/images.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
