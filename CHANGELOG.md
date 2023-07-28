[release notes updated]

[1.4.0]

Changed

AQT-334 :

User Impact --> The API that sends "true/false" national promotions and discounts to display the "PROMO" banner on front services uses an inheritance system that does not allow optimal management of promotions

Solution Implemented --> Removed the dependency of "hasPromo" checks in Operations and Services

AQT-347 :

User Impact: --> Currently, into the tariff national grid, we have one line for the tyres setting, only depending from the tariff zone.

Solution Implemented --> We would like to duplicate this line to be able to get a package price for each size of wheels, from 14" to 20".  The quotation front office allows the customer to select the size of the wheel and AQT should send the appropriate package price regarding the tyre size selected.


AQT-349:

User Impact: --> There is no option to update oil viscosities in UI.

Solution Implemented --> Add/update and delete options have been added
