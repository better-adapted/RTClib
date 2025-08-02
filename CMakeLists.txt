# CMakeFiles.txt inside "RTClib" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/RTClib.cpp" "src/RTC_DS1307.cpp" "src/RTC_DS3231.cpp" "src/RTC_Micros.cpp" "src/RTC_Millis.cpp" "src/RTC_PCF8523.cpp" "src/RTC_PCF8563.cpp"
                    INCLUDE_DIRS "src/." "."
                    REQUIRES "arduino Adafruit_BusIO" # Library requires Arduino
                    )

project(RTClib)