import geopandas as gpd
import pandas as pd
from shapely.ops import cascaded_union
import folium

pharm = gpd.read_file('C:/Users/Dell/Documents/location_analysis/pharmacies_23037.gpkg')
zkh = gpd.read_file('C:/Users/Dell/Documents/location_analysis/zkh.gpkg')
zkh = zkh.to_crs('epsg:23037')
zkh = zkh.dropna(subset = 'geometry')
zkh = zkh.reset_index(drop = True)

pharm['buffer_300m'] = pharm['geometry'].buffer(300)
zkh['buffer_300m'] = zkh['geometry'].buffer(300)

pharm = pharm.set_geometry('buffer_300m', drop = True)
zkh = zkh.set_geometry('buffer_300m', drop = True)

m = folium.Map(location = [55.8, 37.8], tiles = 'cartodbpositron', zoom_start = 13)
folium.GeoJson(data = zkh.head(100)['geometry']).add_to(m)
m
