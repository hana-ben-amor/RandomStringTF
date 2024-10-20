# RandomStringTF
![Capture d'écran 2024-10-20 224744](https://github.com/user-attachments/assets/64d4a09a-9c60-4744-ab85-1b0722e05ffa)

I first started with length 17 and run it using these commands:
        terraform init
        terraform validate
        terraform plan -out myplan 
        terraform apply myplan



Then i wanted to verify that terraform checks the old state and compare with newer requirements in configuration , so i changed the length to 7 and run these commands :
        terraform plan -out myplan 
        terraform apply myplan

      
![image](https://github.com/user-attachments/assets/392f3192-96da-4f0d-9b32-e364bf76c930)
