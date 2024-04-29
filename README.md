<p align="center">
  <img width="460" src="logo.svg">
</p>

**Hi Fellow coders,**


We are Openbracket, a product development company. We are looking for people who are passionate about coding and love to code. We are looking for people who can think out of the box and can solve problems. We are looking for people who can take up challenges and break barriers. We are looking for people who can code.

We challenge ourselves to create an inclusive work environment where we are open to new ideas and never dismiss an idea with prejudice. You will be enabled and empowered to take risks for the right idea.

Our inclusive team of developers, coders, and rebels push all the limits to lose "im" and make everything possible. And you will be part of this team.

The qualities we are looking for are

- **Your love to code**
- **Your love to code**
- **Your love to code**
- and you know how the list goes...

Skills and experience

- Java\*
- Javascript\*
- ReactJS\*
- Reactive Programming\*
- Spring Boot\*\*
- MySQL\*\*
- MongoDB\*\*\*\*
- AWS\*\*\*\*
- Devops\*\*\*\*
- Linux\*\*\*\*
- Build Pipelines\*\*\*\*
- SAAS Product Development\*\*\*\*

_\* Good to have for people with no experience but required for others_

_\*\* Good to have for people with 0-2 years of experience but required for others_

_\*\*\*\* Good to have for people with 0-4 years of experience but required for others_

Choose one or many of the following problem statements and send a github repository link for solution and your resume or cv to **hr3(_at_)openbracket(_dot_)in**.

If you are applying for a full stack role solve one from all sections. If you are applying for only one of the roles solve one from either UI or Backend section and one from logic section.

While we appreciate a submission from you, we will not be so pleased to learn if you waste your and our time with plagiarism.

All the best.

P.S.: If you make any assumptions, please let us know the reasoning behind.

Thank you,

**Openbracket product development team**

-----

#### All applications have to be Java 20 or above and hosted on any free cloud. If they are UI applications then they have to be in ReactJS with Typescript and hosted on any free cloud. Please share a github repo link with the solution and your resume or cv to hr3(_at_)openbracket(_dot_)in.

## UI

All applications have to be ReactJS applications with Typescript and hosted on any free cloud.

***Note:*** Unit tests gain you extra points for you.

### Problem 1

