# Collab-Programming-Guide
Guide &amp; rules on how we can collaborate more efficiently


HTML RULES
  
  TAGS
    
    - Use semantic HTML tags. Increases accessibility for disabled users (and is a project requirement).


CSS RULES
  
  STRUCTURE
    
    - When the HTML has been pre-written, editing anothers work or just applying a large amount of CSS in one go, write out ALL of the HTML tags that will be changed with CSS BEFORE adding CSS code. Makes it easier to keep a track of where you are and enhances clean CSS structure.
    
    - Flexbox containers always go at the top of the CSS element section as they control everything beneath them. The following elements WITHIN the flexbox should be indented (with tabs) to maintain clean code structure.
  
    - DRY principle: Dont Repeat Yourself. Try and write efficient code which means effective use of classes and ids.
  
  COMMENTS
    
    - Add comments to every new element (VScode shortcut- CTRL + U + K / CMD + U + K) to seperate and make more readable.
    
  
  CLASSES vs. ID 
    
    CLASSES
      
      - Use classes in most cases. They can be reused in future elements that have not been written yet where IDs can only be used once.
      
   
    IDs
      
      - Good for use in elements that will only ever be used once. Eg. Navbar links to a section of your HTML page.
      
      - Also used in radio and checkbox buttons to link to its label (text identifying the button or checkbox.
