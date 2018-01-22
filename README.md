# ST0245-033
/**
 * Write a description of class Counter here.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */
public class Counter
{
    private String id;
    private int c;
    
    public Counter(String id){
        this.id = id;
        c = 1;
    }
    
    public void incrementar(){
        c++;
    }
    
    public int incrementos(){
        return c;
    }
    
    public String toString(){
       return "El contador quedó en: " + c;
    }
}
