# weatherlist

Main ideas:
1. Keep the interface easy
2. Register after use
3. A list of destinations + time to get there /in hours rounded up by 30 minutes/ [(distance rounded by 25km)] + The weather now + The weather on arrival if I drive now + The weather tomorrow + The weather on next Sat and Sun (if available) + my free-text-comments
4. The weather should be shown in icons and average temperature
5. Requests should be cached, refreshing once per given period (3hrs? 6hrs? once per day?)
6. Request interface should be decoupled in order to connect to other services


Example: 
a table, that looks like
Paris | 7hrs (800km) | rainy +20 | rainy +5 | rainy +20 | sunny +25 | would need to stay two days there
Garmisch Partenkirchen | 1.5hr (100km) | rainy +10 | sunny +15 | rainy +10 | sunny +15 | visit Zugspitze



