# DataPearl_NewsUS_API_demo
This is the repo for a demo of US News API

## API products with API proxies
The API products would include several API proxies.

### DailyRelatedness
- DailyRelatedness/latest                        
[https://34.117.4.121.nip.io/DailyRelatedness/latest](https://34.117.4.121.nip.io/DailyRelatedness/latest)                            
Clicking url will get the **latest** daily average relatedness score.                       
```
{
  "totalRows": "1",
  "rows": [
    {
      "pubDate_day": "2023-09-01",
      "Oilseed_farming": "0.03497926252228874",
      "Grain_farming": "0.03511879273823328",
      "Vegetable_and_melon_farming": "0.0354599186352321",
      "Fruit_farming": "0.03551506570407323",
      ...
      "Access_to_electricity": "0.027507092271532335",
      "Contributions_to_valueadded": "0.2683852570397513",
      "Total_economic_output": "0.0639694162777492",
      "Hours_of_paid_employment": "0.3498768849032266",
      "Tax_payment": "0.040261677333286824"
    }
  ],
  "totalBytesProcessed": "0",
  "jobComplete": true,
  "cacheHit": true
}
```

- DailyRelatedness/latest/popular_esg      
[https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg](https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg)      
Clicking url will get **top3 ESG topics** of the latest record with the highest daily average relatedness score.      

- DailyRelatedness/latest/popular_esg/top3       
[https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top3](https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top3)      
Clicking url will get **top3 ESG topics** of the latest record with the highest daily average relatedness score.      

- DailyRelatedness/latest/popular_esg/top5        
[https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top5](https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top5)      
Clicking url will get **top5 ESG topics** of the latest record with the highest daily average relatedness score.      

- DailyRelatedness/latest/popular_esg/top10
[https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top10](https://34.117.4.121.nip.io/DailyRelatedness/latest/popular_esg/top10)        
Clicking url will get **top10 ESG topics** of the latest record with the highest daily average relatedness score.

- DailyRelatedness/date/*        
[https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01](https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01)        
Clicking url will get the daily average relatedness score on **2022-10-01**. Date can be change, and format is strictly **YYYY-MM-DD**.       

- DailyRelatedness/date/*/popular_esg        
[https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg](https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg)      
Clicking url will get **top3 ESG topics** with the highest daily average relatedness score on **2022-10-01**. Date can be change, and format is strictly **YYYY-MM-DD**.       

- DailyRelatedness/date/*/popular_esg/top3        
[https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top3](https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top3)       
Clicking url will get **top3 ESG topics** with the highest daily average relatedness score on **2022-10-01**. Date can be change, and format is strictly **YYYY-MM-DD**.       

- DailyRelatedness/date/*/popular_esg/top5          
[https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top5](https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top5)        
Clicking url will get **top3 ESG topics** with the highest daily average relatedness score on **2022-10-01**. Date can be change, and format is strictly **YYYY-MM-DD**.      

- DailyRelatedness/date/*/popular_esg/top10         
[https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top10](https://34.117.4.121.nip.io/DailyRelatedness/date/2022-10-01/popular_esg/top10)         
Clicking url will get **top5 ESG topics** with the highest daily average relatedness score on **2022-10-01**. Date can be change, and format is strictly **YYYY-MM-DD**.          

- DailyRelatedness/index/*/from_date/*/to_date/*        
[https://34.117.4.121.nip.io/DailyRelatedness/index/Forced_labor/from_date/2022-11-01/to_date/2022-12-01](https://34.117.4.121.nip.io/DailyRelatedness/index/Forced_labor/from_date/2022-11-01/to_date/2022-12-01)          
Clicking url will get **Forced_labor** daily average relatedness score from **2022-11-01** to **2022-12-01**. index could be anyname returned by [https://34.117.4.121.nip.io/DailyRelatedness/latest](https://34.117.4.121.nip.io/DailyRelatedness/latest). Date can be change, and format is strictly **YYYY-MM-DD**.           


### Don't Deploy Industries 
Performance is poor, when the industries are too long.
- DailyRelatedness/latest/popular_industry ### temporally not deployed
- DailyRelatedness/latest/popular_industry/top3 ### temporally not deployed
- DailyRelatedness/latest/popular_industry/top5 ### temporally not deployed
- DailyRelatedness/latest/popular_industry/top10 ### temporally not deployed

- DailyRelatedness/date/*/popular_industry
- DailyRelatedness/date/*/popular_industry/top3
- DailyRelatedness/date/*/popular_industry/top5
- DailyRelatedness/date/*/popular_industry/top10