- Create a simple ReactJS application with two pages, one editor page and one form page.
- The editor page should have controls like text box, dropdown, radio button, checkbox, date picker, etc. (Minimum 3 controls not including, mandatory Button and Label components)
  - User should be able to choose them from a toolbar and place them on the editor page (Doesn't have to be a drag and drop).
  - User should be able to select a control and see its properties in a property pane. (One or two properties for each control is enough).
- The form page should have a form with the same controls as the editor page.
  - The form should be able to take the data and on submit it should show as a JSON object.

***Note:*** Please don't use any library for the editor page. You can use any library for the form page. You need to come up with the format to store what controls are used in the editor.

### Problem 2

- Create a simple ReactJS application with heavy drag and drop. 

  - The page should create a circle on double click with random size from 30px to 80px and filled with random color.
  - All circles should be draggable. On right-click the circle should turn to a square and should not be draggable.
  - On double-click again it should turn back to a circle and should be draggable.
  - Clicking two circles should create a link between them depicted by a line. Dragging a circle should move the line with it.
  - If the line is dragged the circles should move along with the line. If the line is connected to a square, that should not move.
  - If the line is connected between two squares, the line should not move.
  
***Note:*** Please don't use any library for the drag and drop. You can use d3js library if you want to draw lines or circles, or you can do it with plain SVG or div tag manipulations. Don't use canvas. Extra points for creating different shapes and styles of lines like dashed, dotted for non movable side of the object and solid for movable side or curved lines instead of straight lines.

### Problem 3

- Create a simple ReactJS application with two halves. One half with a big text area to put JSON Schema and in the other half generate a form based on the JSON Schema put in the text area.
  - On submit capture the data in the form and show it as a JSON object.

- https://JSON-schema.org/ is the reference for JSON Schema.

***Note:*** Do not use any library to generate the form or to validate the JSON Schema. 

## Backend

All applications have to be Spring Boot applications with Java 20 or above and using Spring Webflux for reactive programming. Hosted on any free cloud. https://JSON-schema.org/ is the reference for JSON Schema.

***Note:*** Unit tests gain you extra points for you.

### Problem 1

- Create a simple Spring Boot application with a REST API. (Backend has to be MYSQL)
  - Endpoint 1: /createStorage (POST)
    - Create a table with structure based on the JSON schema posted in the request body.
    - Return the name of the storage
  - Endpoint 2: /updateStorage/{storageName} (PUT)
    - Update the table structure based on the JSON schema posted in the request body.
  - Endpoint 3: /{storageName} (POST)
    - Add a row to the table created in the /createStorage endpoint.
    - Return the row id.
  - Endpoint 4: /{storageName}/{rowId} (PUT)
    - Update the row in the table created in the /createStorage endpoint.
  - Endpoint 5: /{storageName}/{rowId} (DELETE)
    - Delete the row in the table created in the /createStorage endpoint.
  - Endpoint 6: /{storageName} (GET)
    - Get all the rows in the table created in the /createStorage endpoint.
  - Endpoint 7: /{storageName}/{rowId} (GET)
    - Get the row with the rowId in the table created in the /createStorage endpoint.
  - Endpoint 8: /{storageName}/search (GET)
    - Give the information on how to use the search endpoint.
  - Endpoint 9: /{storageName}/search (POST)
    - Search for rows in the table created in the /createStorage endpoint based on the search criteria in the request body. Come up with a query structure.

### Problem 2

- Create a simple Spring Boot application with a REST API. (Backend has to be MongoDB)
  - Endpoint 1: /createStorage (POST)
    - Create a collection with structure based on the JSON schema posted in the request body.
    - Return the name of the storage
  - Endpoint 2: /updateStorage/{storageName} (PUT)
    - Update the collection structure based on the JSON schema posted in the request body.
  - Endpoint 3: /{storageName} (POST)
    - Add a document to the collection created in the /createStorage endpoint.
    - Return the document id.
  - Endpoint 4: /{storageName}/{documentId} (PUT)
    - Update the document in the collection created in the /createStorage endpoint.
  - Endpoint 5: /{storageName}/{documentId} (DELETE)
    - Delete the document in the collection created in the /createStorage endpoint.
  - Endpoint 6: /{storageName} (GET)
    - Get all the documents in the collection created in the /createStorage endpoint.
  - Endpoint 7: /{storageName}/{documentId} (GET)
    - Get the document with the documentId in the collection created in the /createStorage endpoint.
  - Endpoint 8: /{storageName}/search (GET)
    - Give the information on how to use the search endpoint.
  - Endpoint 9: /{storageName}/search (POST)
    - Search for documents in the collection created in the /createStorage endpoint based on the search criteria in the request body. Come up with a query structure.

### Problem 3

- Create a simple Spring Boot application to parse a JSON Schema and validate a JSON object based on the JSON Schema. Do not use any parsing libraries for JSON Schema.

  - Endpoint 1: /validate (POST) return true or false based on the validation.
    - Example Request Object: 
    ```{
      "jsonSchema": {
        "type": "object",
        "properties": {
          "name": {
            "type": "string"
          },
          "age": {
            "type": "number",
            "minimum": 0
          }
        },
        "required": ["name", "age"]
      },
      "jsonObject": {
        "name": "John Doe",
        "age": 30
      }
    }
    ```

## Logic

### Problem 1

- Create a repetitive array data structure.
    - The array should be able to store any type of data.
    - It should store data like [1 x 2, 3 x 3, 8 x 3, 3 x 4] where it represents [1, 1, 3, 3, 3, 8, 8, 8, 3, 3, 3, 3]
    - It should have the following operations
        - Add an element at any index
            Example: [1 x 2, 3 x 3] add 2 at index 3 should be [ 1 x 2, 3, 2, 3 x 2]
        - Remove an element
        - Get an element at a particular index
        - Get the size of the array
        - Get the index of a particular element
    - Also add the details of time complexity of the operations.

### Problem 2

- Create a multidimensional array data structure.
    - The array should be able to store integer data.
    - Each dimension may vary in size.
    - The constructor should take the dimensions of the array.
    - It should have the following operations
        - Add an element at any dimensional index
        - Remove an element
        - Get an element at a particular dimensional index
        - Get the size of the array
        - Get the index of a particular element
    - Please give a detailed explanation of how you are storing the data and how you are accessing the data.
    - Please give your interpretation of dimensions.

### Problem 3

- Write a function to rotate a rectangle of size w x h by d degrees and give the resultant rectangle size w x h that can fit the rotated rectangle.

### Problem 4

- Write a function to take an array numbers and return an array of integers spacing them out evenly and add one data point to both the ends of the data.

    - Example: [1, 2, 3, 4, 5] should return [0, 1, 2, 3, 4, 5, 6]
    - Example: [1, 2, 3, 4] should return [0, 1, 2, 3, 4, 5]
    - Example: [-3.1, -2, 4, 5] should return [-4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6]
    - Example: [-100, -50, 0, 50, 100] should return [-150, -100, -50, 0, 50, 100, 150]
    - Example : [-90, -80, -70, 70, 80, 90] should return [-100, -75, -50, -25, 0, 25, 50, 75, 100]

    - If required add an optional parameter to fine tune the spacing.
