# Section 03: Managing Source Code. ✅

Managing Source Code.

# What I Learned.

# Searching and Navigating Source Code (part 01). ✅

# Searching and Navigating Source Code (part 02). ✅

# Generating Java Source Code. ✅

# Refactoring Code - Extract Constants and Variables. ✅

# Refactoring Code - Extract Methods, Rename Methods and Variables. ✅

- Todo change these ones

### Open Type.

- Open class by name

<div align="center">
    <img 
    src="openType.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

- We can open type by name from here

<div align="center">
    <img 
    src="YouCanUseWildCardsAlso.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

- You can use **wildcards** in Eclipse. Here is usage when opening type

<div align="center">
    <img 
    src="YouCanUseWildCardsAlso.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

### Quick Outline

- You can open outline view


<div align="center">
    <img 
    src="quickOutlineOppening.JPG" 
    alt="alt text" 
    width="400"
    />
</div>

- And it will look like such


<div align="center">
    <img 
    src="quiqk outline.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

- You can also filter in this menu

### Display inheritance tree

> **Navigate** > **Open Type Hierarchy** 

- This will help you to look inheritance tree for class

<div align="center">
    <img 
    src="typeHierachy.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

### Display Quick Inheritance Tree.

> Right-click > Quick Type Hierarchy


<div align="center">
    <img 
    src="quickTypeHierachy.jpg" 
    alt="alt text" 
    width="500"
    />
</div>

- Quick Type Hierarchy

1. You can type to filter 

### Search For Text.

> CTRL + F

- Search for text, with different tools


<div align="center">
    <img 
    src="searchText.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

- If you have multiple files

### Search For Multiple Files.

> Search > Search 

<div align="center">
    <img 
    src="searchFiles.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

1. **File Search**, can search plain text from multiple files
2. **Git Search**, you can search against Git repository
3. **Java Search**, search against Java constructs


<div align="center">
    <img 
    src="typeSearch.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

1. We are searching for where `JButton` is used in this project

<div align="center">
    <img 
    src="searchMethod.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

1. We are using `*` wild card with method name `create*`. Searching **method** name start with `create`

### View Method Detail

> Right-click > Open Declaration (**F3**)

- Opens declaration of method when opened 

### Finding Reference For Method

> Right-click > References > Workspace

<div align="center">
    <img 
    src="findingReferencesInWorkspace.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

- We can look where this method is being called

### Call Hierarchy: Sequence of methods calls

> Right-click > Open Call Hierarchy

- Given sequence of methods calls.

<div align="center">
    <img 
    src="callHierachyCalls.jpg" 
    alt="alt text" 
    width="600"
    />
</div>

1. We are calling `Call Hierachy` here.
2. We are reading this from **top** to **bottom**. **Main method** is calling our **constructor** which in sense is calling **our method** `create*`.

### Generating Getters and Setters

> Right-click > Source > Generating Getters and Setters

<div align="center">
    <img 
    src="generartingGettersAndSetters.jpg" 
    alt="alt text" width="600"/>
</div>

1. We can generate fetters and setters from class fields

### Generating Constructor using fields

> Right-click > Source > Generating Constructors using fields

<div align="center">
    <img 
    src="generartingConstructorUsingFields.jpg" 
    alt="alt text" 
    width="500"
    />
</div>

### Override / Implement Methods

> Right-click > Source > Override / Implement Methods

<div align="center">
    <img 
    src="override.jpg" 
    alt="alt text" 
    width="500"
    />
</div>

- Usually we be overriding `toString()` method

### Template shortcuts

<div align="center">
    <img 
    src="ctrl+space.jpg" 
    alt="alt text" 
    width="500"
    />
</div>

1. `Ctrl+Space` will auto complete code from template 
    - These can be found in Eclipse 
> Java > Editor > Templates > Main

<div align="center">
    <img 
    src="templateList.jpg" 
    alt="alt text" 
    width="500"
    />
</div>

### Format.

> Right-click > Source > Format


### Refactoring.

<div align="center">
    <img 
    src="refactoring.png" 
    alt="alt text" 
    width="400"
    />
</div>

### Extract Constant.

<div align="center">
    <img 
    src="exctractConstant.png" 
    alt="alt text"
    width="400"
    />
</div>

1. Write new for **Extracted Constant**

<div align="center">
    <img 
    src="exctractConstantt.jpg" 
    alt="alt text" 
    width="400"
    />
</div>

1. Extracted to own variable.

### Extract Local Variables.

> Color the code which you want to extract from code > Refactor > 

**Extract Local Variable**

### Extract Methods.

<div align="center">
    <img 
    src="excractMethod.jpg" 
    alt="alt text" 
    width="400"
    />
</div>


1. We can see this is one logical chunk of code, we want to extract this one

> Color the code which you want to extract to method > Refactor > **Extract Method...**

- Input name here to be refactored into 

<div align="center">
    <img 
    src="nameForExctractedMethod.jpg" 
    alt="alt text" 
    width="400"
    />
</div>

### Rename Method or variable.

- Renaming method or variables.

> Right-Click > Refactor > Rename...
