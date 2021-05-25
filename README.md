# video

ffmpeg -i /home/khoand58/gentelella-master-flask/video/video.mp4 -codec: copy -start_number 0 -hls_time 10 -hls_list_size 0 -f hls filename.m3u8
