# self-attest-india
When you need to sign hundreds of pages, and the bureaucrats are going to give you hand cramps.

## What are you talking about?

This: https://legaldesk.com/general/what-is-self-attestation

## OK, how does this help?

Indian law sometimes requires self-attestation. You take a digital copy of your documents (whether an ID, passport, etc) and you sign in blue ink, partially across the picture and off into the whitespace.

Here's a faster way to get your self-attestation done. We'll call it machine-assisted self-attestation.

## Usage
- Clone this, and drop some images into the folder alongside Document.html
- Adjust the list of images inside Document.html
```
let images = [
    'IMG_0001.JPG',
    'IMG_0002.JPG',
    'IMG_0003.JPG',
    'IMG_0004.JPG'
]
```
- Save your "John Hancock" in place of the signature_alpha.png file
    - **IMPORTANT**: make sure it's a PNG file with transparency.
    - (The easiest way to do this is to take a high-res photo of your signature on a white piece of paper. Then in a tool like Photoshop or Gimp, select by color all the white pixels and cut them from the iamge. Save/export as PNG. An example: https://www.youtube.com/watch?reload=9&v=efAOsvfi4sU )
- Open the file in Chrome, File->Print, and 🎉 you have self-attested documents!
    - (sample in the Sample Output.pdf file)

It's handy to combine with digital scan services like http://lookslikescanned.com/ . You can really convince them that you killed a bunch of trees to produce this document. 😉

**IMPORTANT** never upload sensitive info in a document to a public site, such as your SSN, bank or tax info, etc.
