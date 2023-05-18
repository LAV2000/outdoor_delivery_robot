# outdoor_delivery_robot

Outdoor Delivery Robot (HUST)
## Yêu cầu
- Ubuntu [20.04](https://releases.ubuntu.com/focal/)
- ROS2 [Foxy](https://docs.ros.org/en/foxy/Installation.html)

## Packages
|Package|Description  |
|--|--|
|odr_description|Mô phỏng robot của bạn trong Gazebo với file URDF|
|odr_control|Cấu hình bộ điều khiển cho Robot|

## Simulator
Clone Repo này về thư mục *src* trong *workspace* của bạn:

    git clone https://github.com/LAV2000/outdoor_delivery_robot.git
Quay lại thư mục chính của  *workspace* chạy *rosdep* để cài đặt các packages còn thiếu:

    rosdep install --from-paths src --ignore-src --rosdistro=$ROS_DISTRO -y
   Build the *workspace*:
   

    colcon build
Source your *workspace*:

    source install/setup.bash
