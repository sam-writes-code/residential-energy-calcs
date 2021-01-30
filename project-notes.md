### Project Notes
#### Background
I have the following available to use:
* Cost of heatpump and installation
* Name of new heat pump - can use for getting COP curve from manufacturer
* Data from the Met Office - can download this, use SQL for data wrangling and to create a clean `.csv` file that I can feed into my Python script


#### Plan
1. Find out how to download Met Office data for local area.
2. Write Python script to download Data.
3. Write SQL script to convert into useful data.
4. Use Excel to put weather data into graphical format.
5. Look at heat pump from PDF quote.
6. Try to get performance curve from manufacturer website in data format.
7. If unable to get in data, only in picture of the curve, see at what temperature the COP falls below 2.0 and below 3.0 (i.e. 2.0 for case where some electricity is from solar panel and cheap, 3.0 for case where electricity is from grid at ~3x as expensive as oil per kWh energy)
8. Check how often temperature is below temperatures from step 7, using Met Office data in Excel. Include details on time below temperature when it is between 6am-11pm (as less requirement for heat during sleeping hours).
9. Write Python script to calculate time below temperature as well.
10. Calculate total energy usage from oil and heat pump using this hybrid system. If not that great, i.e. not good enough to get max RHI, then maybe ground source heat pump if preferable.
