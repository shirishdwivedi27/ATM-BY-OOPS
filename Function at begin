class Atm:
    
    def __init__(self):
        self.pin=''
        self.balance=0
        self.menu()
    def menu(self):
        w=input('''
                what you want to do?
                1.create pin
                2.check balance
                3.deposit
                4.withdraw
                5.exit
''')
        if w=='1':
            self.create_pin()
        elif w=='2':
            self.check_balance()
        elif w=='3':
            self.deposit()
        elif w=='4':
            self.withdraw()
        elif w=='5':
            self.exit()

    def create_pin(self):
        self.pin=input('enter your pin')
        t=input('cnfrm ur pin')
        if self.pin==t:
            print('pin successfully  created')
        else:
            print('wrong pin')
            print('reprocess')
            self.create_pin()
    def check_balance(self):
        p=input('enter your pin')
        if self.pin=='':
            print("YOU DON'T CREATE PIN YET")
            s=input("TO CREATE PIN PRESS: '5'")
            if s=='5':
                self.create_pin()
        elif p==self.pin:
            print('entered successfully sbi era')
            print(self.balance)
        else:
            print('wrong pin')
            y=input("wanna retry to check balance:   [ Y/N]   ")
            if y=='Y':
                self.check_balance()
            else:
                pass

    def deposit(self):
        w=input("enter pin")
        if self.pin=='':
            print("YOU DON'T CREATE PIN YET")
            s=input("TO CREATE PIN PRESS: '5'")
            if s=='5':
                self.create_pin()
        elif w==self.pin:
            t=int(input("enter amount for deposit"))
            self.balance+=t
            print("amount update")
            t=input("WANT TO GET YOUR UPDATED ACCOUNT DETAIL:  [Y/N]  ")
            if t=="Y":
                print(self.balance)
            else:
                pass
        else:
            print("WRONG PIN")
            
            
                
                
        
    
