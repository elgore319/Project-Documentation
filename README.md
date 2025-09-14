# Project-Documentation

<img width="941" height="571" alt="UML" src="https://github.com/user-attachments/assets/995a183d-8177-4cc0-b420-07f2207b0587" />

Attached here is my UML with notes about the project.

AI Reflection:
The only thing I used AI for was to understand how <<abstract>> and <<interface>> were to be placed in the UML. Looking back, it was wholly unnecessary. I had used Chat GPT.

AI prompt:
Thats fine. Where would you put the words abstract and interface

Response:

In UML class diagrams, you show abstract classes and interfaces in special ways:

🔹 Abstract Class

The class name is italicized or marked with «abstract».

Abstract methods are also italicized.

Example with your Shape:
+----------------+
                | «abstract»     |
                |     Shape      |
                +----------------+
                | - color:String |
                | - name:String  |
                +----------------+
                | + area():double|
                | + draw():void  |
                +----------------+
This tells the reader you can’t create a Shape directly — only subclasses like Circle or Hexagon.

