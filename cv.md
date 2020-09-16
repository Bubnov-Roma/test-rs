Bubnov Roman
================


## Contact info
 *Location: Samara, Russia*  

 *Phone: +7 977-674-2495*  
 
 *GitHub: [Bubnov-Roma](https://github.com/Bubnov-Roma)*  
 
 *Telegram: [@bubnov_roma](https://t.me/bubnov_roma)*
 
 *Mail: [kilkun@mail.ru](mailto:kilkun@mail.ru)*  
 
 *Skype: [Roma Bubnov](https://join.skype.com/invite/jiH3DjfiNZEk)*  
 
## Summary
 **I like writing this code**
 
 >_Most good programmers do programming not because they expect to get paid or get adulation by the public, but because it is fun to program. 
 Linus Torvalds_      
 
 
 
## Skills
 * HTML/CSS
 * JavaScript
 * Java
 * GIT
 
 
## Code example
 **Java**:
 ```Java
 
 public class Solution {
    public static void main(String[] args) {
        byte[] ip = new byte[]{(byte) 192, (byte) 168, 1, 2};
        byte[] mask = new byte[]{(byte) 255, (byte) 255, (byte) 254, 0};
        byte[] netAddress = getNetAddress(ip, mask);
        print(ip);          
        print(mask);        
        print(netAddress);  
    }

    public static byte[] getNetAddress(byte[] ip, byte[] mask) {
        byte[] netAddress = new byte[ip.length];
        for (int i = 0; i < netAddress.length; i ++ ) {
            netAddress[i] = (byte) (ip[i] & mask[i]);
        }
        return netAddress;
    }

    public static void print(byte[] bytes) {
        for (byte b : bytes) {
            String binStr = Integer.toBinaryString(b & 0xFF);
            System.out.print(("00000000" + binStr + " ").substring(binStr.length()));
        }
    }
}
 
 ```
 
 
## Education
 Course :
 
 - [**JavaRush** _Java Multithreading_](https://javarush.ru/me) - in progress
 - [**RS School** _JavaScript/Front-end_](https://rs.school/js/) - in progress
 
 
## English
 A2
