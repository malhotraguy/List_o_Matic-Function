def check_list_o_matic(list_name):
    def list_o_matic(list_name,inp):
        if inp=="":
            return print(list_name.pop(),"popped from list \nLook at the after list: ",list_name)
        else:
            if inp in list_name:
                list_name.remove(inp)
                print("\n1 instance of","'"+inp+"'","has been removed from the list")
                print("Look at the after list: ",list_name)
            else:
                list_name.append(inp)
                print("\n1 instance of","'"+inp+"'","has been appended to the list")
                print("Look at the after list: ",list_name)


    while True:
        if list_name==[]:
            print("\nGOODBYE!!!")
            break
        else:
            print("\nLook at the before list: ",list_name)
            inp=input("Enter your Character or 'quit' to end!! :  ")
            
            if inp=="quit":
                print("GOODBYE!!! \n")
                print(list_name)
                break
            else:
                list_o_matic(list_name,inp)
#=====================================================================================================================
#=====================================================================================================================

list_animal=["cat","dog","horse"]
check_list_o_matic(list_animal)
