# IXHELL. A literal cheat code for online homework.

I've just spent about 2 months making this script, which helps people automatically do IXL. IXL is often used by teachers/parents to assign homework, and I was a victim, and as one of the "nerds" in my class who are known for hacking stuff, I compiled this because no one had a working script to do this. Enjoy my 2 months of time to save many hours of your time!

# How does it work? Is it patchable by IXL?
Short Answer: No. It cannot be patched by IXL.
Long Answer: No. It cannot be patched by IXL because my script uses Tesserat's OCR (Optical Charecter Recognition) to grab all text off of a certain area of the screen, then uses Aria/ChatGPT to solve it, then copy and paste the answer with PyAutoGUI

# What You Will Need
- How to download stuff 
- How to troubleshoot 
- At least 500MB free space 
- A decent internet connection 
- Common Sense 

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
9. Edit my Python script with Notepad and change the path to Tesseract to your install of Tesseract's executable.
10. Log in to IXL, pick a skill and run my python script
11. Enjoy some semi-automatic doing of your homework!

# Limitations
Of course, there are some limitations. Currently, you can only use IXHELL to do word problems in Math. There is NO current way to do image based questions. (due to AI limitations)
There is also currently no way to do those questions which ask you to select an answer, but support for those may be coming soon.

# What To Expect
It takes about 10-25 seconds per question. One IXL is about 20 questions, and 20*20 is 400. 400 seconds = about 6.5 minutes. Pretty fast for automatically doing a dynamically changing thing, with almost 100% accuracy rate due to the use of AI. May change depending on your Internet and your Computer Specs

