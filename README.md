# location-history-visualizer

**Available online: [alexander.bayand.in/location-history-visualizer](https://alexander.bayand.in/location-history-visualizer/)**

A tool for visualizing your complete, consolidated, collected Google [Location History](https://google.com/locationhistory).

It works directly in your web browser &ndash; no software to download, no packages to install. **Everyone deserves to know what data is being collected about them, without having to fiddle with cryptic pieces of software.**

*location-history-visualizer* takes raw Google Takeout output and produces a heatmap of all of your location data over time, overlaid on an interactive map.

## Packages used
* [leaflet.js](https://leafletjs.com/), for rendering the interactive map
* [leaflet.heat](https://github.com/bayandin/Leaflet.heat), for rendering the heatmap overlay; patched to use `rbush` library (see below)
* [rbush](https://github.com/mourner/rbush), for speeding up points filtering
* [oboe.js](https://github.com/jimhigson/oboe.js/), for processing said gigantic files


## License

Copyright (C) 2014 Theopolisme <theopolismewiki@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
