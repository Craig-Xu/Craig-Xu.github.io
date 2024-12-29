+++
date = '2024-12-29T16:41:33+08:00'
draft = false
title = 'ROS环境搭建与配置'
categories = 'Robotics'
featured_image = "https://tse4-mm.cn.bing.net/th/id/OIP-C.CJy0h23BhZ8U6T0kk7wPRAAAAA?rs=1&pid=ImgDetMain"
+++

常见ROS环境配置记录

<!--more-->

# ROS

```
wget http://fishros.com/install -O fishros && . fishros
```

# Gazebo 

```
cd ~/.gazebo/
git clone https://github.com/osrf/gazebo_models.git models
sudo chmod 777 ~/.gazebo/models
sudo chmod 777 ~/.gazebo/models/*
```