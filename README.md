
public class samsple{
    public static int BinarySearch(int number[],int key){
        for(int i=0;i<number.length;i++){
            if(number[i]==key){
                return i;
            }
        
        }
     return -1;   
    }


    
public static void main(String[] args) {
    int number[] ={2,3,4,5,6,7,8};
    int key =5;
int index = BinarySearch(number,key);
if(index == -1){
            System.out.println("you key at" );
        }
        else{
            System.out.println("you key  found  "  +index);
        } 
    }
}
