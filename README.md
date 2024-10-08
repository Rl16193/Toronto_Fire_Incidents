# Toronto_Fire_Incidents

## Overview

This report offers a comprehensive analysis of fire incidents, examining key aspects such as possible causes, fire sources, property types, response times, and associated losses. The dataset covers multiple fire stations, tracks incidents by the hour, and includes important metrics such as total incidents, estimated losses, response times, fire control times, rescues, and civilian casualties. These insights help assess the severity and impact of each fire event.

## Methodology

### Power BI:

1. Corrected column data types to ensure accuracy.
2. Calculated new fields for response time and fire control time.
3. Split the date-time column to allow analysis by day of the week and hour of the day.
4. Generated comprehensive fire station overview reports, focusing on the distribution of fire incidents across days, months, and hours.
5. Developed individual fire incident reports for each station.
6. Created an interactive dashboard that allows users to explore data for each station through slicers, providing an intuitive, station-specific overview.

## Results


### Firestation Overview

![Screenshot 2024-10-07 162329](https://github.com/user-attachments/assets/fcc279ff-dd07-472a-9c3b-85a16564236c)


1. The Toronto Centre fire station responded to the highest number of incidents, totaling 1,381, accounting for 5.4% of total incidents.
2. The station with the highest median response time was Scarborough-Rouge Park, recording a time of 380.86 seconds. Across all stations, the overall median response time was 306 seconds, just under the NFPA standard benchmark of 320 seconds. Stations exceeding this benchmark warrant closer investigation, particularly into the nature of the fires (source, property types).
3. Scarborough-Agincourt recorded the longest average time to control a fire, at 825 seconds, compared to the overall average of 635.45 seconds across all stations. 
4. Notably, 55.27% of incidents were resolved by extinguishing the fire upon arrival.
5. York South-Weston reported the highest total estimated losses, amounting to $76 million.

### Fire Incidents OVerview - Toronto Center FireStation

![Screenshot 2024-10-07 163027](https://github.com/user-attachments/assets/accade7f-f134-4e50-8dde-ffe45f0d3ba6)


1. A total of 85 civilian casualties were reported, averaging one casualty for every 16 fire incidents.
2. The average financial loss per incident was $17.5K.
3. Improperly Discarded Items (e.g., smoking materials) were the leading cause of fire incidents, with 130 cases, representing around 10% of the total incidents.
4. There were 55 incidents of suspected arson, primarily clustered in the Cabbagetown and James Town areas.
5. The average response time was 264 seconds, well below the NFPA standard of 320 seconds.
6. The majority of fires occurred in Multi-Unit Dwellings, accounting for 26.4% of the total incidents.
   
### Hourly Analysis

![Screenshot 2024-10-07 191236](https://github.com/user-attachments/assets/6de0162b-e4d7-4a7d-b757-57e42e6cd8a2)


1. Peak Hours for fire incidents were between 3:00 PM to 8:00 PM, with the highest concentration of incidents.
2. The most fire incidents occurred at 4:00 PM, totaling 1,615 incidents.
3. At 3:00 AM, the highest estimated financial loss of $85M was recorded. Upon closer examination, this was largely due to a single fire in 2019 at a senior school on Eglinton West and Yarrow Road, which resulted in a $50M loss. The possible cause is still under investigation.


### Monthly Analysis

![Screenshot 2024-10-07 191329](https://github.com/user-attachments/assets/759e85fa-cd2e-4f85-93f4-ee357cd79680)


1. May, June, and July, the summer months, accounted for 30% of total fire incidents.
2. The increased volume of incidents during these months led to higher response times, with July recording the highest at 342 seconds.
3. Although the average loss per fire tends to be lower during the summer due to the higher frequency of incidents and quicker control times, May stands as an exception. The school fire previously mentioned significantly contributed to the increased financial loss during this month.



