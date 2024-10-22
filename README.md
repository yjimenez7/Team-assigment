# Team-assigment
def show_menu():
    print("Please choose an option from the menu below:")
    print("Option: One")
    print("Option: Two")
    print("Option: Three")
    print("Option: Four")
    print("Option: five")
    print("option: six")
    print("Option: Seven")
    print("Option: Eight")
    print("Option: Nine")


choice = int(input("Enter your choice (1-9):"))
        if 1 <= choice <= 9:
            print("You're option {choice}.")
        else:
            print("choice 1 to 9.")
    except ValueError:
        print("Invalid input number.")
