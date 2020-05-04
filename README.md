# Cvision.ai-Internship-Assignment
<h5> Name: Shyam Sundar </h5>
<h5> email: <a href = "mailto:shyam.sk1998@gmail.com"> shyam.sk1998@gmail.com </a> </h5>
<h4> Approach </h4>
<p>
In this project, I have used pytesseract which is a python wrapper for <a href = "https://github.com/tesseract-ocr/tesseract/">  Google’s Tesseract-OCR Engine </a> which will recognize and “read” the text embedded in images. After pre-processing the images and extracting the text, I used some pattern matching techniques to extract information such as Registration No, Chassis No, Engine No, Registration Date and MFG Date. Extracting names was a pretty challenging task, since there wasn't a pattern, so I downloaded an Indian names database and matched with it instead. After getting all the information, I dumped it into a pandas dataframe and converted it to an excel sheet. 
</p>

<h4> Requirements </h4>
  <ul> 
    <li> <a href = "https://pypi.org/project/pytesseract/"> pytesseract </a> </li>
    <li> OpenCV </li>
    <li> NumPy </li>
    <li> Pandas </li>
  </ul>

<h4> Instructions </h4>
  <ol>
  <li> Download the project and open <b> "OCR.ipynb" </b> using Jupyter Notebook and specify the paths (in the second cell) for the following: Indian-Male-Names.csv, Indian-Female-Names.csv, dataset folder and tesseract.exe. </li>
  <li> Run the cells. </li>
  <li> A file named <b> OCR_output.xlsx </b> will be saved in the current directory. </li>
  </ol>
