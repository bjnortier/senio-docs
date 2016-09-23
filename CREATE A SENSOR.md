# CREATE A SENSOR

As a user, the first step is to create a new sensor on senio.io. Your sensors are shown by clicking "Sensors" on the navigation bar.

Click on "CREATE NEW SENSOR":

![EMPTY SENSORS](https://cloud.githubusercontent.com/assets/57994/18778448/99dc1b0e-8174-11e6-894a-e6750abb7b56.png

The "CREATE NEW SENSORS" dialog is displayed:

Using this dialog you will name your sensor and add new measurement fields.

We will create a sensor that has 2 "scalar" measurements (temperature and humidity), and one "image" field (cam1). More types of fields (like boolean values and map coordinates) are in the pipeline.

Scalar measurements can also have a "Unit", which will makes the graphs more understandable (scalar measurements with the same can be grouped together on the same graph).

*NOTE:* When you post measurements, you don't need to post values for all the fields at the same time, e.g. the "temperature" and "cam1" measurements can be submitted at different rates and times (i.e. "temperature" every minute and "cam1" image every 15 minutes).

A Raspberry Pi with a DHT22 (temperature & humidity) sensor and a camera can be defined as follows:

After clicking the "CREATE" button, the sensor will be displayed:


*NOTE:* The "Device key" will be used from your device to authorize the measurement being posted to your account:
