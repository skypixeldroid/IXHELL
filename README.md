# IXHELL. A literal cheat code for online homework.

I've just spent about 2 months making this script, which helps people automatically do IXL. IXL is often used by teachers/parents to assign homework, and I was a victim. I hate it SO much, that I compiled this because no one had a working script to do this. Enjoy my 2 months of time to save many hours of your time!

# How does it work? Is it patchable by IXL?
Short Answer: No. It cannot be patched by IXL.
Long Answer: No. It cannot be patched by IXL because my script uses Tesserat's OCR (Optical Charecter Recognition) to grab all text off of a certain area of the screen, then uses Aria/ChatGPT to solve it, then copy and paste the answer with PyAutoGUI

# How do I install it?
Simple Steps:
1. Download Opera (If you haven't)
2. Download Python (Version 3.xx At least)
3. Install PyAutoGUI (<code>pip install PyAutoGUI</code>) [Needed for basic functions]
4. Install Tesseract (<code>pip install PyTesseract</code>) [Needed for Optical Charecter Recognition]
5. Install Pillow (<code>pip install pillow</code>) [Needed for taking screenshot]
6. Install PyperClip (<code>pip install PyperClip</code>) [Normally included with PyAutoGUI, but try again anyway]
7. Install the standby app for Tesseract (Downloadable here: https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-5.3.3.20231005.exe)
8. Log in to an Opera account, and use Aria (in the sidebar) at least once.
9. Log in to IXL, pick a skill and run my python script
10. Enjoy some semi-automatic doing of your homework!

# Limitations
Of course, there are some limitations. Currently, you can only use IXHELL to do word problems in Math. There is NO current way to do image based questions. (due to AI limitations)
There is also currently no way to do those questions which ask you to select an answer, but support for those may be coming soon.

