**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![leafpad_install](https://![task31](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/ca42827a-e8de-4e0d-bb83-13a3752a8a4a)


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Leafpad_editor](https://![task32](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/cbf42bb1-f64b-41ef-98c0-a42ee9113ed1)


**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**
![complie the C Code](https://![task33](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/683d6ccd-951e-4bca-b8d4-6952fb01c891)


**Step 5: Check the output by using the command**

**./a.out**
![C Code Execution with results ](https://![task34](https://![task35](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/e37da37e-4b47-40b7-9ba4-0acfa11e22f1)




**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![view in the C code in notepad](https://![task36](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/86830ef7-2e12-401b-aa68-9128141aa1bd)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![complie riscv](https://![task37](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/7deec88f-c4c9-44b8-ba22-2abe5cb300df)


**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![view the directory contents](https://![task38](https://github.com/Snehas-7/Repo-for-VSD/assets/120084430/74df5a9e-5ff4-42fd-83e5-70b20a84e12d)



![long directory content](https://github.com/Abdulbitm/Abdul/assets/160620896/3e2e473a-9f55-4bec-8ed3-4bd2732efbee)

**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![checking instructions_in_main_C_Code_15_instructions](https://github.com/Abdulbitm/Abdul/assets/160620896/8d7d1502-a997-403d-a2cc-fcd459962a43)

![checking instructions_in_main_C_Code_15_instructions_highlighted](https://github.com/Abdulbitm/Abdul/assets/160620896/0a07ba3e-4a3d-41a7-a158-3ef976ce0292)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![12 instructions with Ofast](https://github.com/Abdulbitm/Abdul/assets/160620896/f2ebdc19-c3a6-494d-a25d-6d71c2811440)



![12 instructions with Ofast_1](https://github.com/Abdulbitm/Abdul/assets/160620896/4904feb4-c3ab-4337-976c-9a94bacbf85a)






