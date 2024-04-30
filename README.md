# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<head>
<title>Agri Search Engine</title>
</head>
<body>
<h3>
WHEAT CROP:
<br>
<a href="https://en.wikipedia.org/wiki/Wheat">
<img src="C:\Users\Hephzibah\wheat.jpeg" height="200" width="200">
</a>
<br>
<br>
WEEDER:
<br>
<a href="https://www.google.com/search?q=weeder+information&sca_esv=568821e4bd74bee9&sca_upv=1&rlz=1C1ONGR_enIN1098IN1099&biw=1536&bih=730&sxsrf=ACQVn0_Sq5xQ5RSHpxtgDWOwWvJUj4RpJA%3A1714499795111&ei=0zAxZrCxBq35seMP8ouW-As&ved=0ahUKEwjw5oS6weqFAxWtfGwGHfKFBb8Q4dUDCBA&uact=5&oq=weeder+information&gs_lp=Egxnd3Mtd2l6LXNlcnAiEndlZWRlciBpbmZvcm1hdGlvbjIGEAAYBxgeMggQABgIGB4YDzIGEAAYCBgeMgsQABiABBiGAxiKBTILEAAYgAQYhgMYigUyCxAAGIAEGIYDGIoFMgsQABiABBiGAxiKBTIIEAAYgAQYogQyCBAAGIAEGKIEMggQABiABBiiBEiUVVCHLljRSnACeAGQAQGYAdUEoAGkHqoBCzAuMi40LjMuMi4xuAEDyAEA-AEBmAIGoAKDB8ICChAAGLADGNYEGEfCAg0QABiABBiwAxhDGIoFwgIOEAAYgAQYkQIYsQMYigXCAgoQABgHGAgYHhgPwgIIEAAYBxgIGB6YAwCIBgGQBgqSBwUyLjEuM6AH5lA&sclient=gws-wiz-serp">
<img src="C:\Users\Hephzibah\WEEDER.jpeg" height="200" width="200">
</a>
<br>
<br>
ORGANIC FERTILIZER:
<br>
<a href="https://en.wikipedia.org/wiki/Organic_fertilizer">
<img src="C:\Users\Hephzibah\organic fertilizer.jpeg"height="200" width="200">
</a>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (7).png>)
![alt text](<Screenshot (6).png>)
## RESULT
 Images as hyperlinks is implemented successfully.
