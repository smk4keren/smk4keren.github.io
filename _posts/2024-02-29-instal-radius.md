## INSTALL FREERADIUS

1.      sudo apt update


   
2.      sudo apt install freeradius

   
3.      sudo service freeradius start

 
4.      sudo service freeradius status

   
5.      sudo nano /etc/freeradius/users

  
6.      username cleartext-password := "password"

    
7.      radtest username password localhost O testing123

    
8.      radclient -x localhost auth testing123



![foto](https://github.com/smk4keren/smk4keren.github.io/assets/157451349/58bf138a-8396-4ade-aec2-270b9dbba187)
