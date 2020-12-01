# Occupancy Grid Mapping

Visualizing the mapped environment through the generated image

## Compiling

```
cd ~/<YOUR WORKSPACE>
git clone https://github.com/morgan9900103/Occupancy-Grid-Mapping-Cpp
cd Occupancy-Grid-Mapping-Cpp/
rm -rf Images/*
g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

## Running

Make sure you delete the image in ```Images``` folder before running the program

```
./app
```

Now, wait for the program to generate the map

## Generated Map

![](Images/Map.png)
