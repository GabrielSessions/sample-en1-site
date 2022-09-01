# sample-en1-site
## How to Modify this Template
1. Clone the code from this repository. Click the green Code button above and either download as a zip, open in GitHub Desktop, or clone to an online IDE.
2. Unzip and extract the source files (if applicable).
3. Delete the firebase files included in the sample project, firebase.json and .firebaserc
4. Open the project folder in a IDE/Text Editor and start coding! Comments are included inside index.html and project1.html to help you get started.

This project uses [Bootstrap](https://getbootstrap.com/). Feel free to copy/paste pre-made components into your project!

## Cloning the Template
If you would like to clone the entire project, run `git clone https://github.com/GabrielSessions/sample-en1-site`

If you're interested in copying a single page, run `wget -p <PAGE LINK>`

## Template Preview
https://gabrielsessions.github.io/sample-en1-site/

## Adding text, images, and video to your site
### Headings
`<h1>Heading Type 1</h1>`
> # Heading Type 1

`<h2>Heading Type 2</h2>`
> ## Heading Type 2

`<h3>Heading Type 3</h3>`
> ### Heading Type 3

`<h4>Heading Type 4</h4>`
> #### Heading Type 4

`<h5>Heading Type 5</h5>`
> ##### Heading Type 5

`<h6>Heading Type 6</h6>`
> ###### Heading Type 6

### Paragraph Text
`<p>Here's a single paragraph of text</p>`

`<p>Here's another paragraph of text</p>`

> Here's a single paragraph of text

> Here's another paragraph of text

### Adding Images
General format: `<img src="PATH_TO_FILE" alt="Description of the image" />`

If you had an image called "landscape.img" in the same folder as the .html file, the image could be added like this:

`<img src="landscape.img" alt="Mountainous, grassy landscape" />`

Or with a link to the image:

`<img src="https://media.istockphoto.com/photos/mountain-landscape-picture-id517188688?k=20&m=517188688&s=612x612&w=0&h=i38qBm2P-6V4vZVEaMy_TaTEaoCMkYhvLCysE7yJQ5Q=" alt="Mountainous, grassy landscape" />`

> <img src="https://media.istockphoto.com/photos/mountain-landscape-picture-id517188688?k=20&m=517188688&s=612x612&w=0&h=i38qBm2P-6V4vZVEaMy_TaTEaoCMkYhvLCysE7yJQ5Q=" alt="Mountainous, grassy landscape" />

You can also change the size of the image using the width and height attributes:

`<img src="https://media.istockphoto.com/photos/mountain-landscape-picture-id517188688?k=20&m=517188688&s=612x612&w=0&h=i38qBm2P-6V4vZVEaMy_TaTEaoCMkYhvLCysE7yJQ5Q=" alt="Mountainous, grassy landscape" height="300px" width="500px" />`

> <img src="https://media.istockphoto.com/photos/mountain-landscape-picture-id517188688?k=20&m=517188688&s=612x612&w=0&h=i38qBm2P-6V4vZVEaMy_TaTEaoCMkYhvLCysE7yJQ5Q=" alt="Mountainous, grassy landscape" height="300px" width="500px" />

### Adding Video
1. Upload a video to Google Drive
2. Open the uploaded video file
3. Click on the three dots in the upper right hand corner and select "Share". Change the general access settings to "Anyone with a link".
3. Click on the three dots in the upper right hand corner again and select "Open in new window"
4. Click on the three dots in the new page and select "Embed item". Copy the code that appears in the popup, it should look like this:

`<iframe src="https://drive.google.com/file/d/1N9CAy_vebTqaG8L0TU5zcETAoCRS9_Vq/preview" width="640" height="480" allow="autoplay"></iframe>`

5. Add this code into your HTML, you should see a Google Drive video appear.

### Adding Code

`<pre>print("hello world!")</pre>`

> <pre>print("hello world!")</pre>

Code box with rounded edges and a gray background:

`<pre style="border-radius: 25px; background: #cfcfcf; padding: 20px;">print('hello world!')</pre>`

> <pre style="border-radius: 25px; background: #cfcfcf; padding: 20px;">print('hello world!')</pre>
