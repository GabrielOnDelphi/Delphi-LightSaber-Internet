# Delphi-LightSaber-SelfTranslator
A collection of Internet-related units.

========================================================

**ciUpdater**

   Automatic program Updater & News announcer
   Checks if a new version is available online.

   You can target (show the news) only to a group of people (Paying customers/Trial users/Demo users/All).
   The library can check for news at startup, after a predefined seconds delay. This is useful because the program might freeze for some milliseconds (depending on how busy is the server) while downloading the News file from the Internet.
   No personal user data is sent to the server.
   
   The Updater
     Checks the website every x days to see if updates of the product (app) are available.

   The Announcer
     The online files keep information not only about the updates but also it keeps news (like "Discount available if you purchase by the end of the day").
     The program can retrieve and display the news to the user (only once).

   The online file
      The data is kept in a binary file. A graphic editor is available for this. The file is extensible (it can be easily expanded to accept new features).
      See the RNews record.
      
========================================================

**ciInternet**
      
   URL utils / URL parsing and validation
         
========================================================

**ciEmail**

   Functions for working with email addresses (email validation, etc)

========================================================

**ciHtmlWriter**

   Basic objects that allow you to enter miscellaneous HTML parts such as
   keywords, title, and body text and write this data to disk as an HTML file.
   
========================================================

**ciHtmlImg**

   Simple HTML Parsing. Specialized in extracting images from a webpage.

   Process 'relative path' for IMG tags
   Extract IMG tags
   Extract URLs from IMG/A HREF tags

========================================================

**ciHtml**

  HTML Parsing
  
========================================================

**ciDownloadThread**

  Downloads a file [ via WinInet ]
   
========================================================

**ciEmailSender**

   Universal 'SendMail' function
   
========================================================

**ciDownload**

   DOWNLOAD A FILE FROM THE INTERNET
   Uses WinInet (slow!) and System.Net.HttpClient.
   
========================================================

**ciCommonWebDown**

  Common WebSite Downloader
  This tool will locate the high resolution images on webpages of popular websites like: Unsplash.com, Pexels, pixabay.com, wallpaperscraft.com (work in progress)

  Unsplash.com
    The user provides the URL of a web page that holds an image.
    The program will try to automatically locate the high res image from that page.

========================================================
