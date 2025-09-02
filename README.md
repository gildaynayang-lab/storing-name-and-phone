import csv
with open('contacts.csv', 'w',newline='') as file:
    cvs.writer(file)
    writer.writerow(['name', 'phone number'])
while true:
    name = input("enter name:")
    phone = input("enter phone number:") 
    writer.writerow([name,phone_number ])
    again = input("add another ?(yes/no):")
    if again.lower() !='yes':
              break
print("done!! data saved.")
