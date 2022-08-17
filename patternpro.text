public class patternpro {
    public static void main(String args[]) {
        int n=4;
        int m = 5;
/******************************************************************************************************************************************************************************** */
        
        // solid rectagle
        System.out.println("solid rectagle :--");
/*
        solid rectagle :--
                            *****
                            *****
                            *****
                            *****
*/
        for (int i=1;i<=n;i++){
            for(int j=1;j<=m;j++){
                System.out.print("*");
            }
            System.out.println("");
        }

 /******************************************************************************************************************************************************************************** */
         
        //boundry *
/*
                            *****
                            *   *
                            *   *
                            *****
*/
        System.out.println("boundry *:--  ");
        //outer loop
        for (int i=1;i<=n;i++){
            //innerloop
            for(int j=1;j<=m;j++){
                //cell - > (i,j)
                if(i==1 || j==1 ||i==n|| j==m){
                    System.out.print("*");

                }
                else{
                    System.out.print(" ");
                }
                
            }
            System.out.println("");
            
        }
/******************************************************************************************************************************************************************************** */
  

        // half pyramid
/*
        Half pyramid :--
                        *
                        **
                        ***
                        ****
*/
        System.out.println("Half pyramid :--");
        for(int i=1;i<=n;i++){
            for(int j=1;j<=i;j++){
                System.out.print("*");

            }
            System.out.println(" ");
        }

/******************************************************************************************************************************************************************************** */
  

        // invert half pyramid
/*
                                ****
                                ***
                                **
                                *
 */


        System.out.println("Invert Half pyramid :--");
        for(int i=n;i>=  1;i--){
            for(int j=1;j<=i;j++){
                System.out.print("*");

            }
            System.out.println(" ");
        }
 /******************************************************************************************************************************************************************************** */
  
        // invert half pyramid(rotate 180 deg)
/*
                                               *
                                              **
                                             ***
                                            ****

 */
        System.out.println("invert half pyramid(rotate 180 deg):--");
        
        for(int i=1;i<=n;i++){
            //innerloop
            for(int j=1;j<=n-i;j++){
                System.out.print(" ");
            }
            //innerloop -> star print

            for(int j=1;j<=i;j++){
                System.out.print("*");


            }
            System.out.println(" ");
        }
/******************************************************************************************************************************************************************************** */
  
        // number half pyramid
/*
                                1
                                12
                                123
                                1234
 */




        System.out.println("number half pyramid:--");
        
        for(int i=1;i<=n;i++){
            

            for(int j=1;j<=i;j++){
                System.out.print(j);


            }
            System.out.println();
        }

/******************************************************************************************************************************************************************************** */
  

        // number inverted half pyramid

/*
                                        1234
                                        123
                                        12
                                        1
 */
        System.out.println("numbers inverted half pyramid:--");
        
        for(int i=1;i<=n;i++){
            

            for(int j=1;j<=n-i+1;j++ ){
                System.out.print(j);


            }
            System.out.println();
        }

/******************************************************************************************************************************************************************************** */
  
        //Floyd's tringle
/*
                            1
                            2 3
                            4 5 6
                            7 8 9 10
 */



        int number = 1;
        
        System.out.println("Floyd's tringle :--");
        
        for(int i=1;i<=n;i++){
            

            for(int j=1;j<=i;j++){
                System.out.print(number+" ");
                number++;//number= number+1;


            }
            System.out.println();
        }

/******************************************************************************************************************************************************************************** */
  
        // 0 - 1 triangle
        //1 {1 == (i=1;j=1)(i+j=2)(sum is even)(print 1)}
        //01 {0== (i=2;j=1)(i+j=3)(sum is odd)(print 0)}  {1 == (i=1;j=1)(i+j=2)(sum is even)(print 1)}
        //101
        //0101


        System.out.println("0-1 triangle :--");
/*
                                            1
                                            01
                                            101
                                            0101
 */
        for(int i=1;i<=n;i++){
            

            for(int j=1;j<=i;j++){
                int sum=i+j;
                if(sum %2==0){
                    System.out.print("1");
                }
                else{
                    System.out.print("0");
                }
            }
            System.out.println();
        }
    }
    
}
