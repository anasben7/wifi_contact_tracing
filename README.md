

<h2>Wifi Contact Tracing</h2>

COVID-19 has forced many industries to shut down or significantly reduce operations—now that cities are beginning to open certain aspects of society, it is crucial we implement comprehensive “Test and Trace” methods, especially for industrial and commercial spaces. Although various testing methods are being scaled successfully, the current contact tracing process is manual, tedious, and inefficient.

Bluetooth-based solution—it’s not for everyone

One approach that’s generated mass attention is Apple and Google’s jointly announced Bluetooth-based solution. This solution uses Bluetooth to periodically capture an identifier of other Apple or Android smartphones in the vicinity, which can be later used to assess possible exposure if a positive patient advertises their COVID diagnosis. This solution is noteworthy in its approach to consumer privacy and emphasis on decentralized contact tracing.

However, for any Bluetooth-based solution, one major limitation is poor indoor positioning accuracy in commercial and industrial spaces, such as warehouses, distribution centers, factories, office buildings, hospitals, retail stores, and hotels. Bluetooth solutions are based on either RSSI (Relative Received Signal Strength Indication) or AOA (Angle of Arrival) measurements.

A key requirement of any proposed indoor wireless contact tracing solution should be robust indoor accuracy of better than six feet. However, these Bluetooth solutions have limited positioning accuracy (10 to 100 ft) due to absorption, line of sight blockages, and multi-path reflections in indoor spaces. These cumulative inefficiencies could result in significant levels of false positives and false negatives in wireless-based contact tracing, potentially causing confusion, anxiety, and disruption.

Additionally, COVID-19 spreads easily through community transmission where people contact objects and surfaces that have been touched previously by an infected person.

Accurate indoor positioning and contact data is therefore essential to also identify objects and spaces of potential transmission for effective cleaning and disinfection—and that starts by using a WiFi-based solution.

Why WiFi-based solutions should take the spotlight

The WiFi-based contact tracing approaches are very promising for several reasons.
First, improvements in advanced analytics and WiFi quality enable WiFi-based local positioning solutions to effectively demonstrate robust sub-meter (approx. 3 ft) positioning accuracy in complex indoor environments, including warehouses, distribution centers, factories, food processing plants, hospitals, and office buildings.

These advances allow WiFi to overcome the inherent limitations of GPS and Bluetooth-based approaches to monitor real-time worker and asset position, movement, and occupancy at sub-meter levels.


<--->

main.py - This file sniffs probe requests and then generates spoofed associations to the proper access point. It then outputs the necessary data for WifiTrace.

csvtest.py - Takes the data generated by main.py and formats it properly for WifiTrace.

output.csv - A sample output file for WifiTrace.

macsniffer.py wifi.pye These two files are library files used by other components of the program.

