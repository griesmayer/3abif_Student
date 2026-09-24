# Student

## Code

```
public class Student
{
    private String  name;
    private int     alter;
    private boolean matura;
    
    public String getName()
    {
        return name;
    }
    
    public void setName(String neuName)
    {
        name = neuName;
    }
}
```

## UML

```
+----------------------------+
|         Student            |
+----------------------------+
| - name: String = "UNKN"    |
| - alter: int = 14          |
+----------------------------+
| + get/set                  |
+----------------------------+
```