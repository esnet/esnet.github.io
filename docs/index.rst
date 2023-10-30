.. ESnet Software documentation master file, created by
   sphinx-quickstart on Tue Apr  1 13:30:53 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ESnet Software
==============

The Energy Sciences Network (ESnet_) is a high-performance, unclassified
national network built to support scientific research. Funded by the U.S.
Department of Energy’s Office of Science (SC) and managed by Lawrence Berkeley
National Laboratory, ESnet provides services to more than 40 DOE research
sites, including the entire National Laboratory system, its supercomputing
facilities, and its major scientific instruments. ESnet also connects to 140
research and commercial networks, permitting DOE-funded scientists to
productively collaborate with partners around the world.

As part of supporting ESnet's mission we develop quite a bit of software. This
page has links to each of ESnet's publically visible software projects.

iperf_
    iperf is a TCP, UDP, and SCTP network bandwidth measurement tool.

sLS_ 
    sLS (Simple Lookup Service) is a key-value based distributed database with a REST/JSON API.

`Timeseries Charts`_
    A set of modular charting components used for building flexible interactive charts. It was built for React from the ground up, specifically to visualize timeseries data and network traffic data in particular.

`Network Diagrams`_
    A set of React based mapping components which are used within the ESnet Portal, but are not tied to ESnet, or even to network visualization.

Pond_
    A library build on top of immutable.js to provide basic timeseries functionality within ESnet tools.

ENOS_
    The ESnet Network Operating System, an environment for running
    control plane software for Software Defined Networks.  Contained
    in two repositories, Netshell_ and ENOS_.

GDG_
    Grafana Dash-n-Grab (GDG) -- Dashboard/DataSource Manager. The purpose of this project is to provide an easy-to-use CLI to interact with the grafana API allowing you to backup and restore dashboard, connections (formerly datasources), and other entities.


.. _ESnet: http://www.es.net/
.. _iperf: http://software.es.net/iperf/
.. _GDG: http://software.es.net/gdg/
.. _sLS: http://software.es.net/simple-lookup-service/
.. _Timeseries Charts: http://software.es.net/react-timeseries-charts/
.. _Network Diagrams: http://software.es.net/react-network-diagrams/
.. _Pond: http://software.es.net/pond/
.. _Netshell: https://github.com/esnet/netshell
.. _ENOS: https://github.com/esnet/enos
.. toctree::
   :maxdepth: 2

