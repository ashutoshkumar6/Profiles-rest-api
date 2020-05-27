Profiles REST API (source cod)

Step 1: Go to the folder directory by writing following command in your terminal.
             
        cd profiles-rest-api
Step 2:  Now type in your terminal 
        
        vagrant up

Step 3: Now type in your terminal 
        
        vagrant ssh

Step 4: Now we go to vagrant enviroment by typing command

       cd /vagrant/
       
Step 5: Create a virtual enviroment on your terminal 
       
        python -m venv ~/env
        
Step 6: Go to the virtual enviroment 

      source ~/env/bin/activate
      
Step 7: Run the following command now

       python manage.py runserver 0.0.0.0:8000
       
Step 8: http://127.0.0.1:8000/api/ type this in your chrome or firefox.       
   
         
        
         
