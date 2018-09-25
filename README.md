# RoslynTypeScriptGenerator
Finds methods on types deriving from 'ApiController' and creates a proxy client with all actions and models.

 ```csharp
public class ComplexObject
{
    public int Id { get; set; }
    public DateTime Date { get; set; }
}

public class ComplexController : ApiController
{
    public ComplexObject Create()
    {
        return null;
    }
    
    public ComplexObject GetComplexObject()
    {
        return null;
    }
    
    public List<ComplexObject> GetComplexObjects()
    {
        return null;
    }
    
    public void Update(ComplexObject object)
    {
        return null;
    }
    
    public void Delete(int id)
    {
        return null;
    }
}
 ```
