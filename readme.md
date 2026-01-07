[Resources](https://www.waveshare.com/wiki/ESP32-S3-Touch-AMOLED-2.06)

SDK Steps: 

Requires v5.4.2 and not v6.xx because of waveshare examples limitation.

`git clone -b v5.4.2 --recursive https://github.com/espressif/esp-idf.git esp-idf-5.4.2`
`cd esp-idf-5.4.2`
`./install.sh esp32s3`
`. ./export.sh`

`echo '~/esp32_projects/esp-idf-5.4.2/export.sh' >> ~/.bashrc`
`source ~/.bashrc`

`idf.py build`

`idf.py flash`
