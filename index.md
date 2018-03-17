# Introduction
Thank you for your interest in helping our research. The guidelines listed here are designed to help enhance your experience as well as improve the quality and consistency of your results. The goal of your task is to determine whether or not a celebrity has sufficient distinct images.

 1. [Interface](#Interface)
 2. [Objective](#Instruction)
 3. [Things to keep in mind](#Note)

### Requirements

  - A stable internet connection.
  - A laptop or desktop computer with an up-to-date browser of your choice. 

### To begin

  - Open a browser and go to [`annotate.altumview.com`](http://annotate.altumview.com/ "Remember this URL"). This is the website that you will use to do the annotations.
  - You will be given parts that you are to annotate. Use the navigation panel at the top right of the [`annotate.altumview.com`](http://annotate.altumview.com/ "Bookmark it maybe") page to go to the parts that you are responsible for.
 
# <a name="Interface"></a>Interface


![alt text](img/Interface.png)

The UI consists of several parts that each have their own uses. I will break them down below and explain what each part is for.
  1. The top left section of the page indicates whether or not a subject has been annotated. When this is empty, it means that no response has been recorded for the current subject. When you submit, a dialogue box will appear in this section to show you what you have submitted.

  2. The top middle section of the page contains information about the subject that the images are displayed of. Use this information to help decide whether or not a subject has sufficient distinct images.
	  - `Celebrity #`: The index of the subject.
	  - `Celebrity name`: Name of the subject.
	  - `# of pictures`: The total number of pictures that this subject has.
	  - `Ratio of pictures`: Selected images / total number of images.
	  - `Percentage`: The percentage of images that are not selected. Ratio of pictures multiplied by 100.
  3. The top right section of the page contains a navigation panel. You can type in an index number and press the navigate button to tell the page to display the images of the subject at that index number. 

  4. The middle of the page is where all the images are displayed. You can scroll with your cursor inside this section to load more images. The total number of images is shown in the information section. 
 5. For each image, there is a button in the top left corner when you hover over the image. You can press this button to open a new tab in your browser with an enlarged version of the image.
	  - You can click on the image itself to mark or unmark it. This will modify the opacity of the image, `ratio of pictures` and `Percentage`.
  6. The leftmost and rightmost buttons in the bottom of the page will respectively bring up the subject at one index lower or higher than the current index shown. 
 7. Residing in the bottom middle of the page are the submit buttons. The green `Good` button will annotate the current subject as having sufficient distinct images, and the red `Bad` button will annotate the current subject as the opposite. 

# <a name="Instruction"></a>Objective
  - For each subject, you are to determine whether the **subject is asian** and falls in one of the following groups: 
	  - If **more than 90% of the images** shown for a celebrity subject belongs to a single face identity, then click the green `Very Good` button.
	  - If **more than 80% and less than 90% of the images** shown for a celebrity subject belongs to a single face identity, then click the yellow `Good` button.
	  - Otherwise, click the red `Bad` button.
		  - If the subject is non-asian, you can submit `Bad` right away.
		  - If the subject has less than or equal to 20 total number of images, then it is `Bad`.
  - You can select an image that you think is not representative of the main identity. Doing this will modify the `Percentage` information. You can use this information to help you in your objective. Images that may satisfy this condition include:
	  - Image with no faces to identify. 
	  - Image with very poor quality or the subject is too far away.
	  - Image with a face that does not look like the main identity.
  - Generally speaking, if you can recognize the main identity in the image then you don't want to mark it. For example:
	  - The subject has makeup on, but you can recognize her because of her lips and nose features.
	  - The subject is wearing sunglasses, but you can recognize his chin and smile. 
	  - A drawing or animated image that is realistically similar to the main identity. 

# <a name="Note"></a>Things to keep in mind
  - A scenario that happens frequently is that the subject will fail the condition before needing to see all the images. 
	  - Going through each image carefully allows you to save time on a subject when this scenario happens. Skimming will have the opposite effect and a worse result as often times you will feel the need to look through the same set of images again and you might still miss some images that are not suppose to be in the set.
	  - If you cannot determine the main identity of the subject from the first 10~20 pictures, then it is likely that the subject will fail before needing to verify every picture. What you can do in this case is skim through some more images to see if you still cannot identify the main identity. If so, then this subject has failed the condition. 
  - Only the response from submit buttons are recorded. You can submit multiple times. Only the last submit is recorded.
  - The website saves the progress for you provided that you are not using the browser in incognito mode or you keep your browsing data. You can close/refresh the web page to still arrive at where you left off.
  - Otherwise, remember the index number so that you can resume progress using the navigation bar.
  - Always submit a response before going to the next subject. This will prevent missing responses.
  - Make sure to record your time in the time sheet every time you start working.
  - Don't hesitate to reach out to me when you are uncertain of anything. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbNTAzMjQ1NjI0LC0xNDMzNjE2MDM0XX0=
-->