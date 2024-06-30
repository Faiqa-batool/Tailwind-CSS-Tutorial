# Tailwind-CSS-Tutorial
A step by step complete guide on how to set up Tailwind css and create an example Tailwind css project

## Steps:

•	Make an empty folder for tailwind css learning, open in vscode. </br>
</br>
•	In terminal, write npx tailwindcss init  </br>
//it will create a file : tailwind.config.js </br>
//make sure, you have already installed node.js </br>
</br>
•	Create build/index.html</br>
•	Create src/ </br>
</br>
•	In tailwind.config.js, in content: [‘.build/*.html’] </br>
//This means apply the Tailwind css on all the '.html' files in 'build' folder.
</br>
</br>
•	Create src/input.css, and paste this </br>
@tailwind base; </br>
@tailwind components; </br>
@tailwind utilities; </br>

/* we can define our own tailwindcss classes here */
</br>
</br>
•	Then in terminal, write this: </br>
npx tailwindcss -i ./src/input.css -o ./build/css/style.css

•	./build/css/style.css is created and it has some css code
</br></br>
•	Link that file with your index.html
</br>
•	In index.html, in <body> tag, write div.bg-emerald-500.w-52.h-52 and enter.   
// this is a tailwindcss class </br>
</br>
•	In terminal, write : npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch </br>
By using this, the code is running, and open in live server. 
</br></br>
•	Install Tailwind css intellisence extension for better view of the html code.
</br></br>
• You can also define your custom Tailwindcss classes. </br>
</br>
•	So while using tailwind css, you only need to write the class name with the tag name, and the functionality is applied to it, just search what you want to do to on the tailwind css website and write it in the tag.

## Here is an example Tailwind css project:


![Bull's Eye using Tailwind css](https://github.com/Faiqa-batool/Tailwind-CSS-Tutorial/assets/115587465/c302cacb-b818-49d9-a39a-60652030a2dc)


