# GCP Docker Machine

This project builds a version of Docker Machine suitable for launching instances in GCP.

The latest official Docker Machine (0.16.1) has a limitation that it does not support creating instances with a specific service account.  The latest source code on master _does_ support this feature but until a release is made we have to build our own.
