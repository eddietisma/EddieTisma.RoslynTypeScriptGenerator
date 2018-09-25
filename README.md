# RoslynTypeScriptGenerator
Generate JavaScript with Roslyn and T4 Templates

Sample

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
