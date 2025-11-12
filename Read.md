files to change
config/template.json

                    "StopCondition": {
                    "OilLimit": 1000,
                    "RunCount": 0,
                    "MapAchievement": "non_stop",
                    "StageIncrease": false,
                    "GetNewShip": false,
                    "ReachLevel": 0
                  },
                  "Fleet": {
                    "Fleet1": 1,
                    "Fleet1Formation": "double_line",
                    "Fleet1Mode": "combat_auto",
                    "Fleet1Step": 3,
                    "Fleet2": 2,
                    "Fleet2Formation": "double_line",
                    "Fleet2Mode": "combat_auto",
                    "Fleet2Step": 2,
                    "FleetOrder": "fleet1_all_fleet2_standby"
                  },
***                  
                    "Submarine": {
                    "Fleet": 0,
                    "Mode": "do_not_use",
                    "AutoSearchMode": "sub_standby",
                    "DistanceToBoss": "use_open_ocean_support"
                  },
***
                  "Storage": {
                    "Storage": {}
                  }
                },
                "EventGeneral": {
                  "EventGeneral": {
                    "PtLimit": 0,
                    "TimeLimit": "2020-01-01 00:00:00"
                  },
                  "TaskBalancer": {
                    "Enable": false,
                    "CoinLimit": 10000,
                    "TaskCall": "Main"
                  },
                  "Storage": {
                    "Storage": {}
                  }
                },
                "Event": {
                  "Scheduler": {
                    "Enable": false,
                    "NextRun": "2020-01-01 00:00:00",
                    "Command": "Event",
