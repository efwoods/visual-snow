# Visual Snow
Working on a solution to removing the noise from visual snow.

## Problem:
### Normal Human Vision:
![image](./vs-image/lena.jpg)

### Daily Vision with Visual Snow:
![alt image](https://github.com/efwoods/visial-snow/blob/fa42de8bc56d1f93f7a187d483f57b6a7c467214/vs-image/vs-lena/vs-lena.gif)

### Daily Vision with Visual Snow while eyes are shut:
![alt text](https://github.com/efwoods/visual-snow/blob/62f6eeba83fe6240d0b25b6b7085af9710279628/vs-image/eyes-closed-vs/eyes-closed-vs.gif)

## Solution
1. Identify a the set of eeg signals that correspond to vision with complete darkness as a baseline.
2. Identify the a set of eeg signals that correspond to vision with visual snow while eyes are shut (a.k.a. the presence of visual activity when eyes are shut)
3. Train a neural network to detect patterns of visal snow. 
4. Define an algorithm to send a signal to counter-act the activity of these neurons.

## References
[Noise Removal in colored Images using Median Filter](https://www.youtube.com/watch?v=GCC52JCBbX0)
[NIH Visual Snow Article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7136068/)

## Related Repositories
[Parkinson's Disease](https://github.com/efwoods/parkinsons-disease)
[Tinnitus](https://github.com/efwoods/tinnitus)
