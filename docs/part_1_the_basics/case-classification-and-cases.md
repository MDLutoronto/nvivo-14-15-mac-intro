---
created_date: 2023-11-20
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Case Classification and Cases
parent: Part 1 - The Basics
nav_order: 7
layout: default
---
Case Classification and Cases
-----------------------------

If you have demographics or other important attributes that you want to incorporate into your study, case classifications and cases can help. For example, if you were analyzing interview transcripts, you might want to create a case classification called “Interviewees” with attributes such as their name, age, education, job title, etc. Once your case classification is in place that defines what characteristics you want to capture for your interviewees, you could then create one case for each interviewee with those attributes filled in. So for example, if you interviewed someone named Geeta, you would create a case called Geeta (or some ID number if needed for confidentiality) with information about Geeta. You would then use that Geeta case to code all the files/content that are associated with Geeta (where the Case acts like a Code). Later you can then run queries that incorporate that information to answer questions such as, do executives talk more about sustainability? We will talk about how to run queries later in the tutorial.

You can manually create case classifications and cases, but often times, it is easier and more common to upload a spreadsheet with all the information for the cases. Let’s try that now.

1. For our project, we have a file called Interviewees.csv. Open it up and take a look. It lists our interviewees and their attributes. Attributes in NVivo work best when they are categorical variables. NVivo would call this a classification sheet. Now close it and go back to NVivo.

    <img src="{{ '/assets/images/nvivo_workshop_mac_070.png' | relative_url }}" alt='Interviewees spreadsheet opened in Microsoft excel' title='' width='600' height='363' />

2. Go to the Import menu,and from the **Classification drop\-down menu, select Classification Sheet...** (You can also go to the **Home menu**, and from the **Case Classification drop\-down menu, select Import Classification Sheet)**.

    <img src="{{ '/assets/images/ScreenshotImportClassificationSheet.png' | relative_url }}" alt='The import menu is highlighted, along with the Classifications submenu and Classification sheet option.' title='' width='1312' height='308' />

3. **Browse to the Interviewees.csv file** and **click on Open**.

    <img src="{{ '/assets/images/NVivo15_Mac_intro_077.png' | relative_url }}" alt='Finder with Workshop Files opened and Interviewees.csv selected. Open highlighted.' title='' width='1766' height='1188' />

4. From the Classification Type drop\-down menu, **make sure it says Case Classification**. Next for **Create new classification, type in “Interviewees”** (to give it that name) and then keep the rest of the defaults (where there should just be a checkmark next to Create new attributes if they do not exist) and **click on Next**.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_4.png' | relative_url }}" alt='Import Classification Window with the classification type set to Case Classification. Beside For text files Create new classification selected and Interviewees entered. Box checked off for Create new attributes if they do not exist. Red box around Next.' title='' width='647' height='477' />

5. Our classification sheet’s first column provides the name of each case (i.e., the interviewee’s first name). Keep the defaults here (where there should be a checkmark next to 'Create new cases if they do not exist') and then **click on Next**.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_5.png' | relative_url }}" alt='Import Classification Window with box checked off for Create new Cases if they do not exist. Next highlighted.' title='' width='609' height='449' />

6. Then **click on Import**. It should open up the newly created Interviewees case classification sheet and attributes.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_6.png' | relative_url }}" alt='Import Classification Window with Import highlighted.' title='' width='617' height='456' />

7. **Click on Classification Sheet** at the top of that window to see something that resembles the csv file we imported. Then close it.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_7.png' | relative_url }}" alt='Imported classification sheet opened in NVivo.' title='' width='792' height='363' />

8. From the left menu, **under Cases, click on Cases** to see our newly created cases. These cases can now be used in coding the same way codes are used.

    <img src="{{ '/assets/images/NVivo15_Mac_intro_082.png' | relative_url }}" alt='Left menu Cases opened and a red box around the Cases list' title='' width='783' height='577' />

9. We can take advantage of NVivo’s autocoding features to allow us to identify the interviewee’s responses in a file and code them automatically into the appropriate case. From the left menu, under **Files,** **select Interviews.** **Hold down the Control key and click on the “Data Center Interview Transcript oct3\_2014” file** and **select Autocode**, and then **select By Speaker**…

    <img src="{{ '/assets/images/NVivo15_Mac_intro_083.png' | relative_url }}" alt='In the interviews folder, a context menu for the last transcript is open. Auto Code highlighted and its side pop-up menu open with by By Speaker... outlined in red.' title='' width='2014' height='1386' />

10. First, make sure that under **What would you like to classify your cases as?** it has **Existing classification \> Interviewees** selected.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_10.png' | relative_url }}" alt='Auto Code window with What would you like to classify your cases as? highlighted in red. Under it Existing classification is selected with Interviewees picked from the drop-down menu. ' title='' width='712' height='468' />

11. Next, our transcripts are formatted in a consistent manner so we can always pick out who is speaking because the text is labeled as “INT:” for the interviewer’s words, and the person’s name in capital letters followed by a colon for the interviewee’s words. We need to tell NVivo who are all the unique speakers in this document. Under "Enter the names of the speakers. These will become your cases.", **type in “INT”** **and hit Enter**. Then **type in BASEL** **and** **hit the TAB key**. You should check the preview on the right to confirm that NVivo is picking up each unique speaker by highlighting them in different colours. If it looks correct, **click on Autocode**. This should code everything that Basel said in the transcript with Basel’s case.

    <img src="{{ '/assets/images/NVIVO_MAC_Case%20Classification_11.png' | relative_url }}" alt='Under Enter the names of the speakers, INT and BASEL have been entered. On the right the interview text has been assigned corresponding colors according to the speaker. Both areas are outlined in Red. Auto Code is highlighted.' title='' width='694' height='457' />

12. From the left menu, **under Cases, click on Cases**. Then **double click on Basel**. You should see everything that Basel said in his interview. These words are coded to this case. The BASEL case code is now linked to Basel’s interview responses.

    <img src="{{ '/assets/images/NVivo15_Mac_intro_086.png' | relative_url }}" alt='Cases open with Basel selected and a red box around the Basel window.' title='' width='2880' height='1240' />

**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo) 