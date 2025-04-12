# WDD 130: Web Fundamentals  

## W01 Assignment: Student's Home Page  

### Overview  
In this assignment, you will apply your learning by creating a basic home page using HTML.  

### Instructions  

1. Create a course folder on your computer named **"wdd130"** (lowercase, no spaces).  
2. Open the **wdd130** folder in **Visual Studio Code (VS Code)** using `File -> Open Folder`.  
3. Create a new file inside the **wdd130** folder named **"index.html"**. This will be your course home page.  
4. In your **index.html** file, write the HTML markup to build the basic HTML page structure using **"!"**.  
5. Set the `<title>` content to **[Your Full Name] | WDD 130**, replacing **[Your Full Name]** with your actual name.  
6. Inside the `<body>` element, include three semantic child elements to create the major sections of the page:  
   - `<header>`  
   - `<main>`  
   - `<footer>`  
7. Inside the `<header>` element, add a `<nav>` element containing `<a>` (anchor) elements with the following `href` attribute values. The **Rafting Website** link will be used in a future assignment, so just prepare it by linking to this future page, even though it will not work now.  
8. Inside the `<main>` element:  
   - Add an `<h1>` heading element containing **Your Full Name | WDD 130**.  
   - Add an `<img>` element with the following attributes:  
     - **src**: The image file path. Use the following path: `src="images/profile.____"`, replacing `____` with your image file extension.  
     - **alt**: A descriptive alternative text, including your name for accessibility.  
     - **width**: Set the initial width of the image to **200**.  
   - Add a `<p>` paragraph element containing information about yourself.  
9. To support the image reference, create a new folder named **"images"** inside the **wdd130** folder.  
10. Copy or move an optimized profile picture of yourself into the **images** folder.  
    - Acceptable image file types:  
      - `.png`  
      - `.webp`  
      - `.jpg`  
    - The image file must not exceed **100 kB** in size.  
11. Rename the image file to **profile.** followed by its extension.  
12. Inside the `<footer>` element, add a `<p>` paragraph containing:  
    - The copyright symbol **©** and the current year.  
    - Your name.  
    - Your state or country.  
    - Separate each of these items using syntax of your choice.  
13. Check your rendered page by right-clicking on the **index.html** file in the **Explorer** panel and selecting **"Open with Five Server"**, or by using the menu at the bottom of **VS Code**. **Five Server** will open the page in your default browser.  

### Complete Example  
![Complete Example Page](images/example.png)  
