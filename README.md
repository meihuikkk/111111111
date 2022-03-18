# Notes
[Week 2](https://github.com/meihuikkk/111111111/edit/main/README.md#week2)
## Week2
### Object Reference Variables
**To reference an object, assign the object to a reference variable.<br/>**
Syntax for reference variable declaration<br/>
```
ClassName objectRefVar;
ClassName objectRefVar = new ClassName();
```
Example
```
Circle myCircle;
Circle myCirlce = new Circle();
```
> Declaration: Circle myCirlce, declaring variable: _myCircle_ to be the reference to _Circle_
> Instantiation: opeartor:_new_ calls the constructor defined in Class _Circle_, requesting memory from the computor
> Initialization: operated by the the constructor in _Circle_ (self-defined or non-arg)

### Access object
**- Referencing the object's data**
```
objectRefVar.data
```
for example
```
myCircle.radius
```
**- Invoking the object's method**
```
objectRefVar.methodName(arguments)
```
for example
```
myCircle.getArea()
```

### Instance Method
**Must be invoked from the object** cannot be called outside the object <br/>
Syntax
```
ObjectName.instanceMethod()
```
for example 
``` 
myCircle.getArea()
```
> the _getArea()_ here is a instance method called out from the object _Circle_ , which is referred by the ObjectRefVar _myCircle_

### Primitive type vs Object type


