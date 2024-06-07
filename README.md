# CAHOOTS-WEATHER

When running script:
  Do not "run all cells" ! : 
  BUG: For whatever reason, cells 2-4 need to be ran twice in order to clean the data properly. 

Weather Variables Used: 

https://www.ncei.noaa.gov/pub/data/uscrn/products/hourly02/
   
1   T_HR_AVG  [7 chars]  cols 66 -- 72
              Average air temperature, in degrees C, for the entire hour. See Note 
          F.

2   T_MAX  [7 chars]  cols 74 -- 80
              Maximum air temperature, in degrees C, during the hour. See Note 
          F.

3   T_MIN  [7 chars]  cols 82 -- 88
              Minimum air temperature, in degrees C, during the hour. See Note 
          F.

4   P_CALC  [7 chars]  cols 90 -- 96
              Total amount of precipitation, in mm, recorded during the hour. See 
          Note F.

5   SOLARAD  [6 chars]  cols 98 -- 103
              Average global solar radiation, in watts/meter^2.

6   SOLARAD_MAX  [6 chars]  cols 107 -- 112
              Maximum global solar radiation, in watts/meter^2.

7   SOLARAD_MIN  [6 chars]  cols 116 -- 121
              Minimum global solar radiation, in watts/meter^2.

8   SUR_TEMP  [7 chars]  cols 127 -- 133
              Average infrared surface temperature, in degrees C.

9   SUR_TEMP_MAX  [7 chars]  cols 137 -- 143
              Maximum infrared surface temperature, in degrees C.

10   SUR_TEMP_MIN  [7 chars]  cols 147 -- 153
              Minimum infrared surface temperature, in degrees C.

11   SOIL_MOISTURE_5  [7 chars]  cols 165 -- 171
              Average soil moisture at 5 cm below the surface, in m^3/m^3. See 
          Note K.

12   SOIL_TEMP_5  [7 chars]  cols 205 -- 211
              Average soil temperature at 5 cm below the surface, in degrees C. 
          See Note K.

F.  The hourly values reported in this dataset are calculated using 
            multiple independent measurements for temperature and precipitation. 
            USCRN/USRCRN stations have multiple co-located temperature sensors 
            that make 10-second independent measurements which are used to 
            produce max/min/avg temperature values at 5-minute intervals. The
            precipitation gauge is equipped with multiple load cell sensors to 
            provide independent measurements of depth change at 5-minute 
            intervals.  
K.  USCRN stations have multiple co-located soil sensors that record 
            independent measurements at 5-minute intervals. The hourly soil 
            values reported in this dataset are calculated from these multiple 
            independent measurements. Average soil moisture (volumetric water 
            content) is the ratio of water volume over sample volume 
            (m^3 water/m^3 soil).
