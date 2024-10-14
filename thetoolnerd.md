I want to make a tool directory with all the latest tools categorised into to different types.
1. We will have a page with list of all the software products
2. We will have list of trending software products
3. We will have list of favourite software products
4. We will have list of new software products
5. Once we click on any software product, we should get a detailed page about the software.
6. We will have an Admin Dashboard, where we will see the list of all the tools in tabular format.
7. In the admin dashboard, I should have a button to add New software product.
8. Also, when i click on any of the software product, i should be able to see the detailed page of the product and able to edit the content.
9. All the data should be stored in database
10. The customer will be able to comment only after logging into the application.

# Admin Portal:
1. Admin portal will be accessible only to user with profile type as admin.
2. The admin portal will have a side bar
3. the home screen of admin portal will have the list of all the tools in tabular format
4. It will have a button to "Add new tool"

   ## Add New tool Page:
   1. The user will be able to enter the url of the tool and click on submit
   2. Once the user submits, we will call an api that will all the releveant information in the editable format
   3. The admin user should be able to review the content and edit it.
   4. The admin user should be able to save the content
   5. The admin user should be able to make the tool active by clicking  on Publish
   6. The admin user should be able to make the tool in active by clicking on unpublish
   7. The admin user should be able to edit the information by clicking on edit icon, even if the tool is in the published state
   8. The admin user can then save it and the tool with updated information will be visible to user only when the admin clicks on re-published
   
  **Page Fields**
    1. Basic Information:

         1. Tool name
         2. Logo
         3. Category
         4. Description
         5. Website URL: this should be the website URL or Our affiliate link
         6. Number of upvotes

      2. Social Links:
      
         1. Twitter URL
         2. LinkedIn URL
         3. GitHub URL
         4. Youtube URL

      3. Open Source Status: 1. Boolean (true/false)
      4. Features:
         1. List of features, each with:
               1. Feature name
               2. Feature description
      5. Use Cases: List of use case descriptions

      6. Alternatives:
         1. List of alternative tool names   
      
      7. Pricing:
         1. List of pricing plans, each with:
            1. Plan name
            2. Price
            3. List of features included in the plan

      8. Screenshots:
         1. List of screenshot image URLs

   ## Tools details page - the first screen of admin
      1. List of tools in the table format arranged in the order of recently added. 
      2. Ability to sort the columns
      3. Ability to filter the columns by category, by name, 
      4. Search option to search of the tool 
      5. Status of the tools - Published, Un-published. 
      6. Any new tool added via api or via any other means the default status will be Un-published, unless manually Published by the Admin

# Home Page

I'll provide you with the details of the data points and a description of the tool-directory home page.

Here are the details of the data points and a description of the tool-directory home page:

Data Points for Each Tool:

1. id: Unique identifier for the tool
2. name: Name of the tool
3. category: Category the tool belongs to (e.g., AI, Design, Development, Productivity)
4. purpose: Brief description of the tool's main purpose
5. description: A more detailed description of the tool
6. upvotes: Number of upvotes the tool has received
7. website: URL of the tool's website


Tool Directory Home Page Description:

The tool-directory home page is designed to showcase various software tools and AI products. It consists of several sections:

1. Header:

   1. Page title: "TheToolNerd"


2. Featured Tools Section:

   1. Title: "Featured Tools"
   2. Displays a grid of featured tools (usually 3)
   3. Each tool is represented by a card containing:

   1. Tool name
   2. Category (as a badge)
   3. Brief description

3. New Tools Section:

   1. Title: "New Tools"
   2. Similar to the Featured Tools section, but showcases recently added tools
   3. Displays a grid of new tools (usually 3)
   4. Each tool card contains the same information as featured tools

4. Smart Search Section:

   1. Title: "Smart Search"
   2. Includes a search input field with AI-powered suggestions
   3. As the user types, it provides tool suggestions based on the input

5. All Tools Section:

   1. Title: "All Tools"
   2. Filtering options:
      1. Search input for filtering by tool name or description
      2. Category filter (multi-select checkboxes)
      3. Purpose filter (dropdown)

6. Displays a table with columns for:
   1. Name (clickable, leads to detailed tool page)
   2. Category
   3. Purpose
   4. Description
   5. Upvotes (with thumbs-up icon)
   6. Website (link to visit the tool's website)

Layout and Functionality:

- Responsive design that adapts to different screen sizes
- The page uses a clean, modern design with a white background and blue accents
- Featured and New Tools sections use card layouts for visual appeal
- The All Tools section uses a table layout for easy scanning and comparison
- Filtering and search functionality allow users to find relevant tools quickly
- The smart search provides an AI-assisted way to discover tools based on user input
- Upvotes give users a quick way to gauge the popularity of each tool
- Direct links to tool websites make it easy for users to explore tools they're interested in


This home page serves as a comprehensive directory for software tools and AI products, allowing users to discover, compare, and access various tools quickly and efficiently.
