# AggieAir Flightgear Models
3D models of AggieAir airframes for FlightGear visualisation. More information at [aggieair.usu.edu](http://aggieair.usu.edu/)

Currently available is [Minion](http://aggieair.usu.edu/node/349) airframe, with wingspan of 9ft and takeoff weight of 18 lbs. The 3D model is rather large because of the details, so it might not suit all platforms.

![Minion 3](https://github.com/AggieAir/Models/blob/master/Data/3.png)

## Installation 
The model itself is `Models` directory and should be copyied into FlightGear directory structure, in Linux:

```bash
cd Models
sudo ln -s `pwd` /usr/share/games/flightgear/Models/Aircraft/paparazzi
```

See [paparazzi wiki](https://wiki.paparazziuav.org/wiki/FlightGear) for more details. The `Data` directory is for auxilliary data, such as images etc.

Then start flightgear with:

```bash
fgfs --fdm=null --native-fdm=socket,in,30,,5501,udp --prop:/sim/model/path=Models/Aircraft/paparazzi/minion.xml  --enable-terrasync
```

## Screenshots

![Minion 5](https://github.com/AggieAir/Models/blob/master/Data/5.png)

![Minion 1](https://github.com/AggieAir/Models/blob/master/Data/1.png)

![Minion 2](https://github.com/AggieAir/Models/blob/master/Data/2.png)



