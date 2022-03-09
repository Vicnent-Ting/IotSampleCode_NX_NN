## Getting Start
#### 1. Create and set the Azure Device Provision Service (DPS).
#### 2. Clone this repo.
#### 3. Modify the Parameter
Open "[run.sh]" modify by following hint
```sh
export IOTHUB_DEVICE_SECURITY_TYPE="DPS" 
export IOTHUB_DEVICE_DPS_ENDPOINT=" Put your DPS endpoint here" 
export IOTHUB_DEVICE_DPS_ID_SCOPE=" Put your DPS ID Scope here" 
export IOTHUB_DEVICE_DPS_DEVICE_ID=" Put your Device ID here" 
export IOTHUB_DEVICE_DPS_DEVICE_KEY=" Put your Device Key here" 
export IOTHUB_DEVICE_CONNECTION_STRING="" 
#export KEYPAD_INTERRUPT="DISABLE" #If KEYPAD_INTERRUPT set DISABLE, the program will never stop
export KEYPAD_INTERRUPT="ENABLE" #If KEYPAD_INTERRUPT set ENABLE, you can stop the program by pressing 'q' key
```
#### 4. Excute the code
##### For Linux Target
Please make sure you have installed python 3.7+ version.
You can check your python version by
```sh
python3 -V
```
To make run.sh excutable please run
```sh
chmod +x run.sh
```
Then finally, run the script file
```sh
./run.sh
```