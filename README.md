```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/christian-rauch/osqp/resolute-lyrical-amd64/ ./" | sudo tee /etc/apt/sources.list.d/christian-rauch_osqp-resolute-lyrical-amd64.list
echo "yaml https://github.com/christian-rauch/osqp/raw/resolute-lyrical-amd64/local.yaml lyrical" | sudo tee /etc/ros/rosdep/sources.list.d/1-christian-rauch_osqp-resolute-lyrical-amd64.list
```
