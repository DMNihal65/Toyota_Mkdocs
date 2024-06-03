# Code & Services Location: GD Plant

## Introduction

This section shows the code locations and some of the services names and locations.

## Code Locations

### Collector Services

1. **Static Collector**

    - Code Location

            /home/tnga_iot/iiot_project/gd_plant/collectors/cnc_static/main/main_static_collector.py

    - Service Name

        static_collector_gd

    - Service File Location (systemctl daemon file)

            /lib/systemd/system/static_collector_gd.service

1. **Dynamic Collector**

    - Code Location

            /home/tnga_iot/iiot_project/gd_plant/collectors/cnc_dynamic/main/main_dynamic_collector.py

    - Service Name

        dynamic_collector_gd

    - Service File Location (systemctl daemon file)

            /lib/systemd/system/dynamic_collector_gd.service

### Back End Services

The back end in developed in FastApi and deployed as docker container. The codes are available in github and can be downloaded modified and dockerized to make any new changes.


### Front End Services

1. **Apache Server**

The front end is developed using html, css, javascript and react. It is being served by apache server. The codes are available in github and can be downloaded modified and build using node package manager and copied to this location (which the apache server will serve)

    /var/www/tnga_iot