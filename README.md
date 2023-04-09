# Constrained-least-squares-filter
Constrained Least Squares Filter (CLSF) implementation in python with auto gamma selection based on best PSNR and MSSIM and noise parameters. This is a practice for Digital Image Processing (Gonzalez 4th ed. book) that automatically estimate best gamma value.

There is three value for gamma:

  1. gamma for best image MSSIM score
  2. gamma for best PSNR
  3. gamma based on noise parameters

As you can see, their values are not equal, but they are close to each other.

![final_result](https://user-images.githubusercontent.com/73604520/230791449-fe8bb1fe-dc5d-42f1-8caf-6278d91c3c4d.jpg)
![final_result](https://user-images.githubusercontent.com/73604520/230791461-a315dd7d-1cd6-49c4-93ba-4d6acb9b8523.jpg)


for noise parameters

![final_result](https://user-images.githubusercontent.com/73604520/230791471-1fe70a61-37ac-47d4-8869-bd2aa1d63560.jpg)
![final_result](https://user-images.githubusercontent.com/73604520/230791477-e83ae235-f144-404c-813a-4f7d53dcea65.jpg)
