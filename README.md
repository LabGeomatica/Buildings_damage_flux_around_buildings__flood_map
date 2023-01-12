# Buildings_damage_flux_around_buildings_flood_map

Program name: Buildings damage - Flood map simulating flux around buildings

Created on Fri Dec  9 2022

@authors: Prof Giorgio Boni, Prof Silvia De Angeli, Prof Bianca Federici, Giulia Mazzaccaro

Giulia was student at the University of Genova, developping the program for Environmental Engineering master course thesis

(C) 2022 by Boni, De Angeli, Federici, Mazzaccaro - University of Genova'

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/.
If you need to contact us: ilaria.ferrando at edu.unige.it, silvia.deangeli at unige.it, bianca.federici at unige.it

This plugin estimates the percentage and the economic damage from flooding for each residential, commercial, industrial and transport building in a given area of interest, through the use of guidelines and Joint Research Centre's vulnerability curves.

Automatic gis based method to estimate the economic damages and percentage of damages caused by floods to buildings in an urban environment, in particular a processing plugin implemented in QGIS (Free and Open Source Geographic Information System) that allow a detailed and rapid estimation of the percentage and the economic damage to buildings of a specific urban area. 
The methodology follows the steps of the flood risk assessment and start from two input maps: one an official map that represent building exposed to a specific scenario and one a flood map from hydraulic simulations that well represent the flood depth reached by the water in every point. 
In fact, it is proposed a methodology to associate the flood depth with every buildings of the area of interest using a flood map obtained by hydraulic simulations that show the water flux around the buildings, taking into account their presence.
For the evaluation of the flood damage the JRC vulnerability curves was used, that permit to asses the maximum direct tangible physical damage values to 6 impact categories. 
These curves are representatives of average European building behaviour.

The document uploaded:
Buildings_damages.model3 - Model in which all the inputs and algorithms necessary for the execution of the methodology that characterizes the plugin are inserted;
"Buildings_damage_flux_around_buildings__flood_map" folder : folder upoadable in QGIS to the creation of a new processing pluging (from ZIP), that contain the algorithm of the script and the metadata;
GiuliaMazzaccaro_thesis.pdf : for detailed information about the procedure performed.
