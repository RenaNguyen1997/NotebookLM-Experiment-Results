# Experiment 1: Source Management Functionality
### **Objectives** 
Through this experiment, we aim to assess NotebookLM's capabilities in handling different file formats and its efficiency in managing updates and visual content.

---

### **Method** 
While NotebookLM supports various file formats, we will focus on three specific types due to time constraints. These selected types represent different methods of input:

-	Google Docs: A cloud-based platform allowing real-time updates and adjustments.
-	PDF: An offline format that can be uploaded directly if the file is available on the local machine.
-	Parsed Text: Instead of uploading or granting access to another platform, users can copy and paste text directly into the NotebookLM system without complicated settings.

The data for this experiment can be found in the GitHub repository under the folder named "Data" (please click on the hyperlink). This experiment aims to evaluate NotebookLM's performance in recognizing and handling various file types. We will focus on the following key questions:

-	File Recognition: Does NotebookLM accurately recognize and respond to simple questions based on the content of each uploaded file?
-	Recognition of Visual Elements: Are graphs, images, and tables correctly identified and interpreted within the files?
-	Update Notifications: After making updates to the Google Docs file, is there a visible notification indicating that an update request has been generated?
-	File Synchronization: Once an update request is made, is the Google Docs file accurately updated to reflect the changes?

---

### **Result**

After clicking on a source, NotebookLM automatically generates a summary and suggests key themes that accurately reflect the research content. This feature allows users to quickly understand the main ideas and themes within their sources. All three sources demonstrate consistent performance, delivering high-quality results

![image](https://github.com/user-attachments/assets/6843d0e6-504e-4bde-89b7-b1007d494438) ![image](https://github.com/user-attachments/assets/3f5ba8cf-4f6b-43f8-8232-79812868fe39) ![image](https://github.com/user-attachments/assets/5f858cc5-c8ad-4b48-ac75-9d09987d4cc3)

1. *Google Docs:*  To automatically sync data between Google Docs on Drive and files in NotebookLM, users can easily find the sync option in the top left corner of the canvas. The syncing process is smooth and seamless, ensuring that any updates made in Google Docs are reflected in NotebookLM without any hassle. Furthermore, I selected a research paper that included pictures and diagrams. It was evident that NotebookLM reads the images and diagrams effectively, accurately reflecting all necessary components while preserving the original formats.

![image](https://github.com/user-attachments/assets/1d8ad859-3a6f-4fdc-88ec-c771d25c4255)
![image](https://github.com/user-attachments/assets/a49842ee-21ba-4593-840c-d807738e6784)



3. *Parsed text:*  A section of the text containing a table was selected to evaluate NotebookLM's ability to read files with tables. NotebookLM provides strong support for table formats, effectively handling even tables with complex formatting from the original version. 

![image](https://github.com/user-attachments/assets/ad3ec3ae-e0f2-40f6-88db-9fc31f378363)



3. *PDF:*  NotebookLM correctly reads all the text content; however, it struggles to read and upload the formatting, figures, and charts accurately. Furthermore, NotebookLM can only recognize files created directly in Google Docs. Files uploaded from a local machine with .docs format are not recognized. Users must save their files as Google Docs to utilize the functionality properly.

![image](https://github.com/user-attachments/assets/5c860281-cc33-4ad1-b141-5a2daa6bb325)
![image](https://github.com/user-attachments/assets/04f1ff87-6b71-4a6f-abba-7a69691a31d4)

---

### **Conclusion**

