# Simulatore ROS2 per compito 10/2022

[![N|Solid](https://www.unicampania.it/doc/img/logo_vanvitelli.jpg)](https://www.ingegneria.unicampania.it/roboticslab)

Porting ROS2 del simulatore in [link](https://github.com/Vanvitelli-Robotics/panda_temp_sim_2210)

## Install

- Installare questo pacchetto e il simulatore, infine scaricare le dipendenze
Nella cartella src del ros workspace
```bash
git clone https://github.com/Vanvitelli-Robotics/uclv_aipr_panda_sim.git #Simulatore
git clone https://github.com/Vanvitelli-Robotics/aipr_2210_support.git
sudo apt update && rosdep install -r --from-paths . --ignore-src --rosdistro $ROS_DISTRO -y
```

## Avviare la demo

Avviare il simulatore:
```bash
ros2 launch aipr_2210_support sim.launch.py
```

## License

GNU General Public License v3.0
