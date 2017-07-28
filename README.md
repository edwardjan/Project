package Model;

public class Project
{
    private static int ID;
    private static String CommonName;
    private static String ProjectName;
    private static String Manager;
    
    public void setID(int ID)
    {
        Project.ID = ID;
    }
    
    public void setCommonName(String CommonName)
    {
        Project.CommonName = CommonName;
    }
    
    public void setProjectName(String ProjectName)
    {
        Project.ProjectName = ProjectName;
    }
    
    public void setManager(String Manager)
    {
        Project.Manager = Manager;
    }
    
    public int getID()
    {
        return Project.ID;
    }
    
    public String getCommonName()
    {
        return Project.CommonName;
    }
    
    public String getProjectName()
    {
        return Project.ProjectName;
    }
    
    public String getManager()
    {
        return Project.Manager;
    }
    
}
