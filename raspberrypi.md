RaspberryPi runs vision, data-aggregator, and tcp-serial-redirect.

RaspberryPi details:
  - Username: pi
  - Password: raspberry
  - hostname: uofmrestraspberrypi
  - ip on wifi router: 192.168.0.108

Login to pi
  ```
  ssh pi@uofmrestraspberrypi
  cd rest
  ```

Run all three scripts
  ```
  ./rest.sh
  ```

Run individual scripts (will need separate terminals for each script)
  ```
  --- New Terminal ---
  cd vision
  ./vision.sh
  --- New Terminal ---
  cd data-aggregator
  ./data-aggregator.sh
  --- New Terminal ---
  cd data-aggregator
  ./tcp-serial.sh
  ```


