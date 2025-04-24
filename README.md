# EXP 7 :USING JOHN THE RIPPER FOR PASSWORD CRACKING

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212222040128
Name: RAGHUL S
```

## DESIGN STEPS:
### Step 1:
Install John the Ripper in Kali linux

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).

### Step 3:
Use John the Ripper to crack the hashes

## PROCEDURE:
### Step 1: Create a Text File

  •	Right-click on the Desktop and choose Create Document → Empty Document.
  
  •	Name the file: raghul.txt

  ![1](https://github.com/user-attachments/assets/8d55c52b-98b1-4a5c-bfc6-ee78b2e5c567)

  •	Open it and type:

   ![2](https://github.com/user-attachments/assets/e77c8c00-5daa-4770-b8ad-95f9fd54dc1f)


  •	Save and close the file.

### Step 2: Create a Password-Protected ZIP File

  •	Right-click on raghul.txt → Create Archive.
  
  ![3](https://github.com/user-attachments/assets/fd07227a-cc88-4724-9198-14b90b323bab)


  •	Select .zip format.
  
  •	Click Other Options, set a password (e.g., 1234), then click Create.
  
  ![4](https://github.com/user-attachments/assets/9c70e493-7141-4a44-812e-224c2d4f21ee)


  •	A file named raghul.txt.zip will appear.

### Step 3: Open John the Ripper Terminal in Kali Linux

  •	Click on the Kali menu or press the Super (Windows) key.
  
  •	Search for “john” and click it — this opens the terminal with John the Ripper installed.
  
  ![5](https://github.com/user-attachments/assets/db8d52b9-e679-4623-b2e1-dcbc734fe746)


  •	Or simply open a Terminal from the dock or desktop.

### Step 4: Navigate to the File Location

  •	In the terminal, switch to the Desktop where the ZIP file is located:
  
  ![6](https://github.com/user-attachments/assets/feb7e3dc-c1b2-475e-9137-37b8dcf34335)


### Step 5: Confirm the ZIP File is Present

  •	Run: “ls” command
  
  ![7](https://github.com/user-attachments/assets/9a9c187a-01c3-4d1e-9f97-f8172e139989)


  •	You should see raghul.txt.zip listed.

### Step 6: Generate Hash Using zip2john

  •	Execute:
  
  ![8](https://github.com/user-attachments/assets/4879763f-d1e5-4fac-a290-05c7cdcc015d)


### Step 7: Verify the Hash File (Optional)
  •	Open hash.txt to ensure it contains the hash line.
  
  ![9](https://github.com/user-attachments/assets/286fe411-959e-4fd5-9dc0-2cffe4c82971)


### Step 8: Start Cracking the Password
  •	Run:
  
  ![10](https://github.com/user-attachments/assets/c63587bb-0d94-41a4-95be-128eeecb4837)


## OUTPUT:View the Cracked Password
  • After cracking is complete, reveal the password using:
  
  ![11](https://github.com/user-attachments/assets/373e5f15-3dc5-4056-97c7-24ac37abd62d)


  •	The terminal will display the filename and its cracked password.


## RESULT:
The password hashes were successfully cracked using John the Ripper.

