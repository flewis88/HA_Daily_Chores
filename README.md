# HA_Daily_Chores
Daily chores for the kids, resets daily and shows a total on the graph.

1. Copy YAML from  automations.yaml, scripts.yaml & sensors.yaml into your respective files
2. Go to Settings -> Devices & Serivces -> Helpers
3. Create toggle helpers for each chore and select the appropriate icon:
   
   a. chore_kid1_breakfast
   
   b. chore_kid1_dressed
   
   c. chore_kid1_reader
   
   d. chore_kid1_tablet

   e. chore_kid1_teeth
   
   f. chore_kid1_toilet
   
   g. chore_kid1_water

   h. chore_kid1_bag
   
   i. chore_kid2_breakfast
   
   j. chore_kid2_dressed
   
   k. chore_kid2_reader
   
   l. chore_kid2_tablet
   
   m. chore_kid2_teeth
   
   n. chore_kid2_toilet
   
   o. chore_kid2_water
   
   p. chore_kid2_bag
   
6. Create counter helpers for each child:
   
   a. chore_star_counter_kid1
   
   b. chore_star_counter_kid2
8. Create a "Manual" card on your Dashboard, and copy in the YAML from Dashboard_ChoreCard.yaml


It may be possible to create the helpers in YAML but I found they're documented in a file that HA doesn't like you meddling with, so I just created them thru the Web interface. I also have it on a conditional card, so the chores disappear after 9am on weekdays and have a reduced list of chores that show on weekends, and disappear after 10am.

![Chores](https://github.com/user-attachments/assets/d0e79324-f5a1-4835-b52d-5ead8454d445)
