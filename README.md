# RGBenc
### Bytes to RGB pixels encoder/decoder
rgbenc.jar enc \<filename> - encode file to png picture with name \<original extension>_\<timestamp>.png <br>
rgbenc.jar dec \<filename> - decode png picture to normal file<br>
rgbenc.jar key \<yourkey> - set your own AES key (will be saved to aespayload.key)<br>
rgbenc.jar aen \<filename> [--kf <keyfile.key>] or [--ks <key string>] - encrypt the copy of file with AES using current payload and encode it to png<br>
rgbenc.jar ade \<filename> [--kf <keyfile.key>] or [--ks <key string>] - decode png to normal file and decrypt AES using current payload<br>
