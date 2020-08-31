# Datascience-A-cholera-Outbreak-Study
'''
Three different datasets containing deaths location, number of deaths, number of attacks, number of contaminated water pumps along with other information is studied to prove a hypothesis- Cholera spreads due to contaminated water and drinages. Back then, it was beleived that Cholera spreads through air.

The data is a cleaned data, so only exploratory analysis is done to check the validity of the hypothesis.

As a first step, the coordiates of the location of death is merged and ploted in the map using folium library. then the location of the pumps are posted over the existing maps. The map clearly shows the death happends around the waterpump location.
As waterpumps on the contaminated location was removed, the deaths and attacks should come reduce drastically to prove our hypothesis. The water pump was removed in '1854/9/8' and the daily deaths 30 days before the removal of the water pump and 30 days after the removal of the water pumps is plotted using Bokeh- an interactive data visualization library.

The chart clearly shows that the deaths, and attacks went down drastically after the removal of the water pump thus proving the hypothesis. 
'''
