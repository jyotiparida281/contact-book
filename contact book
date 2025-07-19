contacts = {}

while True:
    print('\n1. Create contact')
    print('2. View contact')
    print('3. Update contact')
    print('4. Delete contact')
    print('5. Exit')
    choice = input("Enter a choice: ")

    if choice == '1':
        name = input("Enter a name: ").strip()
        if name in contacts:
            print(f"Contact '{name}' already exists.")
        else:
            age = input("Enter age: ").strip()
            number = input("Enter phone number: ").strip()
            contacts[name] = {'age': int(age), 'number': number}
            print(f"Contact '{name}' created successfully.")

    elif choice == '2':
        name = input("Enter a name: ").strip()
        if name in contacts:
            info = contacts[name]
            print(f"Name: {name}, Age: {info['age']}, Number: {info['number']}")
        else:
            print("Contact not found.")

    elif choice == '3':
        name = input("Enter a name to update: ").strip()
        if name in contacts:
            age = input("Enter updated age: ").strip()
            number = input("Enter updated phone number: ").strip()
            contacts[name] = {'age': int(age), 'number': number}
            print(f"Contact '{name}' updated.")
        else:
            print("Contact not found.")

    elif choice == '4':
        name=input("enter contact name to delete =")
        if name in contacts:
           del contacts[name]
           print(f'contact name {name} has been deleted successfully!')
        else:
           print('contact not found')
           
    elif choice == '5':
       print("exit")
       break

    else:
        print("Invalid input. Please choose 1–4.")
                    
   