# autoware-apt-testing

```bash
echo "yaml https://raw.githubusercontent.com/tier4/autoware-apt-testing/ubuntu/rosdep/humble.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/10-autoware-apt-testing.list
echo "deb [arch=amd64 trusted=yes] https://raw.githubusercontent.com/tier4/autoware-apt-testing/ubuntu/ jammy universe" | sudo tee /etc/apt/sources.list.d/autoware-apt-testing.list
```
