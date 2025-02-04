MainPage
Display Items with Price and ItemId (Fancy UI) (If ItemQuantity == 0 Show UI where ItemId is Sold Out)

Keypad to select Displayed item (and quantity) (Fancy UI show selected item)

(Cut the Keypad Connection from UI except for Quit Key)

Display number of Quantity of items Left(LCD)  (Quantity Left: (ItemQuantity))
Display number of Quantity of items (LCD)  (Quantity: (Prompt))

(Keys for Enter and Escape is required)

After pressing Enter

Validate Quantity of item keyed in

No

Display Invalid Quantity (LCD)

Goes Back to Display Quantity of Items (LCD)

Yes

Go to Payment 

Show Payment Page (Fancy UI)


PAYMENT
(Cut all keypad connection to the UI)

Enter bank account number ($1000) (LCD) (Timeout to MainPage for no user interaction 10 Second)

(Keys for Backspace and Enter is required)

Pressing Enter

Validation of Bank Account (If true continue else Show Invalid Bank Account -> 3 Seconds Later (1. Try Again? 2. Abort))

(Try Again goes back to enter Bank Account Number, Abort go back to MainPage)

Enter password (hidden) (LCD) (Timeout to MainPage for no user interaction 10 Second)

(Keys for Backspace and Enter is required)

Pressing Enter

Validation of Password (If true continue else Show Invalid Password -> 3 Seconds Later (1. Try Again? 2. Abort))

(Try Again goes back to enter password, Abort go back to MainPage)


Check if Balance is more than cost

No

Decline Payment 

Show Insufficient Balance (LCD) 

(3 Seconds Later (1. Try Again? 2. Abort)) ( If Have Time for Second Account)

Clears LCD

Goes Back to the MainPage (Fancy UI)

Yes 

Show amount charged (LCD)
Show remaining Balance (LCD)

Show VISA Check (Fancy UI)

Wait 3 Seconds after the Check and Display Snack Dispensing Screen (Fancy UI)

Show Number of Snacks Left (LCD)

Snack Dispensed (360 degree turn of stepper motor for each snack) 5 sec each rotation