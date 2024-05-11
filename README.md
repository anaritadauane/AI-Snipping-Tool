# Problem Statement

 We often need to type out text from videos, images, or thumbnails on websites. This can be a tedious and error-prone process, especially if the text is long or has tricky stuff like website links, technical words, code examples, or math equations. This issue comes up on YouTube, where useful info is shown in videos or thumbnail images.

## Some of the scenarios where this problem arises:
![Screenshot 2024-05-11 050941](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/325fe373-5215-4602-b582-1e2d3e91d96c)

### In the MrBeast Riddle video, he displays a YouTube link to visit as part of the riddle, but manually typing the link is inefficient and prone to errors.





![Screenshot 2024-05-11 050949](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/29019305-a63d-4443-89e8-2a67265befbe)

### A math lecture video full of complex equations in Laplacian notation. Typing or searching would be a total pain.


![image](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/1d84b1e5-6e1e-49b4-aefc-3482b74f29d6)
<br>
### Copying of code to the editor directly is not possible.

# Proposed Solution

![logo](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/121ddde6-77ed-4dad-b9ff-7da6ddffdb38)



## We propose to develop a Chrome extension {AI Screenshot}:



- ### Custom Area Screenshot: Select any area of a webpage/video to screenshot. This will allow to extract images from a particular part of the image. This will allow us to extract hyperlinks, code, complex equations, etc. 

- ### Webpage Summary: Summarize text from a screenshot capture of any webpage in the user-chosen language (MultiModal).
- ### YouTube Video Screenshot: Capture text in the current video frame on the YouTube website. (Not Implemented)
<br>
![Screenshot 2024-05-11 121827](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/000736d9-2311-41ca-b9e3-30d530720bb6)
Working and Tech Stack


# Tech Stack
- HTML (frontend)
- Tailwind CSS (frontend)
- JavaScript (Backend)
- Tesseract (OCR recognition)
- Google Gemini API (LLM (AI) for summarization)










 #    Working

Our Chrome extension is utilizing Tesseract OCR for character recognition in the image and Google Gemini API is used for summarization of text.

 
Similarly, if the user chooses to summarize the webpage then it will also be done with the help of Google Gemini.
All the summarized extracted text is sent back to the Chrome extension popup window for display and coping.


> About Google Gemini: Gemini is the latest and best Large Language Model developed by Google. It can perform any task related to natural language (text) and is also capable of code and image generation.
It also allows developers to use its API to develop AI apps as we proposed here.

> Tesseract OCR: It is an open-source optical character recognition (OCR) engine developed by Google. It is designed to extract text from images and documents without a text layer, outputting the document in various formats such as plain text, HTML, PDF, and more. Tesseract supports recognition of over 100 languages "out of the box" and is highly customizable


# Future Scope
![image](https://github.com/gitgoap/HackFest-24-IIT-Dhanbad/assets/117789470/1592f070-2e07-436b-b268-dc25be5e8e53)
### Answers questions just with a screenshot















 
 




