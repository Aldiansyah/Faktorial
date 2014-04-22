/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package faktorial;

/**
 *
 * @author ADMIN
 */
public class Faktorial {

  public static void main(String[] args) {
       int bil,x,hasil;
       bil=5;x=2;hasil=1;
       do{             
           System.out.print(hasil+"x"+x+"=");
           hasil=hasil*x;
           System.out.println(hasil);
           x++;
       }
       while(x<=bil);
       System.out.println(bil+"!="+hasil);
       }
    }

