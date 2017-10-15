# Fall2017_CS1C-2D Graphics Modeler

Create 2D graphics modeler for simple geometric shapes.
Will be integrated into customer's code.

**//CORE COMPONENT REQUIREMENTS//**
1) Use inheritance, composition, excepstion handlers,
virtual functions, and at least two overloaded operators.

2) One class must contain a pointer.

3) Copy constructor needs to be written and tested.

4) Using the Qt Painter low-level graphics rendering library:
  a)Implement abstract base class shape.
   -aggregation relationship(pointer to another class)
   -includes the following virtual functions:
     > draw
     > move
     > perimeter
     > area
     
  b)Implement shape classes derived from Shape:
   -Line
   -Polyline
   -Polygon
   -Rectangle
   -Ellipse
    <Must contain the following properties>:
    > Dimensions
    > Pen Color
    > Pen Width
    > Pen Style
    > Pen Cap Style
    > Pen Join Style
    > Brush Color
    > Brush Style

   -Text
    <Must contain the following properties>:
    > Alighment
    > Point Size
    > Font Family
    > Font Style
    > Font Weight
  
  c)Overload equality and less-than operators.
    (Will facilitate shape id comparisons for sorting)
    
  d)Disable copy operations for all shape types.
    (Mark copy constructor/assignment operator for Shape as deleted)
    
5) Implement our vector class, based on John's provided example.
  (Will store shape objects for modeler)
  <Suppors the following operations>:
  > constructors for one or more arguments
  > default constructors
  > copy constructors
  > copy assignment
  > move constructor
  > move assignment
  > destructor
  > basic iterator member type
  > member begin() and end() operations
  
6) Implement a user-friendly interface to demonstrate the modeler.

**//CORE FEATURE REQUIREMENTS//**
