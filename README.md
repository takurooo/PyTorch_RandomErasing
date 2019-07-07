# PyTorch_RandomErasing

Implementation of 
[Random Erasing Data Augmentation](https://arxiv.org/pdf/1708.04896.pdf).



# Examples of Random Erasing

![result](https://user-images.githubusercontent.com/35373553/60766408-49a44200-a0e4-11e9-8f14-4d2456b2fd32.png)

# Results

Dataset CIFAR10

## Test accuracy per class
| Class  | Random Erasing OFF | Random Erasing ON| 
| ---    | ---                | ---              |
| plane  | 82 %               | 83 %(+1%)        |
| car    | 87 %               | 91 %(+4%)        |
| bird   | 69 %               | 69 %(  -)        |
| cat    | 64 %               | 66 %(+2%)        |
| deer   | 75 %               | 75 %(  -)        |
| dog    | 64 %               | 74 %(+10%)       |
| frog   | 85 %               | 85 %(  -)        |
| horse  | 85 %               | 84 %(-1%)        |
| ship   | 85 %               | 88 %(+3%)        |
| truck  | 84 %               | 82 %(-2%)        |

## Test average accuracy and loss
|        | Random Erasing OFF | Random Erasing ON  | 
| ---    | ---                | ---                |
| acc    | 78 %               | 80 %(+2%)          |
| loss   | 1.3514 %           | 0.9337 %(-0.41769%)|
