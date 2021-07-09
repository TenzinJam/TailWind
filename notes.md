[] class="text-color-strength" for text colors
[] class="text-size" for text size (in place of size you'd write the text size of your desire. Check documentation for all the size options.)

[] another important pro-tip is the tailwind config file. refer to documentation to run the command for creating that file.
Once you have the config file, you can make the changes and for the app to integrate changes into the main source css, you have to run the npm run build-css command for that to happen.

[] However, making changes directly in the config file is not recommended because we want to keep track of which values are defaults and which ones we created.
So, rename the first config file so that it is a regular js file and run the commang again to create a tailwind config file. Now make the changes in there. Remember to use the

[] using tailwindd css intellisense for autosuggestion of styling, such as colors, font, and others

[] in Tailwind we do not need to manually create any media querries at all. 
