# foodinfo
Identification of additives and preservatives in packaged foods using python and image processing
Food is an essential element for all living organisms. Processed foods have a very 
limited life, in order to preserve them for a longer time and to have good flavor, texture, and 
taste, food additives and preservatives are used. This study is taken to investigate the effects of 
food additives and preservatives on human health and did research on different Optical 
Character Recognition (OCR) algorithms. In this project, we propose an OCR-based algorithm 
to identify food additives and preservatives in packaged foods by analyzing the contents of the 
package and finding their effect on human health. Here, the image of the contents of the 
package is applied to Image enhancement techniques such as to increase the accuracy of the 
OCR. The Google Cloud Vision API detects text from enhanced images based on CNN with 
high accuracy. The extracted text is filtered to remove undesirable words using RegEx. The 
filtered keywords are used to search in the predefined dataset where data is taken from the 
Standard Food Safety Organizations such as FDA and FSSAI. By using Google Cloud Vision 
API, we can extract text with an accuracy of 99.1%
