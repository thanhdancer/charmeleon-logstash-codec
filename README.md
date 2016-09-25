# charmeleon-logstash-codec
CyWall.config is a conf file of logstash in project CyWall DNS protect on Hackathon 2016 - Risk Solution.

CyWall helps read logs from file, filter some columns neccessary for analytics, and output that columns to mongodb.

INSTALL PLUGIN BEFORE USE CyWall.config:
  1. logstash-input-file
  2. logstash-output-mongodb
  
  
USE:

command (root): bin/logstash -f CyWall.config
