^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hertzino_driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Builds with OpenCV 4.5.0 - 4.5.2: the timeout properties came with 4.5.3
* The status goes on at status_rate while the login is refused (not connected, and why),
  instead of falling silent for the back-off (up to 30 s)
* A startup band with one limit set keeps the camera's other limit
* A user name that is not valid UTF-8 no longer throws out of the status thread
* A signal no longer cuts a WebSocket wait short

0.1.0 (2026-10-18)
------------------
* Camera client: token login, settings, detections, records, files, WebSocket streams
* hertzino_acoustic_node: detect action, status, settings and record services, spectrum and raw streams
* hertzino_camera_node: RTSP video with automatic path discovery
* Unit tests, fake camera and launch smoke test
