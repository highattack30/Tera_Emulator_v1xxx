# Tera_Emulator_v1xxx
This is a WIP[Work in progress].

To copmile this you need:
      -boost code
      -mysql code

In the Config/server.txt you find:
     
      -first line - server's ip
      
      -second line- server's port
      
      -third line-max connected clients
     
      -fourth line - mysql server ip
     
      -fifth line -mysql user 
     
      -sixth line -mysql password
      
      -seventh line - mysql database name

      inventory.bin and deposit.bin are used to save players inventory and deposit items to database asa BLOB.
      Format:each item is writed as an int[4 bytes].

      v1020
      -rsolved some bugs
      -more stabile
      -added future need code
      -max point[login->hit lobby]
