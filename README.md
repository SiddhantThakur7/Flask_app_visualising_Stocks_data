# Flask_app_visualising_Stocks_data
The following is dynamic Stocks data visualization webapp 

The app is dynamic and contains the data plot for the data from the 1st of january till today (implies today is a weekday, since weekends arent business days, market is closed.)

The app uses google API and requests library in python to get the dynamic data on each call. The data visualisation is interactive and has the options of zooming a certain area, downloading the plot as .jpg format image and Mouse Zoom which are the javascript functionality.

The pages are served through flask implementation in python and the visualizations are done using the bookeh library.

The final web app is hosted life on heroku using the heroku CLI.


Link for the app --> https://appflasksid.herokuapp.com/plot/
