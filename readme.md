# This is the Valigrind exercise Project

## Instructions to run
```
git clone https://github.com/Arshad-Engineer/Valgrind_Exer.git
cd Valgrind_Exer
mkdir build
cd build
cmake ..
make
cd app
valgrind --leak-check=full --track-origins=yes ./shell-app    
valgrind --tool=callgrind ./app/shell-app
```

## Results:
- Please refer the following log files taken before and after bug fixes:
    - ValgrindLogPreCheck
    - ValgrindLogPostCheck
- Please refer the below screenshots, for the KCacheGrind Output
    - Location: /results
    - Callgrind_Screenshot1.png
    - Callgrind_Screenshot2.png
