# Flowdroid

This is a docker file for Flowdroid
1) Pull the repository ```docker pull maqsoodahmad/flowdroid-docker```
2) Start container ```docker run -it --rm -v /path-to/the-dir/containing-apks/:/opt/flowdroid maqsoodahmad/flowdroid-docker bash```
3) Run Flowdroid ```~$ flowdroid /opt/flowdroid/demo.apk /opt/android-sdk-linux/platforms/android-7.0/android.jar```
