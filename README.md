# northeast_mid_atlantic_fall
A collection of scripts used to analyze the days that produce the most extreme precipitation in fall over the mid-Atlantic and Northeast United States

Script names and functions are listed below *in order*.  Note: ERA5 download scripts/requests are not included

**ar_precip_sensitivity** - determines sensitivity of various precipitation metrics to AR closeness  
**ibtracs_read** - reads IBTrACs v4.0 data into an easier format  
**tc_precip_sensitivity** - determines sensitivity of various precipitation metrics to TC closeness  

**ep_days_define** - choose stations with 95% completeness; define EP days for a range of threshold combinations  
**ep_day_definition_testing** - assessed means and trends for the sets of EP days defined in the previous script; plots tables with this information.  
**precip_basics** - shows 99th percentile threshold at each station as well as mean EP day precipitation  
**ep_days_line_plots** - display seasonal frequency and individual precipitation of EP days  
**ep_day_geotrends_overview** - plots trends in season total EP day precipitation at each station  

**ar_detection_and_weather_typing** - detects ARs based on criteria outlined in paper, and sorts EP days into 11 weather types; also plots 6-hourly maps of these days that show 850 hPa winds (arrows), MSLP (solid contours), IVT above 250 kg m-1 s-1 (grey shading), detected ARs (blue fill over IVT), tropical (red stars) and non-tropical (brown stars) IBTrACS systems, station precipitation classified by weather type (colored dots), and EP day classification (upper left).  
**ivt_threshold_sensitivity_testing** - calculates trends in seasonal AR-dominant EP day frequency and precipitation based on different IVT thresholds  

**ep_days_bar_plots** - plot seasonal frequency and cumulative precipitation from different types of EP days in different seasons  
**ep_days_geoplots** - plot mean daily precipitation and seasonal cumulative precipitation trends for different types of EP days in different seasons  
**ep_day_composites** - makes synoptic composites of EP days.  Shows 1000-500 hPa thickness (dashed contours), MSLP (solid contours), IVT above 250 kg m-1 s-1 (grey shading), and detected ARs (blue fill over IVT).  

**single_day_plot** - plots synoptic setup and precipitation at a single time step  
**Q_vectors_synoptic** - plots a variety of synoptic fields on specified EP days (Q-vectors, MFC, IVT and winds, upper-level, etc.)  
**tc_tracks_plot** - plots IBTrACS TC tracks in the 7 days preceding a set of dates (such as certain EP days)  
**neusa_sequentiality_events** - groups consecutive EP days into events and analyzes the characteristics of these events  

(no specific order) **seasonal_climatology_trends** - plots means and trends of MSLP and IVT for each season as a whole (not just EP days)  
