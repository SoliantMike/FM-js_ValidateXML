FM-js_ValidateXML
===========
A question posed in the FileMaker Community asked if there was a way to validate XML. Interestingly, there are solutions for this in javascript that we can use to pass a result back to a FileMaker script. Based on some javascript found online regarding finding unclosed tags in XML, by adjusting the javascript a little bit, we can have it use a FMP URL to call a script in the parent FileMaker File and pass the result back as a script parameter.

Sample Javascript from Stack overflow here:
http://stackoverflow.com/questions/25898719/how-to-find-invalid-unclosed-xml-tags-in-a-variable-using-jquery

This referenced a source of w3 schools, but that link no longer seems to work:
http://www.w3schools.com/dom/dom_errors.asp

Now updated to support FileMaker 16.

Read more here:
http://www.soliantconsulting.com/blog/2017/06/filemaker-16-javascript-changes