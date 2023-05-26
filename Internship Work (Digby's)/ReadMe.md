Following is the work I completed while employeed with Digby's Detective & Security Agency (May 2022 - December 2022).

The premise of these projects being a third party robot that detects people and license plates, that then sends alerts to Digby's 
once such a detection occurs. 

A CSV can then be pulled from the robot detailing each alert that has occured over a given period of time & takes the following form:

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

| ID	| Date	| Time	| MIN	| Latitude	| Longitude	| Event Type	| Sector Name	| Threat Level	| Clear |	Clear Date	| Clear Time	| Sign-off Name	| Comments |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2998046	| 05/08/2023	| 22:32:08 | 72	| 39.78712615	| -82.93416547  | Person(s) detected	| Cardinal Health OH	| Red	| TRUE	| ('05/08/2023',)	| ('22:35:55',)	| mmcbride@digbysecurity.com	| Cleared by 9133 |
| 2997844	| 05/08/2023	| 20:45:00 | 72	| 39.78714519	| -82.93417419	| Person(s) detected	| Cardinal Health OH	| Red	| TRUE	| ('05/08/2023',) | ('22:35:55',)	| mmcbride@digbysecurity.com	| Cleared by 9133 |
| 2991642	| 05/04/2023	| 20:39:51 | 72	| 39.7870004	| -82.93575322	| Person(s) detected  |	Cardinal Health OH	| Red	| TRUE	| ('05/04/2023',)	| ('21:23:24',)	| watchcommander@digbysecurity.com	| Alerts cleared by wc 0919 |
| 2985249 |	05/01/2023	| 2:30:12	 | 72	| 39.78712991	| -82.93416792	| Person(s) detected	| Cardinal Health OH	| Red	| TRUE	| ('05/01/2023',)	| ('04:08:38',)	| watchcommander@digbysecurity.com	| worker wc 7732 |
| 2985180 |	05/01/2023	| 1:34:02  | 72	| 39.78712991	| -82.93416792	| Person(s) detected	| Cardinal Health OH	| Red	| TRUE	| ('05/01/2023',)	| ('02:15:50',)	| watchcommander@digbysecurity.com	| wc 7732 |

etc....

I was assigned 3 tasks given this information, leading to three independent project designs & implementations:
  1). Monthly Reports
      - Consolidating & manipulating the given data each month as a method of progress monitoring and control.
      This included determining average response times and splitting the alerts by the period of time in which
      it took to respond to it (i.e., within 5 minutes, within 10 minutes, etc.). 
  2). Employee Reports
      - This project centered around retrieving repsonse data from each individual employee to evaluate 
      performance. It required both aggregating all individual data, as well as cross refrencing other
      data sets containing information about the hours each individual was activley working.
  3). Alert Density Report
      - In order to maximize company cost-benefits for each client, robots and officers needed to be deployed 
      during the hours where the most activity was seen. As such, I was asked to create a way of quanitifying 
      alert data/history by hour leading to the alert density report.
