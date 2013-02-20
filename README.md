ipmap
=====
What is it?
-----------
A simple script that takes 2 arguments: ip address map file and config file.

The script takes the map of IPs and finds any instance of the origin IPs in the
config file and replaces it with the destination IP. The map file is a plaintext
file with each line containing an origin IP and a destination IP separated by a
space, i.e.

* 10.0.0.1 10.0.1.1

Why?
----
Because of a boring thing I have to do.
