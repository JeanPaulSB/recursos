# recursos
Les recomiendo correr todo en Linux - en Windows se "puede" pero hay menos soporte y un montón de errores - , si tienen alguna duda con cómo instalarlo o algo me pueden contactar.
Todos los recursos se pueden integrar con MATLAB por si quieren hacerlo (yo aún no he detallado cómo se hace pero estuve viendo que hay bastante documentación )
- Gazebo Simulation: Es un entorno de simulación completo con motores de físicas integrados, se puede crear cualquier modelo de robot o vehículo acoplándole una gran variedad de sensores y de esa forma podríamos evaluar cómo se comportan los algoritmos de Inteligencia Artificial y Computer Vision que pretendamos integrar al modelo real. 
  - Instalación: https://staging.gazebosim.org/docs/garden/install
  - Sensores Disponibles: https://gazebosim.org/api/sensors/7/dir_fdd4197b8f2da1bdde1162b7958a70cb.html
  - Modelos y Mundos ya creados: https://app.gazebosim.org/dashboard
 - ROS2 (C++/Python) : Es un middleware o una interfaz entre el hardware y el software del robot o vehículo, es muy usado en la industria y hay un montón de paquetes creados para sistemas de navegación, herramientas de visualización, debugging, logging y demás - tiene más beneficios técnicos que son súper útiles y los pueden encontrar en la documentaición oficial - . Lo usaremos para correr las simulaciones de Gazebo, Gazebo es simplemente el motor de físicas con los modelos y sensores, ROS por otra parte es el driver o el controlador de la simulación que puede recibir y enviar datos a Gazebo. También lo podemos integrar con la PX4.
    - Instalación: https://docs.ros.org/en/humble/Installation.html
    - Integración con PX4: https://docs.px4.io/main/en/ros/
- PX4: Sistema de piloto automático para UAV'S.
  - Introducción: https://docs.px4.io/main/en/getting_started/ (Explican cómo hacer un UAV desde cero y volarlo con la PX4)
  - Cómo añadir un onboard computer para tareas de computer vision e IA: https://docs.px4.io/main/en/companion_computer/
  - General: https://docs.px4.io/main/en/ (Aquí está toda la documentación, pueden ir consultando más cosas según las dudas que tengan, por el momento yo sólo he revisado lo que les listé) 
- Cursos:
  - https://www.udemy.com/course/ros2-cpp-robotics-developer-course/ En este curso explican lo esencial de ROS2 y las herramientas de visualización como Rviz,RQT, explican cómo integrar Gazebo Simulation con ROS2, cómo crear los modelos y los worlds en Gazebo, cómo acoplarle los sensores, me parece muuy completo y ahorra un montón de tiempo porque de esto no es que haya muucha información y con solo leyendo documentación es bastante más tedioso aprender, yo lo compré (la versión C++) y se los puedo compartir, el curso también lo ofertan en Python y sería bueno comprarlo también para que tomen con el que sea que estén más familiarizado. En el curso explican cómo instalar todo.
- Ejemplos de Gazebo, ROS y PX4 funcionando:
  - https://www.youtube.com/watch?v=iZ4LpNeJeNc
  - https://www.youtube.com/watch?v=47U1kpz-B08

  
  
 
