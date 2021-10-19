# Sample Readme

![image](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

Sr. # | Type | Change
--- | --- | ---
1 | `Service Layer - Class` | **Service Layer Classes are not static anymore**

## collapsible markdown?

<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>

Sr. No.,Component,Item,FACTS v2,FACTS v3,Automated?,Comments
1,Business Logic,Base Class,"No base class is required for Business Logic classes

Code Snippet:
public static class AccountLogic
{
  // Some Code
}
","Business Logic classes need to inherit from LogicBase base class. 

Code Snippet:
public class AccountLogic : LogicBase
{   
 // Some Code
}
",Yes,"v3 has base class for business logic classes, all logic classes need to derive from this, it has the properties like lookups, localizer, context which are not static anymore and are properties of the base class."
2,Business Logic,Class,"Business Logic classes are static.

Code Snippet:
 public static class LinkBusinessLogic
{
  // Some Code
}","Business Logic classes are not static. Remove static keyword from the classes.

Code Snippet:
public class LinkBusinessLogic : LogicBase
{
  // Some Code
}
",Yes,
