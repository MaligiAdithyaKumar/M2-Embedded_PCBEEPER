# Output
![output](https://user-images.githubusercontent.com/94236183/144232829-045c5d5a-e01c-4d4a-8a9a-198f69ff35dc.PNG)

GREEN (COM1A1,COM1A0):This selection of pulling up or down is chosen by  CM1A0 and CM1A1 bits

OCR1A (Output Compare Register 1A) is the byte which stores the user chosen value. So if we change OCR1A=180, the controller triggers the change (high) when counter reaches 180 from 0.
