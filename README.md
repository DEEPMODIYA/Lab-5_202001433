# IT 314 Software Engineering
## Lab 5

### Name: Modiya Deep Ashokbhai
### Student ID: 202001433
<hr>

### Static Code Analysis of a git repository using [mypy](https://mypy.readthedocs.io/en/stable/) tool
## mypy tool:
- mypy is an open-source static type checker for Python.
- It supports type annotations for function arguments, return values, and variables.
- It can also check for common type-related errors such as type mismatches, invalid method calls, and incorrect argument types.
- mypy supports various types of annotations including built-in types like str, int, float, etc., user-defined classes, generic types, and union types.
- It also provides options to customize the checking process, ignore certain files, and suppress specific error messages.
<hr>

## I've uploaded my ML lab .py file an I've taken the code from that file and analyze it using mypy playground online tool
## Library is not installed (This is of type false negative because if I run my code in Google Collab, it'll not give any error)
![image](https://user-images.githubusercontent.com/99895157/227482396-9dce8219-ebc3-4c37-ab27-6110e3cec612.png)
## Syntax error (True positive)
![image](https://user-images.githubusercontent.com/74952781/225270871-cd35240b-df2d-4722-b231-459215385ff6.png)
![image](https://user-images.githubusercontent.com/74952781/225271022-3485b211-8af6-4f21-98c5-08c2f6ad5b66.png)
![image](https://user-images.githubusercontent.com/74952781/225273054-e68d26da-74e7-4758-9955-998abdd57bfd.png)


## Missing arguments (True positive)
![image](https://user-images.githubusercontent.com/74952781/225272141-608a837c-1f2b-43c2-89d3-a3aac460dcb3.png)

## Indentation error (True positive)
![image](https://user-images.githubusercontent.com/74952781/225272628-8c5f3d51-6abb-4b02-9451-e78a1a934e18.png)
![image](https://user-images.githubusercontent.com/74952781/225272911-b1a64b3b-ae1e-4e7f-9838-02b497e9c73c.png)

## Unterminated string literal (True positive)
![image](https://user-images.githubusercontent.com/74952781/225274276-e451fba8-b2f0-47ff-a1f1-c38e881c1678.png)
![image](https://user-images.githubusercontent.com/74952781/225274468-6ff54f26-6e10-4de1-ae0c-57182412b51e.png)
