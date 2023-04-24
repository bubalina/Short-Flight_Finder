# Short-Flight_Finder
A Python script that generates a list of airport pairs that are within a certain distance of each other, based on a list of airport codes. This can be useful for finding short flights for possible low fares. The script uses the Haversine formula to calculate the great-circle distance between two points on a sphere, such as the Earth. The project also includes unit tests to ensure the script works correctly.


## Data

The list of airport codes used in this project was sourced from [OpenFlights](https://openflights.org/data.html). Specifically, the `airlines.dat` file was used, which contains information on over 7,000 airports around the world.

The data is provided under the Open Database License (ODbL), which allows you to freely share, modify, and use the data, as long as you give attribution to the original source and make your changes available under the same license. For more information, please see the [OpenFlights Data License](https://openflights.org/data.html#license).


## License

This project is licensed under the GNU Affero General Public License v3.0. This license requires anyone who uses or distributes the code to provide access to the source code and any modifications they make. It also requires that any web-based applications that use the code must also make the source code available to users. For more information, please see the [LICENSE](LICENSE) file.
