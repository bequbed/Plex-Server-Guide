Recommended Rclone Mount Settings for mounting a Cloud Drive (OneDrive, Google Drive etc)

mount encrypted_union: O:  --config "C:\Users\Server\AppData\Roaming\rclone\rclone.conf" --vfs-cache-mode full --vfs-cache-max-size 450G --vfs-read-ahead 2G --vfs-cache-max-age 168h --buffer-size 1G --dir-cache-time 168h --vfs-read-chunk-size 128M --vfs-read-chunk-size-limit off --attr-timeout 5000h --poll-interval 0 --cache-dir G:\Rclone\MountCache --log-level ERROR --log-file="C:\rclone\onedrivemcrypt.txt" --user-agent "ISV|rclone.org|rclone/v1.68.1" --no-checksum --no-modtime --rc --rc-web-gui --rc-addr=127.0.0.1:5572 --rc-user=admin --rc-pass=xxxx

Reverse proxy setup to securely access local web server page remotely 

https://www.cloudflare.com/products/tunnel/

Recommend purchasing a domain through Cloudflare directly as they are sold at cost price with no markup and minimal yearly subscription to keep the domain


Remote monitoring of the server 

Refer to this: https://github.com/nicolargo/glances
