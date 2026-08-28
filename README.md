# Steps
1. To Compile 
    With Checks for memory issues: 
        `g++ -fsanitize=address -std=c++11 rayTracer.cpp`
    Without Checks for memory issues:
        `g++ -std=c++11 rayTracer.cpp`

2. to take in a text file and output an image:
   `.\ray.exe *path to scenefile* `   
   Ex: `.\ray.exe .\SphereExamples\spheres1.txt `