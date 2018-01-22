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
    private int contador;
    
    public Counter(String id){
        this.id = id;
        contador = 1;
    }
    
    public void incrementar(){
        contador++;
    }
    
    public int incrementos(){
        return contador;
    }
    
    public String toString(){
       return "El contador quedó en: " + contador;
    }
}
