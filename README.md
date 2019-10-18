# Vending Machine Simulation

A Vending Machine GUI simulation for a class

Email me at mhammond9@radford.edu for the source, if you're an employer.

-------------------------------------------------------------------------------------
 Michael Hammond
 
 Simulated Vending Machine 

 09/29/2018 
-------------------------------------------------------------------------------------
                                      ABOUT
-------------------------------------------------------------------------------------
   - This project is intended to function as a simulated vending machine      
   - There are some workarounds so that this project can function as a   
   standalone application.                                                          
       - A GUI frontend is used instead of an actual vending machine.          
       - The machine accepts the following coins:                              
           - penny                                                          
           - nickel                                                         
           - dime                                                           
           - quarter                                                        
       - The machine does not accept any dollar bills                          
       - The machine does not accept credit, debit, student or other cards.    
       - Only six machine items are provided for demonstration purposes.       
       - These items are as follows:                                           
           - Honey Bun                                                      
           - Chips                                                         
           - Soda                                                           
           - Cookie                                                         
           - Popcorn                                                        
           - Cheez-Its                                                       
-------------------------------------------------------------------------------------
                                 GENERAL USAGE NOTES                                
------------------------------------------------------------------------------------
   - Must be run with the Java runtime version 1.8                                  
   - Any computer capable of running this java version is capable of running this   
   application.                                                                     
   - Admin password: JAVAISTHEBEST                                                  
-------------------------------------------------------------------------------------
                                    INSTALLATION                                    
-------------------------------------------------------------------------------------
  - To both avoid plagiarism and for purposes of convenience, this program has      
  already been compiled.							    
  - To run the project, run 'java ViewController' without the quotes while in a     
  terminal window with the project directory as the current directory.              
-------------------------------------------------------------------------------------
                                   FUNCTIONALITY                                    
-------------------------------------------------------------------------------------                                               
- Terminal options after program start:                                             
    - 1: Run the vending machine as an end user                                       
    - 2: Run the vending machine as an admin                                          
- Universal GUI commands to run in AnimationProj:                                   
    - Enter coin (penny, nickel, dime, quarter)                                       
    - Select item (Honey Bun, Chips, Soda, Cookie, Popcorn, Cheez-Its)                
    - exit                                                                            
- GUI command to run AnimationProj as an end user:                                  
  - make purchase                                                                   
  - return change entered                                                           
- GUI commands to run AnimationProj as an admin:                                    
    - collect coins                                                                   
    - restock items                                                                   
-------------------------------------------------------------------------------------
  NOTE: If you accidentally run the program and want to exit, select 1 (end user),  
   then select the 'exit' GUI button to exit.                                       
-------------------------------------------------------------------------------------
                               PROGRAM INFORMATION                                  
-------------------------------------------------------------------------------------
  - VendingMachineCalculations.class                                                
                 - Performs all vending machine calculations.                       
  - VendingMachineInterface.class                                                   
                 - Contains the GUI interface for the Vending Machine               
  - VendingMachineInterface$CollectChangeListener.class                             
                 - Collects a fixed amount of change from the vending machine       
                       - 20 quarters                                                
                       - 15 dimes                                                   
                       - 10 nickels                                                 
                       - 5 pennies                                                                                                                  -
  - VendingMachineInterface$DimeListener.class                                      
  -              - Enters a Dime into the vending machine                           
  - VendingMachineInterface$NickelListener.class                                    
                 - Enters a Nickel into the vending machine                         
  - VendingMachineInterface$PennyListener.class                                     
                 - Enters a Penny into the vending machine                          
  - VendingMachineInterface$QuarterListener.class                                   
                 - Enters a Quarter into the vending machine                        
  - VendingMachineInterface$RestockListener.class                                   
                 - Restocks items in the vending machine to their default amounts   
  - VendingMachineInterface$ReturnChangeListener.class                              
                 - Returns all change entered by the end user to the end user       
  - VendingMachineInterface$SubmitListener.class                                    
                 - Exchanges item selected for change entered and returns remaining 
                 change if sufficient change has been entered.                      
                 - Declines selection if insufficient change has been entered.      
  - ViewController.class                                                            
                - Starts the program, creates the frame and calls the GUI class     
-------------------------------------------------------------------------------------
