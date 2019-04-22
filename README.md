# GpsApp
Location app for places
in the app i'm using GeForce through GoogleApi to save places in local DB (SqlLite).
set GeForce rdaius to 50m , and timeout to 24hrs. 
list of places to save and show on the Google map service.
using BroadcastReciver as the service to check if im in the GeForce radius.
using BroadCastReciver to set Ringer mode silent when enter the GeForce radius.
using ContentProvider to access the DB.
and what is more important about this app that it trying to use as much as it can in GeoForce to use less battery.
