# TDS-PH-TMP--Calibration-IIITH


TDS-PH-TMP--Calibration-IIITH
-------/TDS-PH-TMP-Mean-med--tmpcom----

is my MAIN CODE WHERE I CALIBRATE PH SENSOR 
USING THIS command 
1.ENTERPH
2.CALPH
3.EXITPH





/FOR TDS SENSOR I USE ADC VALUE AND CONVERT THAT ADC VALUE TO TDS VALUE IN PPM 

/AND for tds I ALSO USE TEMPERATURE-COM FOR MORE ACCURATE VALUE 





-----AND Only Tds and tmp com only v1--------
and this file i calibrate only tds using adc and also add tmp com 


---------rtc-------------
in with rtc file all data is there with rtc



--------------esp32 tds cali  v2--with adc try------------
on this file i just add 16 bit adc with esp 32 and measure adc output ,,, sometime its showing - value so ami minimum value 0 kore diyechi 
and adc pin vcc holo 3.3v and tds pin vcc is 5v





-------------------esp32-tm-com-adc--c3--work goog1-----------------
esp32,adc 12 bit ,,,tds cunnectes with 5v ,,tmp cunnectes with 3v ,,,adc is 3v ,,, its good working remember when you cullect the adc value of any water you need to cullect the adc value at 25degree 

