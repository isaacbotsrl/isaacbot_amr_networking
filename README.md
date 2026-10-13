<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="icons/isaacbot-lockup-white-bold.svg">
    <img src="icons/isaacbot-lockup-black-bold.svg" alt="IsaacBot" width="240">
  </picture>
</p>

# isaacbot_amr_networking

Networking for the Ardennes. The repo sits in the ROS workspace's `src/`; nothing in it is a ROS
package, so `COLCON_IGNORE` keeps colcon away from it.

| Folder | What it is |
|--------|------------|
| [`rutx11/`](rutx11/README.md) | The **Teltonika RUTX11** router: its network layout, and the web page that switches the router's Wi-Fi uplink without breaking the firewall/NAT rules (`uplink_manager`). Runs on the isaacbot as the container `isaacbot-amr-network` of [isaacbot_amr_balenaos](https://github.com/isaacbotsrl/isaacbot_amr_balenaos), or on a laptop with `rutx11/run-local.sh`. |
