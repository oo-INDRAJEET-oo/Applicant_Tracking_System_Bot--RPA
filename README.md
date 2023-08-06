# Applicant_Tracking_System_Bot--RPA
RPA using UiPath to build a bot that can track resumes using the set criterion to validate and score candidates according the requirements.

1. When the applicant’s documents are received by email id then the bot starts its work.</br>
2. The bot searches the keyword CV/Resume and only under the subject CV/Resume checks the format of the document and it then further checks for the documents that are in PDF format, rest of the documents are ignored. The PDF documents are then stored in the respective folder of the employee’s machine.</br>
3. If the subject is not mentioned as CV/Resume then that application is not considered and rejected without screening.<br>
4. The bot then retrieves the documents one-by-one, that are initially stored in a folder. The bot uses a pdf-extraction function to extract the content from the pdf. The content is then checked against the given criteria by an organization.</br>
5. Based on criteria, the bot sorts the documents into eligible/non-eligible candidates and selects the applicants that are best suited for the job and stores their information in an excel file, and sends an email to these selected candidates, that they are selected for the interview. The excel file can also be used for further use by the organization.</br>
