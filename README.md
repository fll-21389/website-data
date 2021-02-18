# website-data
This is where the website code is stored and updated. If you are here for our Sharktank website, please navigate to the /sharktank directory, located off the main branch.

# NOTICE
__This website is published universally and any update to it will cause the change to be rolled out worldwide. Please make sure that everything you update is stuff you want posted on the internet.__

## Updating the code
To update the code, open the file in a text editor such as VS Code, Notepad++, etc.

If you update HTML files, please update the respective file. Make sure you know the syntax and preferably know the format I originally wrote it in. This helps keep it cleaner and easier to review later.

If you need to add styling, please make sure you add it to the *style.css* file and, if required, link that css file to the HTML file you are using. Please check if there is this line at the beginning of the HTML document:
##### link rel="stylesheet" type="text/css" href="/resources/style.css"
If this line is not at the beginning, please add it with "<" at the beginning of the line and ">" at the end.

## Adding images, videos, etc.
If you want to add images, please add them to the *resources* folder and then reference them in the file that you are editing. This way images are all in one place and can easily be found and re-referenced if needed.
