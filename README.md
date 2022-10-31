public class missionFive {
    public static void displayList(){
        //Declare a list called "input" which will be used to hold 4 numbers: "12,20,30,17"
        List<Integer> input =new List<Integer> {12, 20, 30, 27};
            System.debug(input);
          
        //For loop runs through each item in the "input" list
            for (Integer i : input) {
                
        //if "input" is multiples of both 3 and 5, display "DingDong"
                if (math.mod(i,3)== 0 && math.mod(i,5)==0){
                    System.debug('DingDong');
                }
                
        //if "input" is multiple of 3, display "Ding"
                else if (math.mod(i,3) ==0){
                    System.debug('Ding');
                }
                
        // if "input" is multiple of 5, display "Dong"
                else if (math.mod(i,5) ==0){
                    System.debug('Dong');
                }
                
        //if neither, return the number
                else if (math.mod(i,3)==0 && math.mod(i,5)==0){
                    break;
                }
                    
                }
                    System.debug('17');
            
    }
}
