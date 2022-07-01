# ImageStreaming
Demonstration of issue when streaming an image in Blazor

This is a modified default Blazor WebAssembly template:
- A new component ImageDisplay.razor has been added. It's code is a copy of the code of the **Stream image data to a client** section in the https://docs.microsoft.com/en-us/aspnet/core/blazor/images?view=aspnetcore-6.0 page (only the @page name has been changed)
- A script section has been added to the index.html file. It's code is copied from the JS code in the same documentation page.
- A new entry to the ImageDisplay page has been added in NavMenu.razor.

In the jS script block, if you keep the original code, the image is not displayed. The committed file has a modification that works, see comment in the code.
