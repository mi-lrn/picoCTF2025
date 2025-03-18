![rust11](https://github.com/user-attachments/assets/8531bda7-7f2d-4a01-b603-016e654cdfa6)
# Step 1

Make a special directory where you will solve this challenge: (something like) rustfixme1.<br>
cd [YOUR_DIR]<br>
Run: sudo apt install rustc cargo<br>
This will install rust and the cargo package manager so you can run this project.
# Step 2

Download the fixme1.tar.gz file from the picoCTF dashboard onto your linux environment. (curl -O [link])
# Step 3

Run: tar -xvf fixme1.tar.gz<br>
This will extract the data from the file.
# Step 4

cd fixme1/src<br>
nano main.rs
# Step 5
![rust12](https://github.com/user-attachments/assets/a6e3a73c-dcf8-4720-9e3e-0b35528104ea)

The first thing that is noteworthy is the comment stating "How do we end statements in Rust?"<br>
Rust syntax requires a semicolon at the end of each line, so modify the code to include a ";".<br>

![rust13](https://github.com/user-attachments/assets/cddf1daa-ca8d-4e72-b587-d2446b4c0d00)
# Step 6

The second thing that is noteworthy is the comment stating "How do we return in rust?"<br>
Rust syntax for returning is just "return" not "ret".<br>

![rust14](https://github.com/user-attachments/assets/2ceae78f-d749-480c-a769-ac945e132269)
# Step 7

The third thing that is noteworthy is the comment stating "How do we print out a variable in the println function?"<br>

![rust15](https://github.com/user-attachments/assets/0ba7c637-60ea-4587-a4c2-0b8e96a56cdc)<br>

This is missing a format string, and we can fix it by changing it to the following:<br>

![rust16](https://github.com/user-attachments/assets/dfd6ec14-d28d-4c55-b75c-e105b60b00d4)
# Step 8

Now the code is all fixed! We just need to run it.<br>
Navigate out of your src directory and into fixme1.<br>
Run: cargo build<br>
Run: cargo run<br>
This will build and run your updated code using the provided cargo config files. Try it out!<br>

![rust17](https://github.com/user-attachments/assets/cff54826-674f-4b28-bd6a-71ac9b6e37c6)
