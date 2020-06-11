
RAIL API Documentation

Get started
===========

        API Endpoint

        https://pnr-status-indian-railway.p.rapidapi.com/rail
                    

The Rail PNR API provides programmatic access to read Railway PNR status
data. Retrieve passenger information and journey information, provide an
oauth connexion, retrieve a familly, filter them, etc.

To use this API, you need an **API key**. Please contact us at
[dev2919@gmail.com](mailto:dev2919@gmail.com) or visit [Vendor
Website](https://rapidapi.com/dev2919/api/pnr-status-indian-railway) to
get your own API key.

Get characters
--------------

    # Here is a pure Javascript fetch example
    fetch("https://pnr-status-indian-railway.p.rapidapi.com/rail/8531575878", {
        "method": "GET",
        "headers": {
        "x-rapidapi-host": "pnr-status-indian-railway.p.rapidapi.com",
        "x-rapidapi-key": "<< YOUR API KEY HERE >>"
        }
    })
    .then(response => {
        console.log(response);
    })
    .catch(err => {
        console.log(err);
    });
                    

To get characters you need to make a GET call to the following url :\
 `https://pnr-status-indian-railway.p.rapidapi.com/rail`




    Result example :
    {10 items
    "arrival_data":{2 items
    "arrival_date":"Tue, 09 Jun 04:45",
    "arrival_time":"Tue, 09 Jun 04:45",
    }
    "boarding_station":"Bhusaval Junction-BSL",
    "chart_status":"Chart Prepared",
    "class":"3A",
    "departure_data":{2 items
    "departure_date":"Sun, 07 Jun 06:25",
    "departure_time":"Sun, 07 Jun 06:25",
    }
    "passenger":[4 items
    0:{3 items
    "booking_status":"W/L 6,RLGN",
    "current_status":"CNF B2 1",
    "name":"Passenger 1"
    }
    1:{3 items
    "booking_status":"W/L 7,RLGN",
    "current_status":"CNF B2 4",
    "name":"Passenger 2"
    }
    2:{3 items
    "booking_status":"W/L 8,RLGN",
    "current_status":"RLWL 1",
    "name":"Passenger 3"
    }
    3:{3 items
    "booking_status":"W/L 9,RLGN",
    "current_status":"RLWL 2"
    "name":"Passenger 4"
    }
    ]
    "quota":"",
    "reservation_upto":"Patliputra Junction-PPTA",
    "train_name":"LTT PPTA SPL-02141",
    "train_number":"LTT PPTA SPL-02141",
    }
                    

#### REQUEST PARAMETERS

  Field             Type     Description
  ----------------- -------- --------------------------------------------------------------------------
  secret\_key       String   Your API key.
  PNR No.           String   (Required) A key number to find journey information.
  Train number      String   (optional - will be added soon) Live track and schedule of train journey
  x-rapidapi-host   String   x-rapidapi-host key

RAIL-API
--------

By [Devesh Pawar](https://dev2919.github.io/) & [Prajeesh
Javkar](https://javkarprajeesh.github.io/Portfolio/index.html) © 2020.\
 This API is intented for educational purpose only. Use this API at your
own discretion.

[](https://github.com/dev2919 "View source on Github")
