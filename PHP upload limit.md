## memory_limit
This sets the maximum amount of memory in bytes that a script is allowed to allocate.
Default size: 128M

## post_max_size (must be greater than upload_max_filesize)
Sets max size of post data allowed. This setting also affects file upload.
Default size: 8M

## upload_max_filesize
The maximum size of an uploaded file. 
Default size: 2M

## max_execution_time
This sets the maximum time in seconds a script is allowed to run before it is terminated by the parser.
Default setting: 30

## max_input_time
This sets the maximum time in seconds a script is allowed to parse input data, like POST and GET. Timing begins at the moment PHP is invoked at the server and ends when execution begins. The default setting is -1, which means that max_execution_time is used instead. Set to 0 to allow unlimited time.
