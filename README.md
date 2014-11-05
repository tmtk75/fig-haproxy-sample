# README

Provide how to ~un following linked containers with fig.

                  .---> app:5000 ---,
	          |                 |
    haproxy:80 ---+                 +---> redis
	          |                 |
                  `---> app:5000 ---'

