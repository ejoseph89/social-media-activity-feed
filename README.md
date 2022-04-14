# Social media news feed - Code challenge  

## Link to the deployed project: [Social Media News Feed](https://ejoseph89-social-media-newsfeed.netlify.app/)  


### Details  
--- 

#### Built with:  
- HTML
- SASS
- JS  
 
#### Installation
1. Clone the repo  
   git clone https://github.com/ejoseph89/social-media-activity-feed.git  
2. Install NPM packages  
   npm install  
3. Run dev server  
   npm start  
   ctrl + click link in terminal to open in browser  
4. Run build command - build version will be in the dist folder
   npm run build  



### Usage  
---  

##### Using The Required Features  
1. Once dev server is running, click the '+' icon on the footer to open the post modal.  
2. To activate the 'Post' button, enter content in the textarea, or upload an image by clicking 'Share an image', or both to make a post with text and image.  
3. To make the post, click 'Post' button once there is content in textarea, and/or an image is uploaded.  
4. To remove an uploaded image, click 'Remove file' that appears if an image is successfully uploaded.
5. To cancel making the post and exit, click 'Cancel'.  



### Features  
---  

##### Key Features
- The app lets a user add a post by clicking the '+' button.  
- The modal that opens has a form that lets the user make a text post, and/or upload an image.    
- If the image is successfuly uploaded, the modal will have a notification that confirms a successful upload.  
- Once uploaded, the user will have the option to remove the file, essentially cancelling the upload.  
- If there is content in the textare (text post), or an image is uploaded, then the 'Post' button will be activated.  
- If there is no text content, or an image file uploaded, the 'Post' button will be disabled - empty posts cannot be make.  
- At any point in the process of a making a post, the user can click 'Cancel' and close the modal and clear content.  
- A successful post will be posted at the top of the post list, and the screen will scroll to the top.  
- Date formatted as required, with the exact time of the post as well.  

##### UX Considerations  
- I've placed the post modal (form to add a new post) at the most accessible location (for left or right handed people), towards the bottom of the viewport. 
- Towards the top left of the screen is where the hamburget icon is, which will open the main navigation bar.  This follows the common convention.  
  - This menu can have general settings of the app.  
- To the right corner is a button styled as a profile icon, which can have more personalized settings - profile, preferences etc.  
- In between these two buttons is a search bar, which can be used to look up people, communities, posts etc.  
- To the bottom of the top nav bar is another navigation, which can let users sort posts based on whats trending, or what's live.  
- Not allowing an empty post - by disabiling the 'Post' button if there is no post or image. 
- Auto scroll to the top of the viewport once a new post is made.  
- Allowing users to remove uploaded image
- Allowing users to cancel and exit from making a post
- Closing the post modal when the 'Home' button on the footer is clicked. 
- Allowing 'Swipe left' to close the nav, when the hamburger navigation is open. 
- Not allowing both the Hamburget menu and post modal to be open at the same time. 
- Spacing between menu items, buttons are considered for mobile use.  

##### Potential improvements  
- Animations and transitions to make the user experience more enjoyable, and changes more subtle.  
- Proceeding with an object oriented approach for the UI (like the Post Class), where all UI related functions are together.  
- Giving more consideration to performance and accessibility.  



### Contact  
---  
Emil Joseph - (emiljoseph@gmail.com) (https://www.emiljoseph.io)  
Project link - (https://ejoseph89-social-media-newsfeed.netlify.app/)  
