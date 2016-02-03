^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package nao_moveit_config
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.9 (2016-02-03)
------------------
* remove nao_meshes from dependency because license not displayed on buildfarm
* Contributors: Mikael Arguedas

0.0.8 (2016-02-03)
------------------
* updated dependency list
* Contributors: Mikael Arguedas

0.0.7 (2016-01-23)
------------------
* homogenize group names to match side_bodyChain
* added end effectors for legs
* update collision matrix: fix collision on NAO's feet
* rename demo_real.launch into moveit_planner.launch to match tutorials
* Merge pull request `#9 <https://github.com/ros-naoqi/nao_moveit_config/issues/9>`_ from nlyubova/master
  missing collisions
* fixing srdf, adding missing collisions
* fixing the projection_evaluator joints for hand groups
* added demo_real.launch from nlyubova's fork
* Contributors: Mikael Arguedas, Vincent Rabaud, nlyubova

0.0.6 (2015-10-21)
------------------
* updating the readme
* fixing the config for the most recent urdf
* add myself as a maintainer
* Contributors: Vincent Rabaud, nlyubova

* add myself as a maintainer
* Contributors: Vincent Rabaud

0.0.5 (2015-05-25)
------------------
* install the .setup_assistant file for potential introspection
* remove the URDF and fix the README
* add a .setup_assistant
* Added foot and pelvis fake controllers
* Added foot and pelvis controllers
* Contributors: Arguedas Mikael, Konstantinos Chatzilygeroudis, Vincent Rabaud

0.0.4 (2014-12-04)
------------------
* fixed collision for ankle
* fixed path to xacro file
* fixed hand links names
* Update README.rst
  Added note for missing deppendency
* add missing dependency
* added moveit tutorial
* Contributors: Arguedas Mikael, Mikael ARGUEDAS, margueda

0.0.3 (2014-10-01)
------------------
* update README
* Merge branch 'master' of github.com:ros-nao/nao_moveit_config
* unify group names to match romeo_moveit_config agreement
* Update README.rst
* Update README.rst
* fixed dependencies and update README
* Initial tracks.yaml
* Contributors: Arguedas Mikael, margueda

0.0.2 (2014-09-24)
------------------
* added version argument to every launchfile
* avoid looping animations
* fixed moveit.rviz location
* Merge branch 'master' of github.com:ros-aldebaran/nao_moveit_config
* fixed robot_description xacro path
* Contributors: margueda

0.0.1 (2014-09-18)
------------------
* fix typos
* Update README.md
* Update README.md
* updated model and cleaning
* update README
* new moveit with controllers
* add README
* initial commit of Ioan's modifications
* Contributors: Arguedas Mikael, Vincent Rabaud, margueda
