# CSGO Round Winner Predcition

### **Obejctive** <br>

This a notebook detailing the programming of a predictive model that aims to predict under what conditions can a round of Counter Strike: Global Offensive be won. The modeling is done using a dataset obtained from `kaggle` named [CS:GO Round Winner Classification](https://www.kaggle.com/datasets/christianlillelund/csgo-round-winner-classification/data).

The working model can be found at [HuggingFace](https://huggingface.co/spaces/TRusso/CSGO_Round_Winner_Prediction?logs=build)

### **Dataset Description**:

| Column                       | Description                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| time_left                    | Time remaining in the current round (in seconds)                |
| ct_score                     | Counter-Terrorist team score                                    |
| t_score                      | Terrorist team score                                            |
| map                          | Name of the map being played                                    |
| bomb_planted                 | Indicates whether the bomb is planted or not                    |
| ct_health                    | Health of Counter-Terrorist team                                |
| t_health                     | Health of Terrorist team                                        |
| ct_armor                     | Armor points of Counter-Terrorist team                          |
| t_armor                      | Armor points of Terrorist team                                  |
| ct_money                     | Money available for Counter-Terrorist team                      |
| t_money                      | Money available for Terrorist team                              |
| ct_helmets                   | Number of helmets bought for Counter-Terrorist team             |
| t_helmets                    | Number of helmets bought for Terrorist team                     |
| ct_defuse_kits               | Number of defuse kits bought for Counter-Terrorist team         |
| ct_players_alive             | Number of Counter-Terrorist team players alive                  |
| t_players_alive              | Number of Terrorist team players alive                          |
| ct_weapon_ak47               | Number of AK-47 weapons bought for Counter-Terrorist team       |
| t_weapon_ak47                | Number of AK-47 weapons bought for Terrorist team               |
| ct*weapon***X**              | Number of **X** weapons bought by Counter-Terrorist team        |
| t*weapon***X**               | Number of **X** weapons bought by Terrorist team                |
| ct_grenade_hegrenade         | Number of HE grenades bought for Counter-Terrorist team         |
| t_grenade_hegrenade          | Number of HE grenades bought for Terrorist team                 |
| ct_grenade_flashbang         | Number of flashbangs bought for Counter-Terrorist team          |
| t_grenade_flashbang          | Number of flashbangs bought for Terrorist team                  |
| ct_grenade_smokegrenade      | Number of smoke grenades bought for Counter-Terrorist team      |
| t_grenade_smokegrenade       | Number of smoke grenades bought for Terrorist team              |
| ct_grenade_incendiarygrenade | Number of incendiary grenades bought for Counter-Terrorist team |
| t_grenade_incendiarygrenade  | Number of incendiary grenades bought for Terrorist team         |
| ct_grenade_molotovgrenade    | Number of molotov grenades bought for Counter-Terrorist team    |
| t_grenade_molotovgrenade     | Number of molotov grenades bought for Terrorist team            |
| ct_grenade_decoygrenade      | Number of decoy grenades bought for Counter-Terrorist team      |
| t_grenade_decoygrenade       | Number of decoy grenades bought for Terrorist team              |
| round_winner                 | Team that won the round (CT or T)                               |
