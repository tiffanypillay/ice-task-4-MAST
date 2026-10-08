**ICE TASK 4 MAST- WEATHER APP**
-


**Name-** Tiffany Pillay

**Student ID-** 10524721

**Task-** MAST ICE TASK 4- WEATHER APP


**Error log table**
-

| # | Where is the Error? | What Was Wrong? | Type of Bug | How It Was Fixed |
| --- | --- | --- | --- | --- |
| 1 | Top of `App.tsx` | `ImageBackground` was used in the app code, but it wasn't added to the import list at the top. | Missing Code | Added `ImageBackground` to the top import list. |
| 2 | Main Picture (`ImageBackground`) | The picture link was written as plain text instead of using `{ uri: ... }`. | Wrong Format | Wrapped the picture link inside `{ url: ... }`. |
| 3 | City Buttons | Clicking a city button checked country names instead of city names, breaking the buttons. | Logic Error | Updated the code to check and match city names. |
| 4 | Main Picture Area | The main picture container was too short and cut off text, and the dark background layer was too faint to read white text. | Styling / Layout | Increased the height and darkened the background tint so white text is easy to read. |
| 5 | Details Box | The detail box showed the name label twice instead of showing the actual number value. | Display Error | Changed the second label text to show the `{value}`. |
| 6 | Details Grid | Details were stretched across the entire width, stacking everything in 1 long column. | Layout | Changed item width to `48%` so they sit side-by-side in 2 neat columns. |
| 7 | Humidity Field | Humidity was showing the "Feels Like" temperature number by mistake. | Wrong Information | Connected the Humidity field to the actual humidity percentage data. |
| 8 | 24-Hour Forecast | The 24-hour weather cards stacked vertically on top of each other. | Layout | Turned on horizontal scrolling (`horizontal={true}`) so you can swipe side-to-side. |
| 9 | 24-Hour Forecast | Every hour showed the main overall temperature instead of that specific hour's temperature. | Wrong Information | Updated the temperature code to pull each specific hour's temperature. |
| 10 | 5-Day Forecast | The 5-day weather list was completely blank on screen. | Code Syntax Error | Fixed the bracket style so the 5-day list actually displays on the screen. |
| 11 | 5-Day Forecast | The high and low temperatures were swapped, and the information was stacked awkwardly. | Layout & Info Error | Lined up the info in a clean row and put the high and low numbers in the right order. |
| 12 | Sun & Moon | The Sunrise box was showing Sunset times instead. | Wrong Information | Fixed the code to show `sunrise` data in the Sunrise box. |

-

**Images of App**

-<img width="200" height="400" alt="we1" src="https://github.com/user-attachments/assets/6f006898-5ad7-42c4-93ee-37ff8ff724a8" />
-


-<img width="200" height="400" alt="we2" src="https://github.com/user-attachments/assets/32400277-7979-410a-aba1-d75cf68f346e" />
-


-<img width="200" height="400" alt="we3" src="https://github.com/user-attachments/assets/56b5ea75-25e4-4712-9a3d-4f955f4da279" />
-

