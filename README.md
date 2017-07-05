# threaded_downloader
A multithreaded python downloader that allows multiple connections to be used to download a file. 

## commandline usage

`./threaded_downloader.py <url>`

## as module

```


downloader = ThreadedDownloader(<dir_to_download_into>)
downloader.multi_part_download_file(<file_name>, url)


```

## features-in-progress

Adding CRC32/MD5 verification of download. 
