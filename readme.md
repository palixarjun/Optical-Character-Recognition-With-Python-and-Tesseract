# Mult-Lingual OCR System: OpenCV and PyTesseract Approach
![ocr system](/decorative-elements/ocr-dg-00.png)

## Side Note
- This is an Optical Character Recognition System can recognise multiple languages. The multi-lingual OCR system is Jupyter Notebook based, dependent with OpenCV and Pytesseract module.

- The test data sets (images) can be used to for assessing different models language models (Eg. English, Hindi, Tamil, Portuguese and Urdu).

- Additional language models can be added to the system and thus adaptable to requirements. 

- The input fed to the system not only is limited to .png, but can work with .jpg, .jpeg, .gif etc. For the uniformity of the data sets, .png extension files were used.

## Output
![output](/output-preview/output-08.png)
This output represents that the system identifies the characters' position in the input file (png) and segments them, creating and combining characters to create words. The system is not AI based thus it lacks the ability to assess and create meaningful words. The system only recognises the text character by character and join them.

**Principle:** to recognise the characters, combine them and output them as a string.

## Future Scopes and Additional Improvements
- Improving the accuracy and training the data set. 

- Many languages were depreciated in the newer versions and required to be trained for the usability with tesseract 5.0 and higher versions. (The older datasets are compatible with 3.0 versions)

- The system only recognises the character based on language model and lacks the ability for translation between inter languages. Addition of translation features can be a significant improvement.

- Real time character recognition and dynamic input feed in the system can be implemented. Dynamic inputs can be provided by real-time images captured using cameras, or so live images which are not captured but being visible on the screen.

![credits and footer](/decorative-elements/ocr-dg-09.png)