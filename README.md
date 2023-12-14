In today's business environment, manual entry of business card details into a database can be time-consuming and prone to errors. To overcome these challenges, developers can leverage the power of optical character recognition (OCR) and databases to automate the process of extracting relevant information from business cards and storing it for easy access.

We organize the data by using pandas so we can analyze it more effectively. Then EasyOCR is an open-source Python library that utilizes to accurately recognize and extract text from various languages. By integrating EasyOCR with a SQLITE, developers can streamline the process of capturing business card data and storing it in a structured and organized manner.

Usage-

1. Once user uploads a business card, the text present in the card is extracted by easyocr library.

2. The extracted text is sent to function for respective text classification as  card holder name, company name, designation, mobile number, email, website URL, area, city, state, and pin code using loops and some regular expression.

3. The classified data is displayed on screen which can be further edited by user based on requirement.

4. On Clicking Upload to Database Button the data gets stored in the MySQL Database.

5. Further with the help of MODIFY menu in the uploaded data’s in SQL Database can be accessed for Read, Update and Delete Operations.
