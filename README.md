### Prayer times for mosques ###

## Featurs

* Show prayer times on a big LCD screen
* Prayer time and iqama flashing
* Show douaa after athan
* Show Aid parayer time after configuring it


## How to configure

The config file is in data/conf.json

```
{
    "joumouaaTime": "",
    "aidTime": "",
    "minimumIchaTime": "19:50",
    "maximumIchaTimeForNoWaiting": "22:00",
    
    "timesPath": "houilles",
    "hijriAdjustment": 0,
    "adhanDouaaEnabled": true,
    "androidAppEnabled": true,
    "headerText": "Mosquée ES-sounna - Houilles",
    "site": "Ces horaires sont accessbiles sur <span style=\"color: #1b6d85;\">http://priere.mosquee-houilles.fr</span> et sur notre application android",
    "supportTel": "06.29.11.16.41",
    "footerText": "Association SFI - Tél. 09.50.31.41.77 / 06.61.49.91.70 | RIB : IBAN FR76 3000 3018 6200 0504 6187 693 / BIC SOGEFRPP",
    "prayersWaitingTimes": [20, 10, 10, 5, 10]
}
```

* `joumouaaTime` if this param is set it will be diplayed on screnn otherwhise 12:10 is displayed in winter and 13:10 in summer
* `aidTime` if set the text and time of aid wil be displayed
* `minimumIchaTime` that means ichaa time will be fixed at the choosen value if lower then it, let it empty if you do not want this behaviour
* `maximumIchaTimeForNoWaiting` if set 


NB : after changing the conf file we should refresh page in browser