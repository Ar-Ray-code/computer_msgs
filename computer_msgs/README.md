# computer_msgs

For rclshark

```
rosidl generate -o gen -t c -t py pc_status msg/PcStatus.msg
rosidl generate -o gen -t c -t py pc_status_srv srv/PcStatusSrv.srv
```