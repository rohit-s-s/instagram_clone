# **Instagram Frontend Development**

This project is aimed at replicating the Instagram frontend using HTML and CSS.

## Getting Started
Clone the repository to your local machine using the following command:

<div>
  <span id="link-text">https://github.com/rohit-s-s/insta_clone.git</span>
  <button onclick="copyLink()">Copy</button>
</div>

<script>
function copyLink() {
  var linkText = document.getElementById("link-text");
  var range = document.createRange();
  range.selectNode(linkText);
  window.getSelection().removeAllRanges();
  window.getSelection().addRange(range);
  document.execCommand("copy");
  window.getSelection().removeAllRanges();
}
</script>


Open the index.html file in your browser to view the Instagram homepage.

Start editing the HTML and CSS files to make changes to the Instagram frontend.

## Folder Structure
The project folder is structured as follows:

insta_clone/
├── images/
├── style.css
├── index.html
└── README.md

images/ - Contains the images used in the project, such as the Instagram logo and profile pictures.
style.css/ - Contains the styling the for Instagram frontend.
index.html - The main HTML file that displays the Instagram homepage.
README.md - The README file for the project.

## Contributing
This project is open to contributions. If you find any issues or have suggestions for improvements, feel free to open a pull request.

## Credits

Special thanks to CodeSandbox for providing the development environment.