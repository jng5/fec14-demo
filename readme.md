
# Responsive Email Demo

Julie Ng  
Frontend Conference Zürich  
28 August 2014

This is responsitory of the demo code from the live coding session during my talk.

This demo newsletter is meant for demonstration and educational purposes only and is not extensively tested or meant for real use.

**TL;DR**  
See the [code changes required to make footer responsive](https://github.com/jng5/fec14-demo/commit/659c500f721b291e5ffa860bc95b2c1c8f61f0c7) for both Android 4.3 and Outlook

## File structure

Please note these folders also include code changes/demoes that were not shown during live coding session.

  * **original-not-responsive**  
    original source code
    
  * **responsive-v1**:  
    Initial responsive footer. Does not work for Android 4.3+ Email app.
    
  * **responsive-v2**:  
    Make footer responsive for Anroid 4.3 but still work for Outlook.
    
  * **responsive-final**:  
    Some more responsive changes to article content above, e.g. hide body text, use buttons.
  
#### Files

   * `build.html` - inlined HTML markup to be sent
   * `demo.html` and `styles.css` compiled email integrating dynamic content, but without prelined CSS. I find it helpful for debugging.
  
## Source Folder

  * `reset.css` - some generic resets you should include in every email.
  * `responsive.css` - the simple styles we used to make the footer responsive.
  * `index.html.erb` - **finished** ERB file used to create markup.
  * `original.html.erb` - original ERB file used to create markup. 
  
As you can imagine, I use a markup templating language like `ERB` or `twig` so I can make my markup changes in **one place instead of three** if I have 3 footer columns.

## License (MIT)

Copyright (c) 2014 Julie Ng

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.