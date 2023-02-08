# humble-focal-edna-deps
Collection of downloaded dependencies for building and running edna

After downloading run

rosdep install -y -r --ignore-src --from-paths src --rosdistro ${ROS_DISTRO}

colcon build --merge-install --cmake-args -DCMAKE_BUILD_TYPE=RelWithDebInfo