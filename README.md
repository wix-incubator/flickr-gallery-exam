# Flickr Gallery

Welcome to the Flickr Gallery application.
This app is simple, you write a tag at the top and you get images from flickr with that tag.

## Before Starting the Test
Please make sure you've read the job description - [Student Software Developer](https://www.wix.com/jobs/locations/tel-aviv/positions/2467) and that you are indeed interested in this position and all its terms.

## Getting Started
To set up the test environment and get this app running locally all you need to do is:
1. Create a new [Bitbucket](bitbucket.org) account
2. Create a new private repository in Bitbucket - use the import repository option, use this repo URL https://github.com/wix-incubator/flickr-gallery-exam
3. In the created folder install the node modules `npm install`
4. Run the app `npm start`
5. Your local app should be available at `http://localhost:8000`

## Your Tasks
This project includes several tasks for different skill levels. You may try completing them all but if you are new to web development, complete the tasks that are a bit above your level.
You can and should learn new skills during the process, you may consult with Google and friends but you will need to explain why you implemented what you implemented, so be responsible for your code.
*Important:* please make sure to commit after each task - for example, after finishing task 1 delete, commmit the files with a relevant message: "task 1 - delete image", and so on.


### Task 1 - Image Actions
Each image has three buttons that appear on mouse hover. You need to make them work.
1. Delete: clicking the delete button should remove the image from the display. 
2. Rotate: each click should rotate the image by 90 degrees.

#### Bonus:
3. Expand: clicking an image should display this image in a larger view.

### Task 2 - Gallery Actions
1. Responsive:  the gallery adjusts the size of each image so that all the images will fit into the screen without margin. However, when the window is resized, the images are not fitted so well. Make sure the images are always adjusted to the window width.
2. Infinite Scroll: currently the gallery displays only 100 images. Create a mechanism that loads more images from flickr when the user is scrolling past the last image.

#### Bonus:
3. Drag & Drop: let your users choose the order of the images by adding an option to drag & drop images to their new position.

## Tips / Notes
- All the code you'll change / add will be in the `/src/components` folder.
- You don't need to complete all tasks. If you are new to web development, finish only the easy tasks. If you have the required skills, try to complete the intermediate and hard tasks too.
- If possible, write tests for every new feature you write (tests are written in spec.js files)
- Think about the product you create, try inovating the user interface, you don't have to create the exact solution as it is in the video, or even the exacts tasks. **be creative, creative is good**.

#### Remember: this test is designed to see how you complete tasks that require self learning, not to test your existing knowledge.

## Submitting your project
After you've completed your tasks, and you are ready to submit it, do the following:
1. Make sure all the code is committed and pushed
2. Add "students-fed-exam@wix.com" as an user to the repo
3. Send us an email with your repo link
4. Profit!


## Good Luck!
![Break a leg](https://media0.giphy.com/media/aHs1EAnUAxYgU/giphy.gif)
